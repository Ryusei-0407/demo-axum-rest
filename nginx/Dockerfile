FROM nginx:mainline-alpine

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 26257
EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]
