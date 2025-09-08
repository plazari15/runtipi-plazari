ARG PAPERLESS_VERSION=2.18.4
FROM ghcr.io/paperless-ngx/paperless-ngx:${PAPERLESS_VERSION}

USER root
RUN apt-get update && \
    apt-get install -y --no-install-recommends tesseract-ocr-por && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

USER paperless
