ARG BUILD_FROM
FROM $BUILD_FROM

ARG DDNSTO_VERSION="3.0.5"
ARG BUILD_ARCH

ADD binary/ddnsto-${DDNSTO_VERSION}-linux-${BUILD_ARCH}.tar.gz /usr/bin/
# RUN chmod +x /usr/bin/ddnsto
COPY rootfs /