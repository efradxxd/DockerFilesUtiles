FROM nginx

COPY index.html /usr/share/nginx/html
COPY app.js /usr/share/nginx/html

#EXPOSE informa a docker que puerto se estará utilizando
EXPOSE 80

#CMD comando que se ejecuta al iniciar/arrancar el contenedor
CMD ["nginx","-g", "daemon off;"]
#deamon off; pone al pricipio el proceso de nginx y no lo manda al fondo