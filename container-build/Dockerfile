# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent
# Change the port to 8080
EXPOSE 8080
# Change web server port to 8080
RUN sed -i "s/Listen 80/Listen 8080/g" /etc/httpd/conf/httpd.conf
