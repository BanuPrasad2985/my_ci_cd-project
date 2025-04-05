# Use Nginx (a web server) as the base image
FROM nginx:alpine

# Copy your project files into the Nginx public directory
COPY . /usr/share/nginx/html

# Expose port 80 (Nginx default)
EXPOSE 80
