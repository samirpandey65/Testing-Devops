#OS with Env (base image)
FROM openjdk:17-jdk-alpine



#Working dir
WORkDIR /app


#Code
COPY src/Main.java /app/Main.java


#Libraroes
RUN javac Main.java


#run
CMD ["java", "Main"]


