FROM httpd:2.4


WORKDIR /usr/www/apache2/htdocs
COPY index.html .
WORKDIR /usr/www/apache2/conf



EXPOSE 9999

ENV CONTAINER="docker"

CMD echo $CONTAINER