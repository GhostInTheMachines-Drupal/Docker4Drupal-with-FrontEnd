ARG PHP_TAG

FROM wodby/drupal-php:${PHP_TAG}

USER root

# Install packages
RUN apk add --no-cache --update gcc g++ nodejs python
RUN apk add --update npm

# Install node packages
RUN npm install --global gulp gulp-cli grunt webpack