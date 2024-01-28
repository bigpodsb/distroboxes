FROM ghcr.io/bigpod98/bigpodsb/distroboxes/debianbased/baseenv:latest
RUN apt install -y bash fish
RUN mkdir /dependency
COPY --from=dependency /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency
