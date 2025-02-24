FROM redhat/ubi9:latest 

RUN dnf update -y && \
    dnf upgrade -y && \
    dnf install -y python3.12 python3.12-pip python3.12-setuptools && \
    dnf clean dbcache && dnf clean all

