FROM nginx:1.15.8
RUN rm -f /etc/nginx/conf.d/*
ADD conf/nginx.conf /etc/nginx/conf.d/app.conf
CMD /usr/sbin/nginx -g 'daemon off;' -c /etc/nginx/nginx.conf
