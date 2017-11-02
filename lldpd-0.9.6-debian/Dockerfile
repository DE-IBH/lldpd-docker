FROM debian:stretch-slim

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install --no-install-recommends -y lldpd

ENTRYPOINT ["lldp", "-d"]
CMD ["-k"]
