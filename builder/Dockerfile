FROM gliderlabs/alpine:3.2
RUN apk-install curl wget tar bash
COPY scripts/mkimage-alpine.bash scripts/apk-install /
ENTRYPOINT ["/mkimage-alpine.bash"]
