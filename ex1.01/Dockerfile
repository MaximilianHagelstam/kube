FROM golang:1.23-alpine

WORKDIR /app

COPY go.mod .

COPY main.go .

RUN go build -o bin .

CMD ["/app/bin"]
