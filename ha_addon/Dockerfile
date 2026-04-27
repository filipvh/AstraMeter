# syntax=docker/dockerfile:1
ARG BUILD_FROM
ARG BUILD_VERSION

# Use the upstream prebuilt addon image as the base.
# Pick a tag that matches the upstream version you want to track.
FROM ghcr.io/tomquist/astrameter-addon:next

# Overlay our customized run.sh
COPY run.sh /run.sh
RUN chmod a+x /run.sh
