Alo Mundo Java com Docker

Aplicação Alo Mundo desenvolvida em Java e executada em um container Docker.

Sobre o projeto
O projeto foi desenvolvido utilizando o NetBeans.
Utiliza Java para desenvolvimento da aplicação.
Utiliza o Apache Maven para automatizar o processo de construção da aplicação.
A aplicação é empacotada no formato JAR (Java ARchive).
Utiliza o Docker para criar uma imagem e executar a aplicação em um container.
A aplicação possui como objetivo exibir a mensagem "Alo Mundo Docker" no console.
Comandos Docker
Utilizar o terminal do Windows PowerShell em modo administrador.
Construir a aplicação
docker build -t alo_mundo_java_docker .
Rodar a aplicação
docker run --rm alo_mundo_java_docker
Execução

A saída da aplicação é apresentada no próprio terminal:

Alo Mundo Docker
Remover imagem
docker rmi alo_mundo_java_docker
Arquitetura do Sistema

A aplicação é composta por uma classe principal responsável pela execução do programa.

Aplicação Java
      │
      ▼
   Maven
      │
      ▼
 Arquivo JAR
      │
      ▼
   Docker
      │
      ▼
   Container
      │
      ▼
Console
      │
      ▼
Alo Mundo Docker
Estrutura do projeto
alo_mundo_java_docker/
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
Docker Hub
https://hub.docker.com/r/darthruver007/alomundo_java_docker