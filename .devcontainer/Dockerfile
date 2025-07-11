FROM mcr.microsoft.com/devcontainers/go:1-1.23-bookworm

# TODO: clear apt cache afterwards?
RUN apt update && apt install -y libgtk-3-dev libwebkit2gtk-4.0-dev libayatana-appindicator3-dev

# Node v22 is LTS
RUN . /usr/local/share/nvm/nvm.sh && nvm install 22 && nvm use 22
