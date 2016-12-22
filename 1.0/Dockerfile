# VERSION 1.0.0
# AUTHOR:         Nicolas Lamirault <nicolas.lamirault@gmail.com>
# DESCRIPTION:    zeiot/rpi-nats_exporter

FROM resin/armv7hf-debian:jessie
MAINTAINER Nicolas Lamirault <nicolas.lamirault@gmail.com>

ENV NATS_EXPORTER_VERSION 1.0.0

ADD https://github.com/lovoo/nats_exporter/releases/download/1.0.0/nats_exporter_linux_arm /pihole_exporter
RUN chmod +x /pihole_exporter

EXPOSE     9118
EXPOSE     8222

ENTRYPOINT [ "/nats_exporter" ]
