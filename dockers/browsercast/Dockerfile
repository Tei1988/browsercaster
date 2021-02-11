ARG BASE_IMAGE
FROM ${BASE_IMAGE}

RUN apk --no-cache add \
        chromium \
        ffmpeg \
        udev \
        xvfb \
        dbus && \
    dbus-uuidgen && \
    adduser -S browsercaster
USER browsercaster
