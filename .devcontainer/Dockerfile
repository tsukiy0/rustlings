FROM mcr.microsoft.com/vscode/devcontainers/rust:0-buster

# apt
RUN apt-get update && apt-get -y install --no-install-recommends \
    vim \
    tmux

# shell
RUN echo "bindkey -v" >> /home/vscode/.zshrc
RUN echo "bindkey '^R' history-incremental-search-backward" >> /home/vscode/.zshrc
