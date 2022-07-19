FROM tomcat:8.0
ADD copy -a java-tomcat-sample-docker/target/*.war /usr/local/tomcat/webapps/

EXPOSE 8080
CMD ["catalina.sh", "run"]
