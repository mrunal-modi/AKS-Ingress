# Use an official nginx image as the base image
FROM --platform=linux/amd64 nginx:latest 

# Copy the custom HTML file to the nginx default HTML directory
COPY ./index.html /usr/share/nginx/html/

# Expose port 80 for the web server
EXPOSE 80

# Command to start the nginx web server
CMD ["nginx", "-g", "daemon off;"]
