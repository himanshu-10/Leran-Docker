#fetch base image
FROM openjdk:17-jdk-alpine

#metadata

LABEL maintainer="himanshusrivastava5390@gmail.com"
LABEL version="1.0"
LABEL description="java hellp application"

#working directory

WORKDIR /app

#copy files to container
COPY src/Main.java .

#RUN Compiler
RUN javac Main.java

#run app when container start
CMD ["java","Main"]









