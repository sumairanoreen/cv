# Use an official Nginx image as the base image
FROM nginx:latest

# Copy your custom index.html file to the NGINX default HTML directory
COPY ./index.html /usr/share/nginx/html/index.html

# Expose the default Nginx port (usually 80)
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
