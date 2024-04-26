FROM alpine:latest
RUN apk add --no-cache curl
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /scripts/entrypoint.sh && pwd && ls -la
ENTRYPOINT pwd && ls -la && /entrypoint.sh
