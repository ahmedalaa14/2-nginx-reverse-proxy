FROM nginx
# delete the existing defulat.conf
RUN /etc/ngnix/conf.d/defulat.conf

# copy the custom default.conf to the nginx configuration
COPY defualt.conf /etc/nginx/conf.d
COPY ./index.html /usr/share/nginx/html/index.html
