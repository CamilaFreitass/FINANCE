# FINANCE :moneybag:

Essa aplicação foi desenvolvida no curso Pythonfull e é uma aplicação para gestão de finanças pessoais. Dentro dessa aplicação terá o cadastro de entradas de ganho financeiro, cadastro de despesas, cadastro de contas, planejamento financeiro, equilibrio financeiro, receitas e despesas mensais e gerenciamento de boletos/contas a pagar. 

### Pré-requisitos para rodar a aplicação:

Instalar Python e Git.

### Tecnologias utilizadas:

[![My Skills](https://skillicons.dev/icons?i=py,django,sqlite,bootstrap,html,css,js,git)](https://skillicons.dev)

* Python 3.10.2
* Django 4.2.6
* SQLite 
* Bootstrap
* HTML 
* CSS 
* JavaScript
* Git

### Como instalar a aplicação localmente 💻:

Clona o repositório:
```
git clone https://github.com/CamilaFreitass/FINANCE.git
```
Instala os pré-requisitos:
```
pip install requirements.txt
```
Sobe o servidor:
```
python manage.py runserver
```
Acessa a aplicação:
```
http://127.0.0.1:8000/perfil/home/
```

### Funcionalidades:

* Cadastrar contas bancárias
* Cadastrar entradas e saídas financeiras
* Classificar despesas como essenciais e não essenciais
* Acompanhamento financeiro mensal
* Cadastrar despesas por categoria
* Visualizar graficamente os gastos por categoria
* Gerar extrato em PDF de entradas e saídas
* Visualizar extrato de entradas e saídas
* Filtrar o extrato por conta e/ou categoria 
* Visualizar as contas em vencidas, próximo ao vencimento e demais contas
* Cadastrar contas a pagar e contas pagas
* Definir e visualizar planejamento das contas

### Entidades/Tabelas:

* ContaPagar
* ContaPaga 
* Valores
* Categoria
* Conta 


