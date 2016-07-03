# docker build -t rocci-cli-ubuntu .
FROM ubuntu:14.04
MAINTAINER Mario David <mariojmdavid@gmail.com>
LABEL description="Container image to run rOCCI cli"

# Install ansible repository
RUN locale-gen en_US.UTF-8
RUN apt-get update -y
RUN apt-get install software-properties-common -y
RUN apt-add-repository ppa:ansible/ansible
RUN apt-get update && apt-get install -y \
    ansible

RUN ansible-galaxy install LIP-Computing.rocci-cli && \
    ansible-playbook -i /etc/ansible/roles/LIP-Computing.rocci-cli/tests/inventory \
    /etc/ansible/roles/LIP-Computing.rocci-cli/tests/test.yml
