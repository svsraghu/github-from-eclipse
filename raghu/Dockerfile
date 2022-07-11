FROM adoptopenjdk/openjdk11:alpine-jre
ADD /target/docker-k8s.jar /var/lib/jenkins/workspace/dockerImage/raghu/target/docker-k8s.jar
ENTRYPOINT ["java","-jar","/var/lib/jenkins/workspace/dockerImage/raghu/target/docker-k8s.jar"]
