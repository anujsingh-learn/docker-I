FROM ubuntu
RUN apt-get update && DEBIAN_FRONTEND="noninteractive" apt-get install -y tzdata
RUN apt-get install -y apache2
ENTRYPOINT apachectl -D FOREGROUND
ADD . /var/www/html/
