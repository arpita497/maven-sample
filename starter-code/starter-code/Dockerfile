FROM tomcat:8
RUN sed -i 's/port="8080"/port="9090"/' /usr/local/tomcat/conf/server.xml
COPY /var/lib/jenkins/workspace/docker-container@2/starter-code/starter-code/target /opt/tomcat/webapps
EXPOSE 9090
CMD ["catalina.sh", "run"]
