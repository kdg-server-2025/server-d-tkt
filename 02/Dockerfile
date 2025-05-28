FROM golang:alpine
WORKDIR /02
COPY main.go .
RUN go build -o main main.go
CMD ["./main"]