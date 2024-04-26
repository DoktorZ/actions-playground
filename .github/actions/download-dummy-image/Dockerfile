FROM alpine:latest
RUN apk add --no-cache curl
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x entrypoint.sh && ls -la
ENTRYPOINT ["pwd", "ls -la", "/entrypoint.sh"]
