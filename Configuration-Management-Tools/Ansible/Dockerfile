FROM ubuntu:latest

# Install prerequisities for Ansible
RUN apt-get update
RUN apt-get -y install python3 python3-nacl python3-pip libffi-dev openssh-client vim

# Install ansible
RUN pip3 install ansible