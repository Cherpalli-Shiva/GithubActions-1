# Use Nginx image to serve static files
FROM nginx:alpine

# Remove default nginx index page
RUN rm  -rf /usr/share/nginx/html/*

# Copy your static website files to the nginx html directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 81

# Start nginx server
CMD ["nginx", "-g", "daemon off;"]

# Note: The above Dockerfile is a simple expose to 81
