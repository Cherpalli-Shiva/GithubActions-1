# Use Nginx as the base image
FROM nginx:alpine

# remove the default Nginx index page
RUN rm -rf /usr/share/nginx/html/*

# Copy the static website files to the Nginx html directory
COPY . /usr/share/nginx/html

# Expose port 82
EXPOSE 82

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]

# Note: The above Dockerfile is a simple example of how to serve static files using Nginx in a Docker container.