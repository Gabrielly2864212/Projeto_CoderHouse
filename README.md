# Projeto Final - Python
### Aluna: Gabrielly Simone Miranda da Silva
### Curso: Python - CoderHouse
### Turma: 63730
### Professor: Gabriel Rodrigues

Este projeto tem como objetivo acessar três APIs públicas, extrair os dados e armazená-los em um banco de dados SQLite. O código utiliza bibliotecas como `requests` para fazer as requisições HTTP, `pandas` para manipulação de dados e `sqlite3` para armazenar os dados em um banco de dados relacional.

## APIs Utilizadas
1. **API de Bancos**: Fornece informações sobre bancos no Brasil. [Link da API](https://brasilapi.com.br/api/banks/v1)
2. **API de Feriados**: Retorna informações sobre os feriados nacionais do Brasil para o ano de 2024. [Link da API](https://brasilapi.com.br/api/feriados/v1/2024)
3. **API de CNPJ**: Retorna dados sobre uma empresa específica, identificada por seu CNPJ. [Link da API](https://brasilapi.com.br/api/cnpj/v1/00000000000191)

## Requisitos
Para executar o projeto, é necessário instalar as dependências listadas no arquivo `requirements.txt`.

### Dependências:
- `requests==2.31.0`
- `pandas==1.5.3`
- `sqlite3==3.8.3` (parte do Python)

### Como Instalar as Dependências:
Execute o seguinte comando no terminal para instalar todas as dependências:
```bash
pip install -r requirements.txt