FROM centos 
MAINTAINER sam 
RUN yum -y install httpd 
RUN echo "Hello Sam" > /var/www/html/index.html
EXPOSE 80 
CMD ["-D","FOREGROUND"]
ENTRYPOINT ["/usr/sbin/httpd"]
