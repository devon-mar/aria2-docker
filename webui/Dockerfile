FROM alpine:latest
RUN apk add darkhttpd

COPY ./webui-aria2/docs/ /var/www/html/

ENTRYPOINT ["darkhttpd", "/var/www/html", "--port", "8000"]