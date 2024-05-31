FROM mambaorg/micromamba:focal

USER root
RUN apt-get update && apt-get install -y --no-install-recommends \
    pandoc \
    pandoc-citeproc \
    curl \
    gdebi-core \
    && rm -rf /var/lib/apt/lists/*

RUN curl -LO https://quarto.org/download/latest/quarto-linux-amd64.deb
RUN gdebi --non-interactive quarto-linux-amd64.deb

USER $MAMBA_USER

COPY --chown=$MAMBA_USER:$MAMBA_USER environment.yml /tmp/env.yaml

RUN micromamba install --yes --file /tmp/env.yaml && \
    micromamba clean --all --yes

RUN cd $CONDA_PREFIX && \
    mkdir -p ./etc/conda/activate.d && \
    mkdir -p ./etc/conda/deactivate.d && \
    touch ./etc/conda/activate.d/env_vars.sh && \
    touch ./etc/conda/deactivate.d/env_vars.sh

ENTRYPOINT ["/usr/local/bin/_entrypoint.sh"]