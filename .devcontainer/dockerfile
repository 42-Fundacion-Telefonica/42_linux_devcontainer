#import a ubuntu 22.04 image
FROM ubuntu:22.04

#install 42 schools minimal packages
RUN apt-get update && apt-get install -y \
    git \
    vim \
    curl \
    clang \
    build-essential \
    libssl-dev \
    libffi-dev \
    python3-dev \
    python3-pip \
    python3-venv \
    python3-wheel \
    python3-setuptools \
    && python3 -m pip install --upgrade pip \
    && python3 -m pip install norminette