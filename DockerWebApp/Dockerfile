# Use the official Tomcat 11 with JDK 21 image
FROM tomcat:11.0-jdk21

# Copy your WAR file into the Tomcat webapps directory
COPY target/DockerWebApp.war /usr/local/tomcat/webapps/DockerWebApp.war

# Expose port 8080
EXPOSE 8080
