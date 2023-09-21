# Challenge ONE | Back End | Alura Forum 

<p align="center" >
     <img width="200" heigth="200" src="https://user-images.githubusercontent.com/78982435/209698701-28dedb2e-855b-44b2-8872-afa45e3b35aa.png">
</p>


## Sobre o projeto
O fórum da Alura é uma API REST de discussão online onde usuáros podem compartilhar dúvidas, respostas e experiências.

## Diagrama Entidade Relacionamento
![forum_alura_DER](https://github.com/wesley-brwno/challenge-one-forum-alura/assets/84514966/e3c0e9ee-1439-4c12-a537-5cb99c92bdf2)

## Endpoints da API
<table border="1">
    <tr>
        <th>método</th>
        <th>URI</th>
        <th>descrição</th>
        <th>perfil</th>
    </tr>
    <tr>
        <td>POST</td>
        <td>/auth/entrar</td>
        <td>permite que usuário efetue log in</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>POST</td>
        <td>/auth/cadastar</td>
        <td>permite que usuário efetue cadastro na applicação</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/cursos</td>
        <td>lista todos os cursos</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>POST</td>
        <td>/cursos</td>
        <td>cadastra um novo curso</td>
        <td>ADMIN</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/cursos/{id}</td>
        <td>lista um curso por id</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>DELETE</td>
        <td>/cursos/{id}</td>
        <td>deleta um curso por id</td>
        <td>ADMIN</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/respostas</td>
        <td>lista todas as respostas pelo id de um tópico</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>POST</td>
        <td>/respostas</td>
        <td>cria uma resposta para um post</td></td>
        <td>ADMIN | USER</td>
    </tr>
    <tr>
        <td>PUT</td>
        <td>/respostas</td>
        <td>atualiza uma resposta</td>
        <td>ADMIN | USER</td>
    </tr>
    <tr>
        <td>POST</td>
        <td>/respostas/{id}</td>
        <td>marca uma resposta como correta ou incorreta usando seu id</td>
        <td>USER</td>
    </tr>
    <tr>
        <td>DELETE</td>
        <td>/respostas/{id}</td>
        <td>deleta uma resposta por id</td></td>
        <td>ADMIN | USER</td>
    </tr>
</table>

![Inserirjh um título](https://user-images.githubusercontent.com/101230741/188219675-46a897f5-7a17-4593-b026-088bc6afd7b9.png)
