FROM golang
WORKDIR /app
COPY *.go ./
RUN go build main.go
EXPOSE 8080
CMD ["./main"]