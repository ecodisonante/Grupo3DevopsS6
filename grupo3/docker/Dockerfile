# Usar la ultima version de la imagen oficial de Nginx
FROM nginx:latest

# Copia el archivo de configuración de Nginx al contenedor
COPY default.conf /etc/nginx/conf.d/default.conf

# Copia el contenido de la aplicación al directorio donde Nginx los servirá
COPY ./html /usr/share/nginx/html

# Exponer el puerto en el que Nginx está escuchando
EXPOSE 80