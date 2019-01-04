FROM debian

RUN apt update \
 && apt-get -y \
    install nginx \
 && rm -rf /var/lib/apt/lists/*
 #borra cache que queda de la instalacion y update 
#RUN rm /etc/nginx/sites-enabled/default

#ADD ficheros/curso_img_debian.conf /etc/nginx/conf.d/curso_img_debian.conf
#ADD ficheros/index.html /var/www/curso_img_debian/index.html

#EXPOSE informa a docker que puerto se estará utilizando
EXPOSE 80

#CMD comando que se ejecuta al iniciar/arrancar el contenedor
CMD ["nginx","-g", "daemon off;"]
#deamon off; pone al pricipio el proceso de nginx y no lo manda al fondo
