FROM tomcat:7-jre8
MAINTAINER "Steve Blackmon <sblackmon@apache.org>"

ADD ./ROOT.war $CATALINA_HOME/webapps/

EXPOSE 8080

CMD ["catalina.sh", "run"]
