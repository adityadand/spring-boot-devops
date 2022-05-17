FROM quay.io/jkube/jkube-java-binary-s2i:0.0.9
ENV JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="CICD With kubernetes" org.label-schema.version=0.0.3-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-05-17T15:21:51.009 org.label-schema.name=sprint-boot-devopsboot-devops org.label-schema.vcs-ref=3f471c27047b5b5ec6d20086693a65b3eb61e37b org.label-schema.vcs-url=https://github.com/adityadand/spring-boot-devops.git
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
