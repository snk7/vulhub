FROM tomcat:8

MAINTAINER phithon <root@leavesongs.com>

RUN set -ex \
    && rm -rf /usr/local/tomcat/webapps/* \
    && chmod a+x /usr/local/tomcat/bin/*.sh

COPY S2-013.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080