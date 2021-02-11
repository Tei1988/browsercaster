ARG BASE_IMAGE
FROM ${BASE_IMAGE}

RUN apk --no-cache add \
        tini \
        udev \
        chromium \
        ffmpeg \
        xvfb \
        dbus && \
    dbus-uuidgen && \
    adduser -S browsercaster
USER browsercaster
