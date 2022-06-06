[![header][header-url]][header-link]

# Spring Boot Forum API Monitoramento
[![Project Version][version-image]][version-url]
[![Backend][Backend-image]][Backend-url]

> Projeto de estudo para monitoramento de API REST.

Aplicação desenvolvida para realizar o monitoriação de uma ou mais APIs.

---
## Autor

**Roger de Azevedo** 

* *Meu perfil profissional no* [LinkedIn][linkedin-url]

## Apresentação

Esse projeto foi desenvolvido para demonstrar:

* Arquitetura API REST / Micro-serviço
* Monitoramento com Spring Boot Actuator
  * Monitoramento com Spring Boot Admin (codecentric)
    * [springboot-forum-api](https://github.com/rogerfdeazevedo/springboot-forum-api) - Projeto de API Rest monitorado por esse projeto;


## Tecnologias

* [Maven](https://maven.org/) - Dependency Management
* [Spring Boot Framework](https://https://start.spring.io/) - Framework API Rest
* [Spring Boot Admin - Codecentric](https://github.com/codecentric/spring-boot-admin) - Framework de Monitoramento deAPI Rest

## Tópico Forum Api

API responsável pelos Tópicos de discussão, em um fórum de cursos de uma escola.

## Release History

* **1.0.0**
  * **Monitoramento com Spring Boot Admin**
    * **Dependências**:
      * Ultilizar o módulo Spring Boot Starter Web;
      * Ultilizar o módulo Spring Boot Admin Starter Server;
        * * Para acessar a interface gráfica do Spring Boot Admin, localmente, utilizar o endereço : http://localhost:8081
    * **MainApplication**:
      * Na clase principal substituir anotação do @SpringBootApplication, pelas anotações @Configuration, @EnableAutoConfiguration e @EnableAdminServer;
    * **Configurações**:
      * Para execução dos projetos em "localhost", alterar a porta da aplicação no arquivo de propriedades "server.port=8081"; 
  

<!-- Markdown link & img dfn's -->

[header-url]: github-template.png
[header-link]: https://github.com/alexandrerosseto

[repository-url]: https://github.com/alexandrerosseto/wbshopping

[cloud-provider-url]: https://wbshopping.herokuapp.com

[linkedin-url]: https://www.linkedin.com/in/alexandrerosseto

[wiki]: https://github.com/yourname/yourproject/wiki

[version-image]: https://img.shields.io/badge/Version-1.0.0-brightgreen?style=for-the-badge&logo=appveyor
[version-url]: https://img.shields.io/badge/version-1.0.0-green
[Backend-image]: https://img.shields.io/badge/Backend-Java%2011-important?style=for-the-badge
[Backend-url]: https://img.shields.io/badge/Backend-Java%2011-important?style=for-the-badge