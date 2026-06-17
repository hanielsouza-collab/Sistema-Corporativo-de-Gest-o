# CorpManager API

## Nome do Projeto

CorpManager API

## Integrantes

Haniel Sousa
Gabriel Henrique
Kaique de Souza
Matheus Pereira

## Descrição do Sistema

O projeto CorpManager API consiste em um sistema corporativo desenvolvido para gerenciar colaboradores de uma empresa de médio porte, substituindo planilhas e registros físicos por uma solução digital moderna.

A aplicação permite cadastrar, visualizar, atualizar e remover colaboradores através de uma API REST conectada a um banco de dados MySQL, garantindo persistência e organização dos dados.

Além disso, o sistema conta com uma interface frontend simples para cadastro e visualização das informações cadastradas.

## Tecnologias Utilizadas

* Node.js
* Express
* MySQL
* JavaScript
* HTML5
* CSS3
* JSON
* Postman

## Estrutura do Banco de Dados

Banco: empresa

Tabela: colaboradores

Campos obrigatórios:

* id
* nome_completo
* idade
* cargo
* salario
* tempo_empresa
* data_admissao
* setor
* status

## Instruções para Execução

1. Instalar dependências:

```bash
npm install express cors mysql2
```

2. Criar banco MySQL chamado empresa

3. Criar tabela colaboradores

4. Executar servidor:

```bash
node server.js
```

5. Abrir frontend e testar aplicação

## Funcionamento da API

Rotas implementadas:

* POST → cadastrar colaborador
* GET → listar colaboradores
* PUT → atualizar colaborador
* DELETE → remover colaborador

## Integração com MySQL

Todos os dados são armazenados permanentemente no banco de dados MySQL, sem uso de arrays locais.

## Frontend

O frontend permite:

* Cadastro de colaboradores
* Exibição dinâmica dos colaboradores cadastrados

## Testes no Postman

Foram realizados testes completos nas rotas:

* GET
* POST
* PUT
* DELETE

Com retorno em JSON e comunicação correta entre API e banco de dados.



Prints:

Mysql Select*From:
<img width="1457" height="905" alt="image" src="https://github.com/user-attachments/assets/9f2665ba-4899-4844-964f-f95c196206ee" />

Postman Get:
<img width="1866" height="863" alt="image" src="https://github.com/user-attachments/assets/8c4393ca-69ff-4d81-85b4-66d757e2d92b" />

Postman Post:
<img width="1860" height="865" alt="image" src="https://github.com/user-attachments/assets/ea6e3e61-dab8-4280-ae68-c95342b85c20" />

Postman Put:
<img width="1860" height="862" alt="image" src="https://github.com/user-attachments/assets/458f4b09-5ac3-4bd8-b449-38442cb2434b" />

Postman Delete:
<img width="1858" height="857" alt="image" src="https://github.com/user-attachments/assets/971dc287-c26e-4964-98d3-ea3b5941fe50" />

Resultado final:
<img width="1901" height="960" alt="image" src="https://github.com/user-attachments/assets/31362a27-1b3b-42aa-a633-de3f6bb19fe6" />

