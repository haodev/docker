FROM php:5.6-apache
RUN apt-get update && apt-get install -y \
		php5-curl \
		php5-gd \
		php5-intl \
		php5-json \
		php5-mongo \
		php5-redis

FROM mongo:latest

FROM redis

FROM docker-varnish