FROM tomcat:8.0
RUN copy -a **/*.war /usr/local/tomcat/webapps/

EXPOSE 8080
CMD ["catalina.sh", "run"]
