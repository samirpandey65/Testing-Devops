##OS
FROM openjdk:17-jdk-alpine
##DIR
WORKDIR /app

##COPY
COPY src/Main.java /app/Main.java

##LIB
RUN javac Main.java

###RUN
CMD ["java", "Main"]
