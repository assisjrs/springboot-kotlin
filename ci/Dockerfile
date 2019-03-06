FROM openjdk:8

ADD target/*.jar /opt/app.jar

ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom -Xms 1024 -Xmx 1024 -server", "-jar", "/opt/app.jar"]
