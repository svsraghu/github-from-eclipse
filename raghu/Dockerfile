FROM adoptopenjdk/openjdk11:alpine-jre
COPY /target/docker-k8s.jar /var/lib/jenkins/workspace/dockerImage@2/raghu/target/docker-k8s.jar
ENTRYPOINT ["java","-jar","/var/lib/jenkins/workspace/dockerImage@2/raghu/target/docker-k8s.jar"]
