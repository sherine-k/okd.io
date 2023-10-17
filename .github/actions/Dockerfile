FROM squidfunk/mkdocs-material:9.4.6

RUN apk add --no-cache --update nodejs npm

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
