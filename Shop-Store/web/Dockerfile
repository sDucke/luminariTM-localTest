FROM nginx:alpine

# Limpiamos config por defecto
RUN rm -rf /usr/share/nginx/html/*

# Copiamos el sitio
COPY site/ /usr/share/nginx/html/

EXPOSE 80

