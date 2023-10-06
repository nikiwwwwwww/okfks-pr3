FROM openjdk:latest

WORKDIR /app

COPY calc.java .

RUN javac calc.java

CMD ["java", "calc.java"]