FROM ghcr.io/bigpod98/bigpodsb/distroboxes/archbased/standardenv:latest
RUN pacman -S --noconfirm bash fish
RUN sudo ln -s /usr/bin/distrobox-host-exec /usr/bin/flatpak
RUN sudo ln -s /usr/bin/distrobox-host-exec /usr/bin/podman
