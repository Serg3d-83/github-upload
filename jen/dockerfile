FROM nginx

RUN apt update -y && apt upgrade -y

COPY index.html /usr/share/nginx/html/
EXPOSE 9000:80