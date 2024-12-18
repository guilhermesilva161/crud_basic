# CRUD Básico com Laravel 11 e PHP 8.2

Este projeto foi desenvolvido como uma avaliação na faculdade, é um exemplo de um CRUD (Create, Read, Update, Delete) básico desenvolvido com **Laravel 11** e **PHP 8.2**. O objetivo deste projeto é demonstrar os principais conceitos do Laravel, incluindo a criação de rotas, controllers, models e views.

## Pré-requisitos

É necessário ter os seguintes itens instalados em sua máquina:

- **PHP 8.2 ou superior**
- **Composer**
- **Laravel 11**
- **Banco de dados (MySQL)**

## Instalação

Siga os passos abaixo para rodar o projeto localmente.

### 1. Clone o repositório

Clone o repositório para sua máquina local utilizando o seguinte comando:

```bash
git clone https://github.com/guilhermesilva161/crud_basic.git
```
### 2.Instale as dependencias 

```bash
cd nome-do-repositorio
composer install
``` 

### 3. Configure
No arquivo .env configure seu banco de dados
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=crud_basico
DB_USERNAME=root
DB_PASSWORD= sua_senha

Após configurar e criar o banco de dados migre as tabelas

```bash
php artisan migrate
```
### Execução 

php artisan serve

Em um browser copie e cole : http://127.0.0.1:8000/login
 





