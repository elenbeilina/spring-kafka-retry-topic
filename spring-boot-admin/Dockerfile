FROM openjdk:17-jdk-alpine
COPY /spring-boot-admin/target/spring-boot-admin-*.jar spring-boot-admin-*.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-boot-admin-*.jar"]