# Use Nginx image to serve static fileeee
FROM nginx:alpine

# Remove default nginx index pages
RUN rm  -rf /usr/share/nginx/html/*

# Copy your static website files to the nginx html directories
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start nginx server
CMD ["nginx", "-g", "daemon off;"]
