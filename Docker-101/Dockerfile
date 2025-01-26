# Use the official Nginx base image
FROM nginx:alpine

# Copy the web app into the default Nginx HTML directory
COPY ./src/index.html /usr/share/nginx/html/index.html

# Expose port 80 internally
EXPOSE 80

# Run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]