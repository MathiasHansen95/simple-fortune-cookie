FROM golang:1.19.0

WORKDIR /usr/src/app

COPY . .

RUN chmod +x .

EXPOSE 9000/tcp

CMD ["go", "build"] 
CMD ["go", "run", "backend"] 


