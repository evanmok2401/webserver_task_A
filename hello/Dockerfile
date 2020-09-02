FROM nginx:1.19.2-alpine
COPY /html /usr/share/nginx/html
COPY ./default.conf /etc/nginx/conf.d/default.conf
EXPOSE 9988
CMD ["nginx", "-g", "daemon off;"]