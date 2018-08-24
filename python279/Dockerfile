FROM ubuntu:18.04

RUN apt-get update && apt-get install -y \
	wget \
	build-essential \
	vim \
 && rm -rf /var/lib/apt/lists/*

RUN wget https://www.python.org/ftp/python/2.7.9/Python-2.7.9.tgz

RUN tar -xvf Python-2.7.9.tgz

WORKDIR /Python-2.7.9

RUN ./configure

RUN make

RUN make install

WORKDIR /