# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.245.0/containers/python-3.14/.devcontainer/base.Dockerfile

# [Choice] Python version (use -bullseye variants on local arm64/Apple Silicon): 3.14, 3.13, 3.12, 3.11, 3.10, 3.9, 3.8, 3.7, 3.6
ARG VARIANT="3.14"
FROM mcr.microsoft.com/devcontainers/python:${VARIANT}-bookworm

# [Optional] If your requirements don't change often, uncomment this section to add them to the image layer
# COPY requirements.txt /tmp/pip-tmp/
# RUN pip install --no-cache-dir --force-reinstall -r /tmp/pip-tmp/requirements.txt \
#    && rm -rf /tmp/pip-tmp/

# [Optional] Uncomment this section to install additional OS packages
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment this line to install global node packages.
# RUN su vscode -c "source /usr/share/nvm/nvm.sh && npm install -g <your-package-here>" 2>&1