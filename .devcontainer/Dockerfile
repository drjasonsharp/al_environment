FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    nasm \
    gcc \
    gdb \
    make \
    binutils \
    strace \
    ltrace \
    git \
    vim \
    nano \
    less \
    curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

CMD ["/bin/bash"]