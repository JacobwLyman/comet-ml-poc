FROM ubuntu:22.04
ENV DEBIAN_FRONTEND=noninteractive

# install base utils
RUN apt-get update
RUN apt-get install -y iputils-ping dnsutils jq vim curl unzip git wget

# get bash completion for git
RUN echo 'source /usr/share/bash-completion/completions/git' >> /root/.bashrc

# Python Essentials
RUN apt-get install -y python3.10 python3-pip python-is-python3