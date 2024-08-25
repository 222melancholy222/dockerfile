FROM ubuntu:22.04

RUN mkdir -p /opt/app &&\
  mkdir -p /opt/app/data

COPY script.sh /opt/app/script.sh
RUN chmod +x /opt/app/script.sh

VOLUME /opt/app/data

WORKDIR /opt/app

CMD ["./script.sh"]
