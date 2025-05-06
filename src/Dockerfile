# For deployment on render.com and others
FROM golang:latest

WORKDIR /

COPY . .

RUN go build Athanatos

EXPOSE 8080

CMD [ "./Athanatos" ]
