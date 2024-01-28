FROM ghcr.io/bigpod98/bigpodsb/distroboxes/dependency:latest AS dependency

FROM ghcr.io/bigpod98/bigpodsb/distroboxes/fedorabased/baseenv:latest
RUN dnf5 install -y bash fish
RUN mkdir /dependency
COPY --from=dependency /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency
RUN sudo ln -s /usr/bin/dnf5 /usr/bin/dnf
