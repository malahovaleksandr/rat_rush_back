FROM centos:7

COPY asset/nginx.repo /etc/yum.repos.d/nginx.repo
RUN yum -y update && yum install -y nginx
COPY asset/default.conf /etc/nginx/conf.d/default.conf
