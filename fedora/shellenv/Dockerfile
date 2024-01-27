FROM ghcr.io/bigpod98/bigpodsb/distroboxes/fedorabased/baseenv:latest
RUN dnf5 install -y bash fish
RUN sudo ln -s /usr/bin/distrobox-host-exec /usr/bin/flatpak
RUN sudo ln -s /usr/bin/distrobox-host-exec /usr/bin/podman
RUN sudo ln -s /usr/bin/dnf5 /usr/bin/dnf
