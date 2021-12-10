FROM ubuntu

RUN apt -qq update && apt -qq -y install maven
RUN apt -qq update && apt -qq -y install default-jdk

COPY untitled2 /usr/app 
 
WORKDIR /usr/app
ENTRYPOINT ["mvn","exec:java"]

