FROM tomcat:8
RUN sed -i 's/port="8080"/port="9090"/' /usr/local/tomcat/conf/server.xml
COPY /var/lib/jenkins/workspace/demo-4.0.0-SNAPSHOT.war /opt/apache-tomcat-10.0.27/webapps
EXPOSE 9090
CMD ["catalina.sh", "run"]
