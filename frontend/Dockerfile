FROM golang:1.19.0

WORKDIR /app

COPY . .
COPY ./static ./static/
COPY ./templates ./templates/

RUN chmod +x .

EXPOSE 8080/tcp

CMD go build
CMD BACKEND_DNS="backend" go run frontend