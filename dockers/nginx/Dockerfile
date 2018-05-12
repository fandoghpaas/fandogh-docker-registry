from nginx:latest

RUN apt-get update
RUN apt-get -y install apache2-utils

COPY run_nginx.sh ./run_nginx.sh

ENTRYPOINT ["./run_nginx.sh"]
