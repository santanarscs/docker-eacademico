FROM jboss/wildfly

COPY standalone.xml /opt/jboss/wildfly/standalone/configuration/standalone.xml
ADD oracle /opt/jboss/wildfly/modules/system/layers/base/com/oracle
RUN /opt/jboss/wildfly/bin/add-user.sh admin 12345678 --silent
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0", "--debug", "8787"]

MAINTAINER raphaelstn@gmail.com
