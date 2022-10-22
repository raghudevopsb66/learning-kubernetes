FROM      centos:7
RUN       yum install epel-release -y
RUN       yum install nginx -y
#ENTRYPOINT ["ping", "-c3"]
#CMD       ["yahoo.com"]

ENTRYPOINT ["nginx", "-g", "daemon off;"]