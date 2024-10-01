# Use an Ubuntu base image
FROM ubuntu:20.04

# Set environment variables to suppress interactive prompts
ENV DEBIAN_FRONTEND=noninteractive
ENV TZ=Etc/UTC

# Install dependencies
RUN apt-get update && apt-get install -y \
    texlive-full \
    texlive-latex-extra \
    latexmk \
    ghostscript \
    && rm -rf /var/lib/apt/lists/*

# Set LaTeX as the default environment
ENV PATH="/usr/local/texlive/2020/bin/x86_64-linux:${PATH}"
