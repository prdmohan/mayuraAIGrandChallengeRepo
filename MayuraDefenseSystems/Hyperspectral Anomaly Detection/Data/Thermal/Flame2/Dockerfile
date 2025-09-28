# hash:sha256:0767af246ba3f4ee1ec5374abf5c081120491389f1af16d2cd6fc057d5014000
FROM registry.codeocean.com/codeocean/miniconda3:4.9.2-cuda11.7.0-cudnn8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

COPY postInstall /
RUN /postInstall
