FROM jenkins/jenkins:alpine
MAINTAINER swetank01 <swetank@farnodes.com>
USER root
RUN apk add maven 
COPY plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/plugins.txt
USER jenkins
EXPOSE 8080
