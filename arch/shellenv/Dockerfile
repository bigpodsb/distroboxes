FROM ghcr.io/bigpod98/bigpodsb/distroboxes/dependency:latest AS dependency

FROM ghcr.io/bigpod98/bigpodsb/distroboxes/archbased/baseenv:latest
RUN pacman -Syyu --noconfirm
RUN pacman -S --noconfirm bash fish
RUN mkdir /dependency
COPY --from=dependency /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency