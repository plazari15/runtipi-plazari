FROM ghcr.io/paperless-ngx/paperless-ngx:2.18.4

USER root

RUN apt-get update && \
    apt-get install -y tesseract-ocr-por && \
    rm -rf /var/lib/apt/lists/*

USER paperless
