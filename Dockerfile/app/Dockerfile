FROM tomcat:8-jre11
LABEL maintainer='Zulqarnain <muhammad.zulqarnain1001@gmail.com>'
LABEL project='VProfileProject'

RUN rm -rf /usr/local/tomcat/webapp/*

COPY ./vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/

VOLUME /usr/local/tomcat/webapps

