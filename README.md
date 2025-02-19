# Controle de Acesso com Senha

Este projeto é uma implementação simples de um sistema de controle de acesso utilizando JavaScript. Ele permite que um usuário tente acessar até 3 vezes inserindo uma senha. Se a senha estiver correta, o acesso será permitido, caso contrário, o número de tentativas restantes será decrementado. Após 3 tentativas incorretas, o acesso será bloqueado.

## Funcionalidades

- Criação de um **usuário** com **nome** e **senha**.
- O usuário tem até **3 tentativas** para digitar a senha correta.
- O sistema informa quantas tentativas restantes o usuário tem após cada tentativa.
- Após 3 tentativas incorretas, o **acesso é bloqueado**.

## Tecnologias Utilizadas

- **JavaScript**: Linguagem de programação utilizada para a implementação da lógica.

## Como Rodar o Projeto

Este projeto pode ser executado diretamente em um ambiente JavaScript, como um navegador ou no Node.js.

### Para executar no navegador:

1. Crie um arquivo `index.html` e insira o código JavaScript dentro de uma tag `<script>` no final do arquivo, como mostrado abaixo:
    ```html
    <html>
        <head>
            <title>Controle de Acesso</title>
        </head>
        <body>
            <h1>Controle de Acesso com Senha</h1>
            <script src="controleSenha.js"></script>
        </body>
    </html>
    ```

2. Abra o arquivo `index.html` em um navegador e interaja com o prompt de senha.

### Para executar no Node.js:

1. Salve o código JavaScript em um arquivo, como `controleSenha.js`.

2. No terminal, execute o comando:
    ```bash
    node index.js
    ```

## Exemplo de Execução

- **Senha incorreta**:
  ```plaintext
  Digite sua senha: 1234
  Senha incorreta. Você tem 2 tentativa(s) restante(s).

- **Senha correta**
```plaintext
Digite sua senha: 8759
Acesso permitido!
