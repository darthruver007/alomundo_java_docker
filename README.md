# Alô Mundo Docker

Projeto desenvolvido em Java com o objetivo de apresentar uma aplicação simples executada em um ambiente Docker.

O programa exibe a mensagem "Alo Mundo Docker" no console.

Sobre o projeto

Este projeto faz parte dos estudos iniciais de Ciência da Computação, utilizando conceitos básicos da linguagem Java e introduzindo o uso de Docker para execução da aplicação.

O projeto também utiliza Maven para gerenciamento e configuração da aplicação.

Tecnologias utilizadas
Java
Docker
Maven
NetBeans
Git
GitHub
Estrutura do projeto
Alô-Mundo-Docker/
│
├── src/
│   └── main/
│       └── java/
│           └── Principal.java
│
├── Dockerfile
├── pom.xml
├── nbactions.xml
├── .gitignore
├── LICENSE
└── README.md

Código

A aplicação possui uma classe principal chamada Principal:

public class Principal {

    public static void main(String[] args) {
        System.out.println("Alo Mundo Docker");
    }
}

O comando System.out.println() é utilizado para exibir uma mensagem no console.

Como executar
Executando com Java

Para executar o projeto utilizando Java, compile e execute a classe principal:

javac Principal.java
java Principal
Resultado esperado
Alo Mundo Docker
Executando com Docker

Para executar a aplicação utilizando Docker, primeiro é necessário criar a imagem do projeto.

Criar a imagem

Na pasta principal do projeto, execute:

docker build -t alo-mundo-docker .
Executar o container

Depois de criar a imagem:

docker run --rm alo-mundo-docker
Resultado esperado
Alo Mundo Docker
Docker Hub

A imagem do projeto também está disponível publicamente no Docker Hub.

Projeto no Docker Hub:
https://hub.docker.com/r/darthruver007/alomundo_java_docker

Requisitos

Para executar o projeto, é necessário ter instalado:

JDK
Maven
Docker
Git
Licença

Este projeto está disponível sob a licença definida no arquivo LICENSE deste repositório.

Autor

Douglas de Almeida Ruver

Projeto desenvolvido para fins acadêmicos e de aprendizado em Ciência da Computação.

Desenvolvido utilizado JDK 1.8 e NetBeans 13. 