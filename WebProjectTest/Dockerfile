FROM tomcat:8.0-alpine
LABEL maintainer=”saurabh1988gupta@gmail.com”
ADD ../Maven-Build/WebProjectTest/target/web-project-dev-ops.war /usr/local/tomcat/webapps/
EXPOSE 8084
CMD [“catalina.sh”, “run”]