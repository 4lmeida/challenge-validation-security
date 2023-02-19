<h1 align="center"> :white_check_mark:Validation Security:closed_lock_with_key: </h1>
<p align="center">
  <img src="https://img.shields.io/static/v1?label=spring&message=framework&color=blue&style=for-the-badge&logo=SPRING"/>
  <img src="https://img.shields.io/static/v1?label=Postman&message=API management&color=blue&style=for-the-badge&logo=postman"/>
  <img src="https://img.shields.io/static/v1?label=Apache&message=Dependency manager&color=blue&style=for-the-badge&logo=apache"/>
  <img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
</p>  

### Tópicos 

:small_blue_diamond: [Sobre o projeto](#Sobre-o-projeto-open_file_folder)

:small_blue_diamond: [Funcionalidades](#Funcionalidades)

:small_blue_diamond: [Modelo Conceitual](#Modelo-conceitual-page_with_curl)

:small_blue_diamond: [Layout](#Layout-mag_right)

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

# Sobre o projeto :open_file_folder:

O Validation security é uma extensão do projeto TDD de CRUD, porém com enfoque na implementação da segurança e validação, e também é uma avaliação geral 
de tudo que foi aprendido até o momento na escola [DevSuperior](https://devsuperior.com.br/cursos), sendo assim é um dos desafios para avançar no curso.

<p>
O projeto é um sistema de eventos e cidades com uma relação N-1, que também tem um domínio de usuários e seus papeis para autenticar e autorizar permissões de acesso aos 
recursos da aplicação. 
O foco principal da aplicação é autenticar e autorizar alguns recursos conforme o papel do usuário e também validar as informações passadas pelo mesmo usuário caso elas sejam invalidas.
</p>

## Funcionalidades

:heavy_check_mark: Testa componentes da aplicação.

:heavy_check_mark: Busca lista de recursos ordenado por nome.

:heavy_check_mark: Inserir novo recurso.

:heavy_check_mark: Autorização e autenticação. 

:heavy_check_mark: Validação. 

# Layout:mag_right:

- Endpoints:

![]()

- Testes:

![]()

# Modelo conceitual :page_with_curl:
![Modelo Conceitual]()

## Linguagens, dependencias e libs utilizadas :books:
- [JAVA](https://www.java.com/pt-BR/)
- [JPA](https://spring.io/projects/spring-data-jpa) / [Hibernate](https://hibernate.org/)
- [Maven](https://maven.apache.org/)
- [H2](https://www.h2database.com/html/main.html)
- [JUnit](https://junit.org/junit5/)
- [Mockito](https://site.mockito.org/)
- [Jakarta Bean validation](https://beanvalidation.org)
- [JWT](https://jwt.io)
- [OAuth 2.0](https://oauth.net/2/)
- [Spring Security](https://docs.spring.io/spring-security/reference/index.html)
- [Spring Cloud](https://docs.spring.io/spring-cloud/docs/current/reference/html)

# Como rodar a aplicação :arrow_forward:

Pré-requisitos: Java 17

```bash
# clonar repositório
https://github.com/4lmeida/challenge-validation-security.git

# entrar na pasta do projeto challenge-validation-security
cd challenge-validation-security

# executar o projeto
./mvnw spring-boot:run
```
# Autor

| [<img src="https://avatars.githubusercontent.com/u/93017964?v=4" width=115><br><sub>Luís Almeida</sub>](https://github.com/4lmeida) |
| :---: |

## Licença 

The [MIT License](https://github.com/4lmeida/challenge-validation-security/blob/main/License)(MIT)

Copyright :copyright: 2023 - Validation Security
