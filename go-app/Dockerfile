FROM golang:1.16-alpine

WORKDIR /app

COPY . .

RUN go build -o main .

Expose 80

CMD ["./main"]