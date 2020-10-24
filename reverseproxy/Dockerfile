FROM nginx

# Deletes existing default.conf from nginx image
RUN rm /etc/nginx/conf.d/default.conf

# Copy the default.conf that we have created into nginx image
COPY default.conf /etc/nginx/conf.d
