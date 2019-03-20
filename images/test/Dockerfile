#ksavithri/b35-httpd:v1
FROM centos
RUN yum install httpd -y
RUN echo "<h1>Hello<h1>" >/var/www/html/index.html
CMD httpd -DFOREGROUND 
