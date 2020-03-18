FROM centos:7
COPY ./nginx.repo /etc/yum.repos.d/nginx.repo
RUN yum install -y nginx
COPY ./nginx.conf /etc/nginx/nginx.conf
CMD ["nginx", "-g", "daemon off;"]