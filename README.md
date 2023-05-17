# Escola API - Projeto P.O.S.

### Descrição do Serviço:

- Escola – Deve fazer cadastro de alunos, professores e turmas. A Escola deve interagir com a Biblioteca para indicar quais usuários são alunos ou professores, de maneira que eles possam pegar uma quantidade maior de livros emprestados.

- Biblioteca – Sua principal função é realizar empréstimos de livros a usuários. Para isto, são necessários cadastros de livros e usuários. A Biblioteca é um serviço independente da Escola, de maneira que qualquer pessoa pode pedir livros emprestados. No entanto, professores e alunos podem pegar uma quantidade maior de livros emprestados. Assim, a Biblioteca deve pedir informações sobre os usuários à Escola para saber se são professores, alunos ou usuários comuns.

- Autenticação – Serviço de autenticação de usuários da Escola e da Biblioteca. Este é o único serviço responsável por armazenar credenciais (login, senha, chaves de acesso…) e fazer autenticação dos usuários (log in, log out). Será usado pela Escola e pela Biblioteca para autenticar seus usuários.

### Como executar o sistema:
# Dependências:
    As principais dependências do peojeto são o software Composer, o framework Laravel e a linguagem de programação PHP.
# Rodando o sistema:
### 1.0
    1. Faça o download do projeto e em seguida, no terminal do seu computador, abra-o no diretório onde o mesmo está localizado.
    2. Com a pasta localizada no seu terminal, insira o seguinte comando: php artisan serve.
    3. Com o sistema rodando, pegue o link que foi gerado e abra no navegador.
### 1.1
    O sistema ainda só responde apenas com duas requisições GET, são elas:
        GET "/":
          Resposta: string JSON contendo {“hello_url” : “/hello”}.
        GET "/hello":
          Resposta: string Hello, World!
