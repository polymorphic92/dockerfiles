FROM python
WORKDIR /audio
RUN apt update && \ 
    apt upgrade -y && \
    apt install curl  ffmpeg libav-tools -y && \ 
    curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl && \
    chmod a+rx /usr/local/bin/youtube-dl 
ENTRYPOINT ["youtube-dl"]
CMD ["--help"]