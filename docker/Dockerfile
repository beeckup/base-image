FROM golang:alpine
RUN apk add --no-cache git mysql-client openssl curl python py-pip coreutils bash \
    && go get github.com/robfig/cron \
    && go get github.com/aws/aws-sdk-go \
    && go get github.com/go-sql-driver/mysql