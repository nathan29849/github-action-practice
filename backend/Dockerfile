FROM openjdk:11-jdk
COPY ./backend/build/libs/*.jar sidedish.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/sidedish.jar"]

