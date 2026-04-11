FROM almalinux:9

RUN dnf install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html

# The ONBUILD instruction adds a trigger instruction to the image that will be executed when the image is used as the base for another build. In this case, it will copy the index.html file to the nginx html directory when a new image is built from this one.   

ONBUILD COPY index.html /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]

