FROM tomcat:8-jre11
RUN rm -rf /usr/local/tomcat/webapp/*
COPY target/*.war /usr/local/tomcat/webapp/ROOT.war
VOLUME /usr/local/tomcat/webapp
WORKDIR /usr/local/tomcat/
EXPOSE 8080