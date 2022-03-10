FROM nginx:latest
RUN mkdir /app
COPY --from=builder /angular-starter/dist/angular-starter /app/
COPY --from=builder /angular-starter/docker/nginx.conf /etc/nginx/conf.d/default.conf
CMD ["nginx", "-g", "daemon off;"]