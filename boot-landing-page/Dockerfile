#HTTPD server with Start Bootstrap landing page template.

FROM httpd:alpine

MAINTAINER steve

RUN apk update 
RUN apk add git 

RUN git clone https://github.com/BlackrockDigital/startbootstrap-landing-page.git
RUN cp -r startbootstrap-landing-page/. /usr/local/apache2/htdocs/
