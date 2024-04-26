FROM alpine:latest
RUN apk add --no-cache curl
WORKDIR /download
COPY entrypoint.sh .
RUN chmod +x entrypoint.sh
ENTRYPOINT ["./entrypoint.sh"]
