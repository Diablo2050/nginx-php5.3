FROM centos:latest
RUN yum update -y
COPY nginx.repo /etc/yum.repos.d/nginx.repo
RUN yum install nginx -y
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
CMD ["nginx"]
EXPOSE 80
