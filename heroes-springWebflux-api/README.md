<h2>Digital Innovation One: Criando seu gerenciador de super heróis da Marvel e da DC em uma API reativa com Spring Boot

Atividade de desenvolvimento de uma API de gerenciamento de heróis utilizando Spring WebFlux, de uma library reativa Reactor.

Foi usado o banco de dados DynamoDb localmente para armazenar dados. 

A aula que deu origem ao projeto contou com testes unitários da sua API com Junit e como gerar documentações simples por meio 
do Postman e também do Swagger.

Para executar o projeto no terminal, digite o seguinte comando:

```dynamo
 java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb

 aws dynamodb list-tables --endpoint-url http://localhost:8000
```

```swagger
http://localhost:8080/swagger-ui-heroes-reactive-api.html
```
<h6>-RAA-</h6>




