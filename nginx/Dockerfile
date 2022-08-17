FROM nginx:1.15.0

# removing default image configuration
RUN rm /etc/nginx/conf.d/default.conf

# setting my custom configuration
COPY nginx.conf /etc/nginx/conf.d