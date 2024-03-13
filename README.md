# Biblioteca

Aplicação para gerenciamento de bibliotecas. Considerações:

Sistema de gerenciamento de uma biblioteca que permite a organização e controle de livros, membros, empréstimos, devoluções e reservas. O sistema será implementado em Python, utilizando o framework Flask e PostgreSQL como banco de dados. O sistema deve:

1. **Cadastrar Livros**:
    Para o cadastro de livros vamos ter algumas variáveis como título do livro, autor(es), número de cópias disponíveis, editora e ano de publicação.

2. **Cadastrar Membros**:
    Para o cadastro de membros vamos ter algumas variáveis como nome, ID e informações pessoais.
   
3. **Empréstimos**:
    Para o empréstimos de livros vamos ter variáveis como registro do membro que solicitou o empréstimo e sua data.

4. **Devoluções**:
    Para a devolução, será registrado o membro que realizou a devolução e sua data. Vale lembrar que pode-se aplicar multas à entregas atrasadas.

5. **Reservas**:
    Esta seção seria para caso acontecesse uma grande demanda de um mesmo livro, onde será necessário uma fila com base na ordem de solicitação do livro.

6. **Pesquisa e Filtros**:
    Plataforma capaz de pesquisar os livros por título, autor(es) para verificar a disponibilização do mesmo.

7. **Autenticação e Controle de Acesso**:
    Criar acessos administrativos para ações administrativas.

8. **Notificações**:
    Notificação para os membros sobre datas de devolução e disponibilidade de reservas caso solicitado.

9. **Multas e Penalidades**:
    Seção destinada para o cálculo da multa cobrada por atraso de devolução.

10. **Gerenciamento de Estoque**:
    Seção destinada a atualizar o número de cópias de um livro quando este sofrer empréstimo e devoluções.

11. Interface de Usuário (frontend).
    Uma interface de usuário amigável para administradores da biblioteca e membros.

**PostgreSQL**

O banco de dados utilizado neste projeto será o PostgreSQL:

- Instalação do PostgreSQL em [postgresql.org](https://www.postgresql.org/).

**Linguagem**

- A aplicação será desenvolvido em Python, onde podemos instalá-lo seguindo o [link](https://python.org.br/instalacao-linux/).
