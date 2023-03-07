FROM ubuntu:lunar
RUN apt update
RUN apt upgrade -y
RUN apt autoremove -y vim vim-runtime vim-tiny vim-common 
RUN apt install -y --no-install-recommends nano tar zip unzip jq fish caja direnv 
RUN apt install -y --no-install-recommends bc curl diffutils findutils less passwd pinentry-tty sudo util-linux wget ncurses-base ncurses-bin 