FROM adoptopenjdk/openjdk11:alpine-jre
ADD /target/docker-k8s.jar docker-k8s.jar
ENTRYPOINT ["java","-jar","/docker-k8s.jar"]
