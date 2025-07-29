FROM nginx:1.27.2-alpine
COPY ./server.conf /etc/nginx/conf.d/default.conf

EXPOSE 80
CMD ["nginx","-g","daemon off;"]