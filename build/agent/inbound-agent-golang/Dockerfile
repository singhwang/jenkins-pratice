FROM core.harbor.xxx.com/jenkins/jenkins-inbound-agent-base:4.6-1
MAINTAINER wangxin_0611@126.com

ADD https://studygolang.com/dl/golang/go1.15.3.linux-amd64.tar.gz /opt/
RUN tar -zxvf /opt/go1.15.3.linux-amd64.tar.gz -C /opt/ && \ 
    rm -rf /opt/go1.15.3.linux-amd64.tar.gz && \
    apt-get update && \
    apt-get install -y git
ENV PATH /opt/go/bin:$PATH

