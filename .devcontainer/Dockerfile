FROM mcr.microsoft.com/devcontainers/go:1-1.23-bookworm

USER vscode
RUN . /usr/local/share/nvm/nvm.sh && nvm install 12.13
USER root
# TODO: clear cache afterwards?
# RUN apt get update && apt install -y libgtk-3-dev libwebkit2gtk-4.0-dev libappindicator3-dev
