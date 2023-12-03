FROM mambaorg/micromamba:1.5.3

USER root
# ffmpeg - to run mujoco renderer
# texlive-latex-extra texlive-fonts-recommended cm-super - to have a pretty matplotlib
RUN apt-get update -y && apt-get install git ffmpeg texlive-latex-extra texlive-fonts-recommended cm-super dvipng -y

USER $MAMBA_USER

COPY --chown=$MAMBA_USER:$MAMBA_USER environment.yml /tmp/env.yaml
RUN micromamba install --yes --file /tmp/env.yaml && \
    micromamba clean --all --yes

ARG MAMBA_DOCKERFILE_ACTIVATE=1  # (otherwise python will not be found)

# create needed files
RUN cd $CONDA_PREFIX && \
    mkdir -p ./etc/conda/activate.d && \
    mkdir -p ./etc/conda/deactivate.d && \
    touch ./etc/conda/activate.d/env_vars.sh && \
    touch ./etc/conda/deactivate.d/env_vars.sh

RUN echo "export LD_LIBRARY_PATH=$CONDA_PREFIX/lib:$LD_LIBRARY_PATH:$(python3 -m cmeel lib)" >> $CONDA_PREFIX/etc/conda/activate.d/env_vars.sh

# change default matplotlib style
COPY .config/style.mplstyle /home/mambauser/.config/matplotlib/matplotlibrc

ENTRYPOINT ["/usr/local/bin/_entrypoint.sh"]