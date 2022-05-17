FROM quay.io/jkube/jkube-java-binary-s2i:0.0.9
ENV JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="CICD With kubernetes" org.label-schema.version=0.0.2-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-05-17T14:45:50.260 org.label-schema.name=sprint-boot-devopsboot-devops org.label-schema.vcs-ref=d8e7a6b7a84bb973c176570a82aad8a14573e546 org.label-schema.vcs-url=https://github.com/adityadand/spring-boot-devops.git
EXPOSE 8090 8778 9779
COPY /deployments /deployments/
