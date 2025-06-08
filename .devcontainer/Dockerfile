# .devcontainer/Dockerfile

FROM python:3.11-slim

# Install system tools
RUN apt-get update && apt-get install -y \
    git curl vim nano htop \
    && apt-get clean

# Optional: pre-create workspace folders
# RUN mkdir -p /workspace/src /workspace/data /workspace/notebooks

# Set the working directory
WORKDIR /workspace
