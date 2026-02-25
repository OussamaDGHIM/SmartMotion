FROM ubuntu:24.04
RUN apt update && apt install build-essential chrpath cpio debianutils diffstat file gawk gcc git iputils-ping libacl1 liblz4-tool locales python3 python3-git python3-jinja2 python3-pexpect python3-pip python3-subunit socat texinfo unzip wget xz-utils zstd -y 

WORKDIR /project_yocto
WORKDIR /project_yocto/layers

RUN git clone -b scarthgap git://git.yoctoproject.org/poky.git 

#COPY README.md /usr/
#ADD kas /usr/
#ENV PATH="/usr:${PATH}"
#EXPOSE 80
#CMD ["source", "poky/oe-init-build-env","build"]
