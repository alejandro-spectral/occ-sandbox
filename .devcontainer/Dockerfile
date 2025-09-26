FROM mcr.microsoft.com/devcontainers/cpp:ubuntu-22.04
RUN apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y \
    git \
    cmake \
    pkg-config \
    build-essential \
    libocct-foundation-dev \
    libocct-modeling-data-dev \
    libocct-modeling-algorithms-dev \
    libocct-data-exchange-dev \
    libocct-ocaf-dev \
    libocct-visualization-dev \
    libocct-draw-dev \
    libtbb-dev \
    && rm -rf /var/lib/apt/lists/*
