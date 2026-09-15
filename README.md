Alo Mundo Docker

Projeto desenvolvido em Java com o objetivo de exibir a mensagem "Alo Mundo Docker" no console e demonstrar a execução de uma aplicação Java utilizando Docker.

Sobre o projeto

O projeto possui uma classe principal chamada Principal, responsável por iniciar a aplicação e exibir a mensagem:

Alo Mundo Docker

O projeto também utiliza Maven para gerenciamento e construção da aplicação e Docker para criação e execução do ambiente da aplicação.

🛠️ Tecnologias utilizadas
Java
Maven
Docker
NetBeans
Estrutura do projeto
AloMundoDocker/
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
▶️ Execução do projeto
Executando com Java

Compile e execute a classe Principal:

javac Principal.java
java Principal

A saída esperada será:

Alo Mundo Docker
Executando com Maven

Para compilar o projeto utilizando Maven:

mvn clean package

Depois, execute a aplicação conforme a configuração definida no projeto.

Executando com Docker

Para criar a imagem Docker:

docker build -t alo-mundo-docker .

Depois, execute o container:

docker run --rm alo-mundo-docker

A saída esperada será:

Alo Mundo Docker

Objetivo

O objetivo deste projeto é praticar os conceitos básicos de:

Desenvolvimento de uma aplicação Java;
Organização de um projeto Maven;
Criação de uma imagem Docker;
Execução de uma aplicação Java em um container;
Versionamento do projeto utilizando Git e GitHub.

Docker Hub
https://hub.docker.com/r/darthruver007/alomundo_java_docker