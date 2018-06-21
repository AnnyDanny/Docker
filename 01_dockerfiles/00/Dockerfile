#FROM  confluent/postgres-bw:0.1

#RUN ["apt-get", "update"]
#RUN ["apt-get", "install", "-y", "vim"]
#docker build .

FROM alpine

RUN apk update
RUN apk add emacs

ENTRYPOINT emacs