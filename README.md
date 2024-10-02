# LOGIN ANIMATE 
👨‍🏫FORMULARIO DE CADASTRO E LOGIN EM HTML, CSS, PHP E MARIADB.

<img src="./IMAGENS/FOTO_1.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_3.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_4.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este aplicativo web oferece funcionalidades de cadastro e login para os usuários. 

1. **Cadastro de Usuários:**
   - Os usuários podem se cadastrar fornecendo seu e-mail e senha.
   - Após preencher os campos necessários, o usuário pode clicar no botão "CADASTRAR" para criar sua conta.
   
2. **Login de Usuários:**
   - Usuários registrados podem fazer login fornecendo seu e-mail e senha.
   - Após preencher os campos necessários, o usuário pode clicar no botão "LOGIN" para acessar sua conta.

## EXECUTANDO O PROJETO:
1. **Configuração do Banco de Dados:**
   - Antes de executar o site, é necessário importar o arquivo `DATABASE.sql`. 

2. **Configuração do PHP:**
   - Abra o arquivo `./CODIGO/CODIGO.php` e ajuste as configurações do banco de dados:

     ```php
     $servidor = "localhost";
     $username = "seu_usuario";
     $usersenha = "sua_senha";
     $database = "registro";
     ```

3. **Executando o Aplicativo com Apache:**
   - Coloque os arquivos em um servidor web compatível com PHP (por exemplo, XAMPP, WAMP, LAMP).
   - Acesse o formulário no navegador visitando [http://localhost/CODIGO/index.html](http://localhost/CODIGO/index.html).

4. **Executando o Aplicativo com `php.exe`:**
   - Alternativamente, você pode iniciar o servidor diretamente no diretório `./CODIGO` com o comando abaixo:
   ```bash
   php -S localhost:8080
   ```
   - Em seguida, acesse o formulário no navegador através do endereço: [http://localhost:8080/index.html](http://localhost:8080/index.html).

5. **Cadastro:**
   - Preencha o campo "SEU EMAIL" com seu endereço de e-mail.
   - Digite uma senha no campo "SUA SENHA".
   - Clique no botão "CADASTRAR" para criar sua conta.

6. **Login:**
   - Insira o e-mail cadastrado no campo "SEU EMAIL".
   - Digite a senha associada à sua conta no campo "SUA SENHA".
   - Clique no botão "LOGIN" para acessar sua conta.

## NÃO SABE?
- Entendemos que para manipular arquivos em `HTML`, `CSS` e outras linguagens relacionadas, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE HTML E CSS](https://github.com/VILHALVA/CURSO-DE-HTML-E-CSS)
* [CURSO DE PHP](https://github.com/VILHALVA/CURSO-DE-PHP)
* [CURSO DE MARIADB](https://github.com/VILHALVA/CURSO-DE-MARIADB)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)
- [PROJETO BASEADO NO "CADASTRO E LOGIN COM PHP"](https://github.com/VILHALVA/CADASTRO-E-LOGIN-COM-PHP)
- [A INTERFACE DO FORMULÁRIO FOI BASEADO NO "FORMULARIO ANIMATE"](https://github.com/VILHALVA/FORMULARIO-ANIMATE)




