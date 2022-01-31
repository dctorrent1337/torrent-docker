FROM kalilinux/kali-rolling

ENV DEBIAN_FRONTEND=noninteractive 

RUN apt-get update -qy &&\
    apt-get dist-upgrade -qy &&\
    apt-get autoremove -qy &&\
    apt-get install -qy curl ncat nmap

ENV DEBIAN_FRONTEND=
