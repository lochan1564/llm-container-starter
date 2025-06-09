# .devcontainer/Dockerfile

FROM python:3.11-slim

RUN apt-get update && apt-get install -y \
    git curl vim nano htop build-essential \
    && apt-get clean

# Install Poetry
ENV POETRY_VERSION=1.8.2
RUN curl -sSL https://install.python-poetry.org | python3 - && \
    ln -s ~/.local/bin/poetry /usr/local/bin/poetry

# Set working directory
WORKDIR /workspace

# Install dependencies later via postCreateCommand

