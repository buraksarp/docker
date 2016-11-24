FROM java:8 

# Install maven
RUN apt-get update  
RUN apt-get install -y maven

# Adding spring-boot app
ADD . /usr/
WORKDIR /usr/springboot-app
RUN ["mvn", "package"]

EXPOSE 8080
CMD ["/usr/lib/jvm/java-8-openjdk-amd64/bin/java", "-jar", "target/springboot-app-0.0.1-SNAPSHOT.jar"]
