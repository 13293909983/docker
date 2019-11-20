# base image
FROM jre:1.0.0

#Ali-Tomcat 环境
ADD taobao-tomcat-7.0.59.tgz /opt
ADD taobao-hsf.tgz /opt/taobao-tomcat-7.0.59/deploy

WORKDIR /opt/taobao-tomcat-7.0.59
CMD ["/opt/taobao-tomcat-7.0.59/bin/catalina.sh","run"]