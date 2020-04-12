FROM nginx:alpine

RUN rm /etc/nginx/conf.d/*

COPY ./cert.pem ./key.pem /etc/nginx/certificates/
COPY ./nginx.conf /etc/nginx/conf.d/
