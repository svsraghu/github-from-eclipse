FROM adoptopenjdk/openjdk11:alpine-jre
ADD target/docker-k8s.jar /var/lib/jenkins/workspace/dockerImage@2/raghu/target/docker-k8s.jar
ENTRYPOINT ["java","-jar","/docker-k8s.jar"]
