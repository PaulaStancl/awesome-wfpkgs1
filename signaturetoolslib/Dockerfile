FROM alpine:latest

LABEL org.opencontainers.image.source https://github.com/paulastancl/awesome-wfpkgs1

ENV PATH="/tools:${PATH}"

COPY *.py /tools/

ENTRYPOINT ["/usr/bin/env"]

CMD ["/bin/bash"]
