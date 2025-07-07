FROM nginx:alpine

# Remove default NGINX web files
RUN rm -rf /usr/share/nginx/html/*

# Copy your static HTML files
COPY ./app/frontend/ /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
