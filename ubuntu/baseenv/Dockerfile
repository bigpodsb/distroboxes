FROM ubuntu:latest
RUN apt update && apt upgrade -y && apt install -y --no-install-recommends 
RUN apt install -y fish apt-utils bash-completion bc bzip2 curl dialog diffutils findutils gnupg 
RUN apt install -y gnupg2 gpgsm hostname iproute2 iputils-ping keyutils language-pack-en less libcap2-bin 
RUN apt install -y libkrb5-3 libnss-mdns libnss-myhostname libvte-2.9*-common locales lsof 
RUN apt install -y man-db manpages mtr ncurses-base openssh-client passwd pigz pinentry-curses procps rsync 
RUN apt install -y sudo tcpdump time traceroute tree tzdata unzip util-linux wget xauth xz-utils zip libgl1 libegl1-mesa 
RUN apt install -y libgl1-mesa-glx libegl1 libglx-mesa0 libvulkan1 mesa-vulkan-drivers
RUN userdel ubuntu
