FROM mambaorg/micromamba:1.5.3

COPY --chown=$MAMBA_USER:$MAMBA_USER environment.yml /tmp/env.yaml
RUN micromamba install --yes --file /tmp/env.yaml && \
    micromamba clean --all --yes

ARG MAMBA_DOCKERFILE_ACTIVATE=1  # (otherwise python will not be found)

USER root
RUN apt-get update -y && apt-get install ffmpeg -y
USER $MAMBA_USER

# create needed files
RUN cd $CONDA_PREFIX && \
    mkdir -p ./etc/conda/activate.d && \
    mkdir -p ./etc/conda/deactivate.d && \
    touch ./etc/conda/activate.d/env_vars.sh && \
    touch ./etc/conda/deactivate.d/env_vars.sh

RUN echo "export LD_LIBRARY_PATH=$CONDA_PREFIX/lib:$LD_LIBRARY_PATH:$(python3 -m cmeel lib)" >> $CONDA_PREFIX/etc/conda/activate.d/env_vars.sh

# Copy the matplotlibrc file to the Matplotlib folder
RUN python -c "import matplotlib; print(matplotlib.get_configdir())" > /tmp/matplotlib_conf_path.txt
RUN DESTINATION_PATH=$(cat /tmp/matplotlib_conf_path.txt)
COPY matplotlibrc $DESTINATION_PATH/matplotlibrc
COPY style.mplstyle $DESTINATION_PATH/style.mplstyle

ENTRYPOINT ["/usr/local/bin/_entrypoint.sh"]