FROM golang:1.22

WORKDIR /app

COPY . .

RUN go mod init service1 2>/dev/null || true

RUN go build -o service1 .

EXPOSE 8001

CMD ["./service1"]

