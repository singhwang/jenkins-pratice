FROM jenkins/jenkins:2.263.3-lts
MAINTAINER wangxin_0611@126.com

# Preinstalling Plugins
RUN rm -rf /usr/share/jenkins/ref/plugins/org.jenkins-ci.plugins.lock
COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt
