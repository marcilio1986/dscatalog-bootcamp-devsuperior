
# dscatalog-bootcamp-devsuperior
:hammer_and_wrench: Em construção.....

#  
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/marcilio1986/dscatalog-bootcamp-devsuperior/blob/main/LICENSE) 

[Link do projeto no Figma](https://www.figma.com/file/1n0aifcfatWv9ozp16XCrq/DSCatalog-Bootcamp?node-id=1%3A2012)

# Sobre o projeto
## Projeto full stack web e mobile de catálogo de produtos e área administrativa com autenticação e autorização, desenvolvido durante o Bootcamp DevSuperior

# Modelo conceitual 

![Mobile 1](https://github.com/marcilio1986/assets/blob/main/Modelo%20conceitual%20DSCatalog.png)

# Ferramentas necessárias para o desenvolvimento do projeto :
## JDK 11
## STS
## Postman
## Postgresql 12 e pgAdmin
## Heroku CLI
## NPM
## VS Code
## Git

## Capítulo 1 -- CRUD - BACKEND

#-01 Visão geral do capítulo  ------------------------------------------------------------->>  Concluido 


#-02 Visão geral do ecossistema Spring  --------------------------------------------------->>  Concluido


#-03 Aviso sobre o processo de desenvolvimento  ------------------------------------------->>  Concluido


#-04 Visão geral do app dscatalog  -------------------------------------------------------->>  Concluido


#-05 Instalação das ferramentas  ---------------------------------------------------------->>  Concluido


#-06 Criação do projeto Spring Boot  ------------------------------------------------------>>  Concluido


#-07 Salvando o projeto no Github  -------------------------------------------------------->>  Concluido


#-08 Classe Category  --------------------------------------------------------------------->>  Concluido


#-09 Category Resource  ------------------------------------------------------------------->>  Concluido


#-10 Observações importantes sobre o sistema  --------------------------------------------->>  Concluido


#-11 Banco de dados H2, camadas  ---------------------------------------------------------->>  Concluido


#-12 Transações e sessão JPA  ------------------------------------------------------------->>  Concluido


#-13 Seeding da base de dados  ------------------------------------------------------------>>  Concluido


#-14 DTO  --------------------------------------------------------------------------------->>  Concluido


#-15 Criando um ambiente de execução no Postman  ------------------------------------------>>  Concluido


#-16 Buscando categoria por id  ----------------------------------------------------------->>  Concluido


#-17 Tratamento de exceções  -------------------------------------------------------------->>  Concluido


#-18 Inserindo nova categoria com POST  --------------------------------------------------->>  Concluido


#-19 Atualizando categoria com PUT  ------------------------------------------------------->>  Concluido


#-20 Deletando categoria com DELETE  ------------------------------------------------------>>  Concluido


#-21 Dados de auditoria  


#-22 Paginação


#-23 Entidade Product, revisão modelo relacional N-N


#-24 Mapeamento JPA N-N, script SQL completo


#-25 ProductDTO


#-26 Product repository, service, resource, GET ok


#-27 Product insert, update, delete


#-28 Apresentando o trabalho final do capítulo


TAREFA: API CRUD de clientes



## Capítulo 2 --  Testes automatizados

#-01 Visão geral do capítulo


#-# Tipos de teste


#-03 Benefícios dos testes automatizados


#-04 O que é TDD


#-05 Boas práticas para testes


#-06 Visão geral do JUnit


#-07 Primeiro teste na prática com JUnit


#-08 Observação sobre TDD


#-09 Teste deposito deveria fazer nada quando quantia for negativa


#-10 Padrão de projeto Factory para instanciar objetos


#-11 Teste saque total deveria limpar saldo e retornar todo saldo


#-12 Testes para método withdraw


#-13 Exercício JUnit vanilla


#-14 Baixando o projeto do capítulo 1 (se precisar)


#-15 Refatoração no Pageable


#-16 Visão geral de testes com Spring, principais annotations


#-17 Primeiro teste de repository


#-18 Testando outro cenário do delete


#-19 Fixtures no JUnit, BeforeEach


#-20 Testando save com id nulo


#-21 Exercício com repository


#-22 Começando testes de ProductService, Mockito vs MockBean


#-23 Primeiro teste, simulando comportamento com Mockito


#-24 Imports estáticos do Mockito


#-25 Teste delete lança ResourceNotFoundException quando id não existe


#-26 Teste delete lança DatabaseException quando id dependente


#-27 Simulando comportamentos diversos com Mockito


#-28 Testando findAllPaged do ProductService


#-29 Exercício testes de unidade com Mockito


#-30 Começando testes na camada web


#-31 Legibilidade e negociação de conteúdo


#-32 Testando o findById


#-33 Testando o update


#-34 Simulando outros comportamentos do ProductService


#-35 Exercício testes na camada web


#-36 Nosso primeiro teste de integração


#-37 Teste de integração para findAllPaged


#-38 Teste de integração na camada web findAll


#-39 Teste de integração na camada web update


#-40 Apresentando o desafio TDD resolvido


#-41 Implementando o desafio resolvido


#-42 Desafio TDD para entregar


TAREFA: TDD Event-City



## Capítulo 3 -- Validação e segurança

#-01 Visão geral do capítulo


#-02 Baixando o projeto pronto ao final deste capítulo


#-# Baixando o projeto do capítulo anterior (se precisar)


#-04 Implementando entidades User e Role


#-05 Mapeamentos objeto-relacional, seed do banco


#-06 CRUD de usuários PARTE 1


#-07 CRUD de usuários PARTE 2


#-08 CRUD de usuários PARTE 3


#-09 Introdução ao Bean Validation


#-10 Testando anotações básicas


#-11 Tratando exceção MethodArgumentNotValidException


#-12 Resposta customizada para erro de validação


#-13 Implementando um ConstraintValidator customizado


#-14 UserUpdateValidator PARTE 1


#-15 UserUpdateValidator PARTE 2


#-16 Token JWT, autenticação e autorização


#-17 OAuth2


#-18 Como funciona o processo de login


#-19 Checklist do Spring Security


#-20 Checklist do Spring OAuth e JWT


#-21 Ajustando o arquivo pom.xml


#-22 Implementando checklist do Spring Security


#-23 Implementando OAuth2 authorization server


#-24 Externalizando configuração, variáveis de ambiente


#-25 Adicionando informações ao token


#-26 Implementando OAuth2 resource server


#-27 Configuração especial para o banco H2


#-28 Deixando o Postman top


#-29 Spoiler - próximos tópicos de autenticação e autorização


#-30 Apresentando o desafio resolvido


#-31 Reaproveitando a infraestrutura do DSCatalog


#-32 Implementando as funcionalidades


#-33 Desafio para entregar


TAREFA: Validação e segurança




## Capítulo 4 -- Dominio e ORM , Autorizações

##-01 Visão geral do capítulo


##-02 Visão geral do sistema DSLearn


##-03 Baixando o projeto pronto (opcional)


##-## Setup do projeto DSLearn


##-05 User, Role


##-06 Course


##-07 Offer


##-08 Resource


##-09 Section


##-10 Enrollment, EnrollmentPK


##-11 Enrollment seed


##-12 Correção - Offer sem timezone


##-13 Lesson, Content, Task


##-14 Lesson seed, correção - lessonsDone


##-15 Restante da implementação, clone do projeto


##-16 Correções adicionais no código


##-17 Últimas considerações sobre o projeto do Github


##-18 Preparando para a segunda parte do capítulo - autorizações


##-19 Criando os repositories


##-20 Incluindo exceções, validação e segurança ao projeto


##-21 Busca de usuário por id


##-22 Autorização customizada em nível de serviço PARTE 1


##-23 Autorização customizada em nível de serviço PARTE 2


##-24 Conteúdo customizado para usuário logado


##-25 Refresh token


##-26 Pré-autorizando métodos por perfil de usuário


##-27 Desafio para entregar


TAREFA: MovieFlix domínio e autorização



## Capítulo 5 -- Consultas ao Banco de Dados 


##-01 Visão geral do capítulo


##-02 Baixando os projetos prontos


##-03 Orientações de estudo sobre SQL


##-04 Postgresql 12 instalado neste momento


##-## URI 2602 - Elaborando a consulta


##-06 Baixando os projetos iniciados dos estudos de caso


##-07 URI 2602 Spring Boot SQL


##-08 URI 2602 Spring Boot JPQL


##-09 URI 2611 Elaborando a consulta


##-10 URI 2611 Spring Boot SQL e JPQL


##-11 URI 2621 Elaborando a consulta


##-12 URI 2621 Spring Boot SQL e JPQL


##-13 Dica - pratique um pouco se você estiver precisando


##-14 URI 2609 Elaborando a consulta


##-15 URI 2609 Spring Boot SQL e JPQL


##-16 URI 2737 Elaborando a consulta


##-17 URI 2737 Solução alternativa


##-18 URI 2737 Spring Boot SQL


##-19 URI 2990 Elaborando a consulta


##-20 URI 2990 Solução alternativa


##-21 URI 2990 Spring Boot SQL e JPQL


##-22 Preparando o DSCatalog do fim do capítulo 3


##-23 Query methods


##-24 Problema N+1 consultas com Spring Data JPA


##-25 Disclaimer - avisos sobre o DSCatalog


##-26 Filtrar produtos, INNER JOIN, IN


##-27 Filtrar produtos, DISTINCT, IS NULL


##-28 Filtrar produto, FNC, LIKE, LOWER, CONCAT, Trim


##-29 Filtrar produtos, COALESCE, List


##-30 Lidando com o famigerado problema N mais 1 consultas


##-31 Corrigindo os testes do DSCatalog


##-32 Configuração de CORS no DSCatalog


##-33 Consulta de notificações do DSLearn


##-34 Apresentando o desafio para entregar


##-35 Explicação adicional: DTOs de cada requisição


TAREFA: MovieFlix casos de uso



## Capítulo 6 -- Docker, Implantação, CI/CD

##-01 Visão geral do capítulo


##-02 Instalação do Docker


##-03 Introdução a Docker e containers


##-04 Imagem, container, registry


##-05 Docker ps, images, pull, start, stop


##-## Instanciando um container Postgres


##-07 Comandos básicos de manutenção no Docker


##-08 Arquivo Dockerfile


##-09 Analisando os demais exemplos de Dockerfile


##-10 Volumes no Docker


##-11 Enviando imagens para o DockerHub


##-12 Começando a implantação manual - baixando o DSCatalog


##-13 Perfis de projeto, variáveis de ambiente


##-14 Gerando imagem com Dockerfile


##-15 Criando base de dados Postgres remota no Heroku


##-16 Instanciando um container no modo dev


##-17 Cadastro na Amazon AWS e usuário IAM


##-18 Criando instância EC2


##-19 Acessar instância EC2 via SSH e instalar Docker


##-20 Criando base de dados no Amazon RDS


##-21 Conectando e instanciando a base de dados


##-22 Enviando imagem para DockerHub


##-23 Instanciando um container para conectar ao banco do RDS


##-24 Instanciando o container no EC2


##-25 CI CD no Heroku


##-26 CI CD na AWS com Github Actions - visão geral


##-27 Primeiro teste Github Actions


##-28 Etapa 1 - Conexão e Cloud Shell


##-29 Etapa 2 - Rede


##-30 Etapa 3 - Banco de dados RDS


##-31 Administração do banco de dados


##-32 Etapa 4 - Aplicação Elastic Beanstalk e bucket S3


##-33 Etapa 5 - Subindo build zero para nuvem


##-34 Etapa 6 - Implantando build zero no Elastic Beanstalk


##-35 Etapa 7 - Criando environment no Elastic Beanstalk


##-36 Etapa 8 - Configurando variáveis de ambiente adicionais


##-37 Etapa 9 - Configurando environment secrets no Github


##-38 Etapa 10 - Incluindo pipeline Github Actions


##-39 Exterminando os recursos da AWS








Marcilio Bruno Dias da Silva



