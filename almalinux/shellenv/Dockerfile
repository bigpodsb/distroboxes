FROM ghcr.io/bigpod98/bigpodsb/distroboxes/dependency:latest AS dependency

FROM ghcr.io/bigpod98/bigpodsb/distroboxes/almalinuxbased/standardenv:latest
RUN dnf install -y bash fish
RUN mkdir /dependency
COPY /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency