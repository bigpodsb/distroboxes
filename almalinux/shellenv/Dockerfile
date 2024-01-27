FROM ghcr.io/bigpod98/bigpodsb/distroboxes/almalinuxbased/standardenv:latest
RUN dnf install -y bash
COPY ./host-exec-links /
RUN bash /host-exec-links && rm -rf host-exec-links