# Use an official lightweight web server image
FROM nginx:alpine

# Copy all project files and directories to the Nginx html directory
COPY . /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]