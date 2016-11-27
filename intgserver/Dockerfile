FROM alpine:latest

MAINTAINER Celvva Vetrivelu <celvaprabu@gmail.com>

WORKDIR "/opt"

ADD .docker_build/intgserver /opt/bin/intg_server
ADD ./templates /opt/templates
ADD ./static /opt/static

CMD ["/opt/bin/intg_server"]

