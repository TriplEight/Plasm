# Use parity rust-builder as our base image.
FROM parity/rust-builder

RUN apt-get update && \
    apt-get install -y \
        clang \
        llvm

WORKDIR /opt
