FROM ubuntu:latest

RUN apt update \
    && apt install -y \
       build-essential \
       wget \
       texlive-full \
       ghostscript
       

RUN["chmod", "+x", "/entrypoint.sh"]

ENTRYPOINT["/entrypoint.sh"]


