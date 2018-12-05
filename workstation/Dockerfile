FROM fedora:29
WORKDIR /root

COPY . /root
RUN dnf update --refresh -y && \
    dnf install\
    flatpack\ 
    git\ 
    vim\ 
    ranger\ 
    curl\ 
    wget\
    python\
    python3\
    ansible\
    zsh\
    stow\
    fish -y 
CMD "bash"