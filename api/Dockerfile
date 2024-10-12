FROM golang:1.23.2

WORKDIR /app

COPY go.mod ./
RUN go mod download

CMD ["go", "run", "main.go"]