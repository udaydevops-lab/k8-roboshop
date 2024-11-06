# Use a lightweight version of the NGINX image
FROM nginx:alpine

RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf

# Copy configuration and static files
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/