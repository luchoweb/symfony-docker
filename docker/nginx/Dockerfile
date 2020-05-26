# docker/nginx/Dockerfile

FROM nginx:alpine

RUN apk add --update --no-cache nginx

COPY nginx.conf /etc/nginx/
COPY sites/symfony.conf /etc/nginx/conf.d/
COPY conf.d/upstream.conf /etc/nginx/conf.d/

RUN adduser -D -g '' -G www-data www-data

CMD ["nginx"]

EXPOSE 80
EXPOSE 443
