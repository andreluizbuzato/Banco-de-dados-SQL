# Banco-de-dados-SQL
# Sistema de Gerenciamento de Alunos

Este projeto é um sistema de console em C# para gerenciar informações de alunos usando SQLite. Permite realizar operações de cadastro, listagem, atualização e exclusão de registros de alunos.

---

## Funcionalidades

- Autenticação simples via login
- Inserção de novos alunos
- Listagem de todos os alunos
- Atualização de informações dos alunos
- Exclusão de alunos pelo ID

---

## Pré-requisitos

- [.NET SDK](https://dotnet.microsoft.com/download) instalado no seu sistema
- SQLite (incluído via pacote NuGet `Microsoft.Data.Sqlite`)

---

## Como usar

1. Clone ou baixe este repositório.
2. Abra o projeto na sua IDE de preferência (por exemplo, Visual Studio ou VS Code).
3. Compile e execute o programa.
4. Na tela de login, insira o usuário `admin` e a senha `1234` para acessar o sistema.
5. Utilize o menu para gerenciar os alunos conforme desejado.

---

## Como funciona

- O sistema cria automaticamente a tabela `Alunos` no banco de dados `alunos.db`, se ela ainda não existir.
- A autenticação é básica, com credenciais fixas (`admin` / `1234`).
- As operações de CRUD (Create, Read, Update, Delete) são realizadas via comandos SQL.

---

## Observações

- As credenciais de login são fixas para simplicidade; recomenda-se implementar um sistema de usuários mais robusto para uso em produção.
- Os dados dos alunos são armazenados localmente no arquivo `alunos.db`.

---

## Licença

Este projeto é apenas um exemplo educacional e pode ser usado livremente. Para projetos comerciais ou mais complexos, recomenda-se implementar melhorias de segurança e funcionalidades adicionais.

---

## Contato

Para dúvidas ou sugestões, envie um e-mail para: seuemail@exemplo.co
