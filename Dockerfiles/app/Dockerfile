FROM tomcat:8-jre11
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/*.war /usr/local/tomcat/webapps/ROOT.war
VOLUME /usr/local/tomcat/webapps
WORKDIR /usr/local/tomcat/
EXPOSE 8080