FROM tomcat:9-jre8

# Set the working directory
WORKDIR /usr/local/tomcat

# Copy the WAR file into the Tomcat webapps directory
COPY docker-java-sample-webapp-1.0-SNAPSHOT.war webapps/ROOT.war

# Expose the port your servlet will run on (adjust if needed)
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
