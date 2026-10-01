# Projeto Gestão de Alunos

Este projeto consiste na criação de uma pequena aplicação para **gerir informações de alunos**.  
O objetivo é permitir consultar, adicionar e organizar dados de forma simples.  
O projeto foi desenvolvido como exercício de aprendizagem de programação e bases de dados.


## Tecnologias

As principais tecnologias utilizadas no projeto são:

| Tecnologia | Versão |
|:---:|:---:|
| HTML | 5 |
| CSS | 3 |
| JavaScript | ES6 |
| MySQL | 8.0 |

## Funcionalidades

O projeto permite:

- Consultar alunos
- Adicionar novos alunos
- Alterar informações
- Eliminar registos
- Consultar dados através de SQL

### Tarefas

- [x] Criar a base de dados
- [x] Criar as tabelas
- [x] Inserir dados
- [ ] Criar a página principal
- [ ] Testar todas as funcionalidades

## Instalação

Para instalar e executar o projeto:

1. Instalar o **XAMPP**.
2. Iniciar o Apache e o MySQL.
3. Criar a base de dados no MySQL.
4. Importar o ficheiro `database.sql`.
5. Abrir o projeto no navegador.

### Comando SQL

Exemplo de criação da base de dados:

```sql
CREATE DATABASE gestao_alunos;

USE gestao_alunos;

CREATE TABLE aluno (
    id INT PRIMARY KEY,
    nome VARCHAR(100),
    idade INT
);
```

O ficheiro de configuração utilizado no projeto chama-se `config.txt`.

> **Nota importante:** Antes de executar o projeto, é necessário confirmar que o serviço MySQL está ativo.

## Links

- [GitHub](https://github.com/)
- [MySQL](https://www.mysql.com/)
- [Markdown Guide](https://www.markdownguide.org/)

## Autores

Projeto desenvolvido por **Hugo Teixeira** no âmbito da formação.

Este projeto tem como objetivo aplicar os principais elementos da linguagem *Markdown* e melhorar os conhecimentos de documentação de projetos.
