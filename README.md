# projeto-nativa

   Esse repositorio é  uma api e um desafio logico para um processo seletivo desenvolvido com framework spring boot (JAVA), foi implementado spring security para autenticação com jwt (Bearer token).
   Para rodar a aplicação é só escolher a ide (intellij, sts , eclipse e etc), o spring boot já tem o servidor tomcat embutido e por padrão o servidor é levantado na porta 8080
   http://localhost:8080/
   
## Swagger

  para facilitar a interação com a api foi incluido o swagger na aplicação. O Swagger é uma linguagem de descrição de interface para descrever APIs RESTful expressas usando JSON.
  O swagger é acessível na rota /swagger-ui.html - http://localhost:8080/swagger-ui.html#/

![alt text](https://github.com/LucasFreitasRocha/projeto-nativa/blob/master/img/Swagger.PNG)

## Autorização
    A maioria das rotas são protegidas e para acessar é necessario adicionar um token no header "Bearer token"


## Autenticação
  Para se autenticar é enviado um post para rota /atuh com body contendo email e senha
  ![alt text](https://github.com/LucasFreitasRocha/projeto-nativa/blob/master/img/auth.png)
  