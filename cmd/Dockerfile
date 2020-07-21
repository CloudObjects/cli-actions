FROM cloudobjects/php-app-base:latest

COPY entrypoint.sh /entrypoint.sh

RUN curl -O -L https://github.com/CloudObjects/CloudObjects-CLI/releases/download/0.4/CloudObjects-CLI.phar

ENTRYPOINT ["/entrypoint.sh"]