FROM tomcat:8-jre8

RUN rm -rf /usr/local/tomcat/webapps/*

COPY target/gameoflife.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8082
CMD ["catalina.sh", "run"]
