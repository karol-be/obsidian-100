FROM mcr.microsoft.com/devcontainers/dotnet:8.0
RUN sudo apt-get update && apt-get upgrade

RUN curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt-get install -y nodejs
RUN git config --global core.autocrlf