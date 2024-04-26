FROM alpine:latest
RUN apk add --no-cache curl
WORKDIR /script
COPY entrypoint.sh .
RUN chmod +x /entrypoint.sh && pwd && ls -la
ENTRYPOINT ["/script/entrypoint.sh"]
