FROM adoptopenjdk/openjdk11:alpine-jre
ADD target/devops-docker.jar devops-docker.jar
ENTRYPOINT ["java","-jar","/devops-docker.jar"]