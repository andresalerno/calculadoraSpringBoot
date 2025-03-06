```java
mvn clean package
```

```java
mvn spring-boot:run
```

```browser
http://localhost:8080/soma/1/2
```

## Taget Folder

Uma vez que você digitou o comando `mvn clean package` ele gerou um folder de nome target. Para rodar nesse formato, você deve digitar:

```java
java -jar .\target\calculadorarestspring-0.0.1-SNAPSHOT.jar
```

```browser
http://localhost:8080/soma/10/2
```

## Rodando pelo debugger

Vá até o arquivo CalculadorarestspringApplication.java e clique no F5 ou no símbolo de play para rodar o projeto.