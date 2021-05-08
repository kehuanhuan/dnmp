FROM ubuntu:16.04

MAINTAINER  huanhuan <1152018701@qq.com>

RUN \
    wget https://artifacts.elastic.co/downloads/beats/filebeat/filebeat-7.0.0-linux-x86_64.tar.gz && \
    tar -zxvf filebeat-7.0.0-linux-x86_64.tar.gz && \
    mv filebeat-7.0.0-linux-x86_64 /usr/local/filebeat && \
    rm -rf filebeat-7.0.0-linux-x86_64

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN echo 'Asia/Shanghai' > /etc/timezone