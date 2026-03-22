FROM nginx
WORKDIR /app
COPY ./.github/workflows/index.html /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
