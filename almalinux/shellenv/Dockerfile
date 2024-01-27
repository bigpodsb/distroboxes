FROM ghcr.io/bigpod98/bigpodsb/distroboxes/dependency:latest AS dependency

FROM ghcr.io/bigpod98/bigpodsb/distroboxes/almalinuxbased/baseenv:latest
RUN dnf install -y bash fish
RUN mkdir /dependency
COPY --from=dependency /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency