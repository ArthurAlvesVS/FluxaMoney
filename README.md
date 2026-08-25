# FluxaMoney

Aplicação web para organização, acompanhamento e análise de finanças pessoais.

O FluxaMoney permite registrar receitas e despesas, acompanhar indicadores financeiros em dashboards, definir metas e visualizar projeções e análises sobre a evolução financeira do usuário.

## Funcionalidades

* Cadastro de receitas e despesas
* Sistema de login e autenticação
* Filtros por mês, ano e descrição
* Dashboard com indicadores financeiros
* Gráficos de categorias e evolução mensal
* Diagnóstico financeiro automático
* Comparação com períodos anteriores
* Alertas financeiros
* Definição de metas mensais
* Projeção de economia
* Exportação de dados em CSV e Excel

## Tecnologias

* Python
* Flask
* SQLAlchemy
* SQLite
* JavaScript
* HTML e CSS
* Chart.js
* Git/GitHub

## Arquitetura geral

```text
Usuário
   ↓
Flask
   ↓
Autenticação e regras da aplicação
   ↓
SQLAlchemy
   ↓
SQLite
   ↓
Dashboard e visualizações
   ↓
Chart.js
```

## Principais recursos técnicos

### Autenticação

A aplicação possui sistema de login para controlar o acesso às informações financeiras de cada usuário.

### Persistência de dados

Os dados são armazenados em SQLite e manipulados utilizando SQLAlchemy.

### Dashboard

O sistema consolida os dados financeiros e apresenta indicadores, gráficos e comparações para facilitar o acompanhamento da evolução financeira.

### Análises financeiras

A aplicação calcula informações como:

* Total de receitas
* Total de despesas
* Saldo
* Gastos por categoria
* Evolução mensal
* Margem financeira
* Metas e projeções

## Como executar

Clone o repositório:

```bash
git clone https://github.com/ArthurAlvesVS/FluxaMoney.git
```

Entre na pasta:

```bash
cd FluxaMoney
```

Crie o ambiente virtual:

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### macOS/Linux

```bash
source venv/bin/activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute a aplicação:

```bash
python app.py
```

Acesse no navegador:

```text
http://127.0.0.1:5000
```

## Documentação

A pasta `/docs` contém documentação adicional sobre a estrutura e o funcionamento da aplicação.

## Objetivo do projeto

O FluxaMoney foi desenvolvido como projeto prático para aplicar conceitos de desenvolvimento web, autenticação, persistência de dados, modelagem de banco de dados, análise de informações e construção de dashboards utilizando Python e Flask.

## Status

Em desenvolvimento.

## Autor

Arthur Alves Vasconcelos da Silva