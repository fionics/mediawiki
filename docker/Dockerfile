FROM ubuntu:latest

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y nginx php-fpm && ln -fs /usr/share/zoneinfo/Europe/Tirane /etc/localtime && dpkg-reconfigure --frontend noninteractive tzdata

