FROM alpine:latest
RUN apk add --no-cache curl
COPY entrypoint.sh .
RUN chmod +x entrypoint.sh && ls -la
ENTRYPOINT ["./entrypoint.sh"]
