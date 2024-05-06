<img src="./planifylogo.svg" width="100" height="100" alt="logo" />

# Planify

## Plano de Desenvolvimento DOMVS iT 2023

Projeto de engenharia e arquitetura de software utilizando microserviços baseados em ASP.NET Core com Clean Architecture e MediatR e interface de gerenciamento com ReactJS.

### Diagrama de Arquitetura
![Diagrama de Arquitetura](./architecture.svg)

### Fluxo de Autenticação
![Fluxo de Autenticação](./auth_flow.svg)

### Como rodar o projeto

O projeto utiliza Docker para rodar os serviços, então é necessário ter o Docker instalado na máquina.

1. Clone o repositório com os submódulos
```shell
git clone --recurse-submodules
```
2. Entre na pasta principal do projeto
```shell
cd domvsit-pdi23
```
3. Rode o comando para subir os serviços
```shell
docker-compose up
```
4. Acesse o frontend em http://localhost:3000