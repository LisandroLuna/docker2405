FROM ubuntu:20.04

RUN apt update
RUN apt install nano -y

WORKDIR /srv

COPY script.sh ./
RUN chmod +x ./script.sh

EXPOSE 9999
EXPOSE 9998

CMD ["./script.sh"]