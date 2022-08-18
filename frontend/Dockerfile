FROM golang:1.19.0

WORKDIR /usr/src/app

COPY . .
COPY ./static ./static/
COPY ./templates ./templates/

RUN chmod +x .

EXPOSE 8080/tcp

CMD ["go", "build"]
CMD ["go", "run", "frontend"]