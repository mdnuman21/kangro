# Use lightweight Nginx base image
FROM nginx:alpine

# Remove default Nginx config (optional, if you're customizing)
RUN rm /etc/nginx/conf.d/default.conf

# Copy your static site files into Nginx's web directory
COPY . /usr/share/nginx/html

# Expose port 80 for web traffic
EXPOSE 80