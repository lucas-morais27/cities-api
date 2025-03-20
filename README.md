# Controle de Estacionamento de Veículos API
Este projeto tem como objetivo o desenvolvimento de um conjunto de APIs utilizando Spring Boot para controlar um estacionamento de veículos. A aplicação gerencia a entrada, saída e o valor a ser cobrado de cada cliente. Utiliza Spring Security para a segurança, PostgreSQL para persistência de dados e implementa boas práticas de desenvolvimento de APIs, incluindo a criação de testes automatizados e cobertura de testes.

## Funcionalidades
- Cadastro de veículos: O sistema controla o registro de veículos que entram no estacionamento.
- Entrada e saída de veículos: Realiza o controle da entrada e saída dos veículos no estacionamento.
- Cálculo de cobrança: Calcula o valor a ser cobrado pelo tempo que o veículo ficou estacionado.
- Segurança: A aplicação utiliza Spring Security para proteger os endpoints sensíveis.
- Persistência: Utiliza PostgreSQL para armazenar os dados dos veículos, entradas, saídas e cobranças.
- Testes: Testes automatizados foram implementados, com relatórios de cobertura para garantir a qualidade do código.

## Tecnologias Utilizadas
- Spring Boot: Framework para desenvolvimento de aplicações Java.
- Spring Security: Para controle de segurança e autenticação.
- Spring Data JPA: Para integração com banco de dados PostgreSQL.
- PostgreSQL: Banco de dados utilizado para persistir os dados.
- JUnit: Framework para testes automatizados.
- Heroku: Para fazer o deploy da API na cloud.
- Lombok: Para evitar código repetitivo, como getters e setters.

## Estrutura do Projeto
A aplicação segue a arquitetura padrão de um projeto Spring Boot com as seguintes camadas:

- Controller: Responsável por gerenciar as requisições HTTP.
- Service: Contém a lógica de negócios, como o cálculo do tempo de permanência e o valor a ser cobrado.
- Repository: Responsável pela persistência de dados no banco de dados.
