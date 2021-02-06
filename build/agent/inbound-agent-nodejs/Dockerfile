FROM core.harbor.xxx.com/jenkins/jenkins-inbound-agent-base:4.6-1
MAINTAINER wangxin_0611@126.com

RUN apt-get update && \
    apt-get install -y git && \
    curl -sL https://deb.nodesource.com/setup_10.x | bash - && \
    apt-get install -y nodejs

