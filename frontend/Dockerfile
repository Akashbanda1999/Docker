FROM centos:07
LABEL Devops ="Anup_Dudhe"
RUN yum install httpd -y
COPY index.html /var/www/html/
RUN chmod 777 -r /var/www/
RUN chmod 644 /var/www/html/index.html
EXPOSE 80
CMD httpd -DFOREGROUND


