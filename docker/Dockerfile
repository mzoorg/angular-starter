FROM nginx:latest
RUN mkdir /app
COPY dist/angular-starter /app/
COPY nginx.conf /etc/nginx/conf.d/default.conf
CMD ["nginx", "-g", "daemon off;"]