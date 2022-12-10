FROM openjdk:8-jdk-alpine
ENV SA_LOGIC_API_URL http://localhost:5050
ADD /var/lib/jenkins/workspace/spring-petclinic/target/spring-petclinic-2.7.0-SNAPSHOT.jar /
EXPOSE 8080
CMD ["java","-jar","spring-petclinic-2.7.0-SNAPSHOT.jar","--sa.logic.api.url=${"SA_LOGIC_API_URL"}]

