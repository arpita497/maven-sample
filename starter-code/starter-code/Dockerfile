FROM tomcat:8
RUN sed -i 's/port="8080"/port="9090"/' /opt/tomcat/conf/server.xml
ADD /var/lib/jenkins/workspace/ecr_pipeline/starter-code/starter-code/target/demo-4.0.0-SNAPSHOT.war /opt/tomcat/webapps
EXPOSE 9090
CMD ["catalina.sh", "run"]
