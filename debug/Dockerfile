FROM almalinux:8
RUN dnf install -y \
    telnet \
    iputils \
    net-tools \
    && dnf clean all

RUN useradd ec2-user
USER ec2-user
CMD [ "sleep","100000" ]