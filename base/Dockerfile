#FROM alpine:latest as base
FROM ubuntu:16.04 as base
RUN pwd
RUN which sh
RUN which bash
RUN \
   apt-get update && \
   apt-get install -y python python-dev python-pip python-virtualenv vim && \
   rm -rf /var/lib/apt/lists/*
#RUN apt-get update
#RUN apt-get upgrade
#RUN apt-get add bash
#
##RUN apk --no-cache --update upgrade && apk --no-cache add ca-certificates

#FROM scratch
#COPY --from=base /etc/ssl/certs/ca-certificates.crt /etc/ssl/certs/ca-certificates.crt
