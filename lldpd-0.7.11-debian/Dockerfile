FROM debian:jessie-slim

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install --no-install-recommends -y lldpd

ENTRYPOINT ["lldpd", "-d"]
CMD ["-k"]
