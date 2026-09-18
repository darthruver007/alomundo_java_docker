# Alomundo Java com Docker

Aplicação Alomundo desenvolvida em Java e executada em um container Docker.

---

## Sobre o Projeto

- O projeto foi desenvolvido utilizando o NetBeans.
- O nome do projeto é alomundo_java_docker.
- Utiliza o Java 8.
- Utiliza o Apache Maven para automatizar o processo de construção da aplicação.
- A aplicação é empacotada no formato JAR (Java ARchive).
- Utiliza o Docker para criar uma imagem e executar a aplicação em um container.

---

## Tecnologias Utilizadas

- Java 8
- Apache Maven
- Docker
- NetBeans IDE

---

## Estrutura do Projeto

```text
alomundo_java_docker/
├── src/
│   └── main/
│       └── java/
│           └── Principal.java
├── Dockerfile
├── pom.xml
├── nbactions.xml
├── .gitignore
├── LICENSE
└── README.md

---

## Docker Hub

A imagem oficial deste projeto está publicada e disponível no Docker Hub:

- https://hub.docker.com/r/darthruver007/alomundo_java_docker

---

## Comandos Docker

Utilizar o terminal do Windows PowerShell em modo administrador.

### Construir a aplicação

docker build -t alomundo_java_docker .

### Rodar a aplicação

docker run --rm alomundo_java_docker

### Execução

A saída da aplicação é exibida no próprio terminal.

### Remover imagem

docker rmi alomundo_java_docker

---

## Execução sem Docker

### Executando com Java

javac src/main/java/Principal.java
java -cp src/main/java Principal

### Executando com Maven

mvn clean package
java -jar target/alomundo_java_docker-1.0.jar

---

## Objetivo

O objetivo deste projeto é praticar os conceitos básicos de:

- Desenvolvimento de uma aplicação em Java 8;
- Organização de um projeto Maven;
- Empacotamento de aplicação em arquivo JAR;
- Criação de uma imagem e execução de um container Docker;
- Publicação da imagem no Docker Hub e versionamento do projeto utilizando Git e GitHub.