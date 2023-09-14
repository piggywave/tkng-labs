FROM alpine

RUN mkdir /opt/bin

WORKDIR /opt/bin

ADD https://github.com/containernetworking/plugins/releases/download/v1.3.0/cni-plugins-linux-amd64-v1.3.0.tgz ./

RUN tar zxvf cni-plugins-linux-amd64-v1.3.0.tgz && rm cni-plugins-linux-amd64-v1.3.0.tgz


