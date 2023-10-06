FROM openjdk:latest

WORKDIR /app

COPY game.java .

# Компилируем Java-код
RUN javac game.java

CMD ["java", "game"]