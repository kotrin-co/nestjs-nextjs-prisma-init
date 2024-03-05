FROM nginx:1.24

RUN rm -f /etc/nginx/conf.d/*

ADD local.conf /etc/nginx/conf.d/local.conf

CMD /usr/sbin/nginx -g 'daemon off;' -c /etc/nginx/nginx.conf