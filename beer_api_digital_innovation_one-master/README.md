<h2>Digital Innovation: Expert class - Desenvolvimento de testes unit�rios para validar uma API REST de gerenciamento de estoques de cerveja.</h2>

Atividade de teste unitario, projeto de uma API REST para o gerenciamento de estoques de cerveja. 
Foram trabalhados os principais conceitos para cria��o de testes unit�rios com JUnit e Mockito. 
Al�m disso, foram desenvolvidas funcionalidades da API se utilizando a t�cnica do TDD.

Durante a sess�o, ser�o abordados os seguintes t�picos:

* Baixar um projeto atrav�s do Git para desenolver nossos testes unit�rios. 
* Apresenta��o conceitual sobre testes: a pir�mide dos tipos de testes, e tamb�m a import�ncia de cada tipo de teste durante o ciclo de desenvolvimento.
* Foco nos testes unit�rios: mostrar o porque � importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
* Principais frameworks para testes unit�rios em Java: JUnit, Mockito e Hamcrest. 
* Desenvolvimento de testes unit�rios para valida��o de funcionalides b�sicas: cria��o, listagem, consulta por nome e exclus�o de cervejas.
* TDD: apresenta��o e exemplo pr�tico em 2 funcionaliades importantes: incremento e decremento do n�mero de cervejas no estoque.
* E como atividade restaram para serem entregues pelos alunos os testes referentes a fun��o de baixas no estoque.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a su�te de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Ap�s executar o comando acima, basta apenas abrir o seguinte endere�o e visualizar a execu��o do projeto:

```
http://localhost:8080/api/v1/beers
```

S�o necess�rios os seguintes pr�-requisitos para a execu��o deste projeto:

* Java 14 ou vers�es superiores.
* Maven 3.6.3 ou vers�es superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.

Abaixo, seguem links bem bacanas, sobre t�picos mencionados durante a aula:

* [SDKMan! para gerenciamento e instala��o do Java e Maven](https://sdkman.io/)
* [Refer�ncia do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Refer�ncias - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Refer�ncia para o padr�o arquitetural REST](https://restfulapi.net/)
* [Refer�ncia pir�mide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

<h4>-RAA-</h4>

