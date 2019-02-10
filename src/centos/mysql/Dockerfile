FROM centos:centos7
MAINTAINER JOBJAVA00 <jobjava00@gmail.com>

RUN yum -y install wget
RUN wget https://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm
RUN rpm -ivh mysql57-community-release-el7-11.noarch.rpm
RUN yum -y install mysql-server