#Start with a base image containing Java runtime
FROM eclipse-temurin:17-jdk-jammy

LABEL authors="anandchitte"

#Information around who maintains the image
MAINTAINER anandchitte

# Add the application's jar to the image
COPY target/accounts-1.0-SNAPSHOT.jar accounts-1.0-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]