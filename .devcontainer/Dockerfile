FROM openjdk:8-jdk-alpine
ENV SA_LOGIC_API_URL http://localhost:5050
ADD target/spring-petclinic-2.7.0.jar /
EXPOSE 8080
CMD ["java","-jar","spring-petclinic-2.7.0.jar","--sa.logic.api.url=${"SA_LOGIC_API_URL"]

