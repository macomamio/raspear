FROM alpine:3.8

RUN mkdir -p /app/raspear
WORKDIR /app/raspear

RUN pwd && env
RUN apk --update add bash ruby nginx


CMD ["nginx", "-g", "daemon off;"]
