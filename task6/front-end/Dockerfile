# From NGINX Copy front end file to the Docker Image
# Copy configuration file to the config file
FROM nginx:latest
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
