FROM nginx:latest
RUN mkdir /app
COPY dist /app/
COPY docker/nginx.conf /etc/nginx/conf.d/default.conf
CMD ["nginx", "-g", "daemon off;"]