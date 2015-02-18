FROM ubuntu:14.04

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get -y update && \
    apt-get -y --quiet upgrade && \
    apt-get -y --quiet install libxml2-dev libxslt1-dev git python python-setuptools python-dev build-essential libz-dev lsb openssl dnsutils curl rsync iptraf-ng rdiff ethtool iotop libtool pv curl unzip zip inotify-tools && \
    apt-get -y --quiet install python-software-properties software-properties-common htop && \
    easy_install pip && \
    apt-get -y update && \
    apt-get -y clean


