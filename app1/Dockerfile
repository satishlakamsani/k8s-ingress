FROM nginx

# Remove default content
RUN rm -rf /usr/share/nginx/html/*

# Create new index file
RUN echo "<h1>Hi, I am from APP-1</h1>" > /usr/share/nginx/html/index.html

# Fix permissions
RUN chmod -R 755 /usr/share/nginx/html