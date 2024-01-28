FROM ghcr.io/bigpod98/bigpodsb/distroboxes/opensusebased/baseenv:latest
RUN zypper install -n bash fish
RUN mkdir /dependency
COPY --from=dependency /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency