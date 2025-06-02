# static-website/Dockerfile
FROM nginx:alpine

# Remove default Nginx content
RUN rm -rf /usr/share/nginx/html/*

# Copy static files 
COPY . /usr/share/nginx/html

# Nginx runs on port 80 by default
EXPOSE 80