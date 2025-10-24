FROM maven:3.9.9-eclipse-temurin-21-jammy AS Build_Image
RUN git clone https://github.com/faresalig/vprof-Project.git
RUN cd vprof-Project && MAVEN_OPTS="-Xmx1024m" mvn install



FROM tomcat:9-jdk11
RUN rm -rf /usr/local/tomcat/webapps/*
COPY --from=build_image vprof-Project/target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]


# to login to the image
#docker run --rm -it maven:3.9.9-eclipse-temurin-21-jammy bash

# to show all files in target

# git clone https://github.com/faresalig/vprof-Project.git
# cd vprof-Project
# mvn install
# ls -lh target/
