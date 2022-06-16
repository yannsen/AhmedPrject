FROM maven
RUN mkdir -p /usr/local/myjava
WORKDIR /usr/local/myjava
COPY target/*.jar bin.jar
CMD [ "java", "-jar", "bin.jar" ]