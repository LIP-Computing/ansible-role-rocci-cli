# docker build --rm -t rocci-cli .
FROM lipcomputing/ansible-ubuntu14.04
MAINTAINER Mario David <mariojmdavid@gmail.com>
LABEL description="Container image to run rOCCI cli"

RUN ansible-galaxy install LIP-Computing.rocci-cli && \
    ansible-playbook /etc/ansible/roles/LIP-Computing.rocci-cli/tests/rocci-cli.yml

