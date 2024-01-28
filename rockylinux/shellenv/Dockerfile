FROM ghcr.io/bigpod98/bigpodsb/distroboxes/rockylinuxbased/baseenv:latest
RUN dnf install -y bash
RUN mkdir /dependency
COPY --from=dependency /* /dependency/
RUN bash /dependency/host-exec-links
RUN rm -rf /dependency