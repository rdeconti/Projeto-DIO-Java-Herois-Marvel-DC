:spiral_calendar: Atualizado em 10 de abril de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One Java

# Criando seu gerenciador de super heróis da Marvel e da DC em uma API reativa com Spring Boot
- Este projeto foi proposto pela Digital Innovation One - Link do código original: https://github.com/Kamilahsantos/Heroes-SpringWebflux-API
- Professor: Kamila Santos
- Aulas: https://web.digitalinnovation.one/lab/criando-seu-gerenciador-de-super-herois-da-marvel-e-da-dc-em-uma-api-reativa-com-spring-boot/learning/82d5791a-c271-4f34-92d4-76364a05d497

# Descrição
Nesta sessão vamos desenvolver uma API de gerenciamento de heróis utilizando Spring WebFlux, utilizada por empresas como Netflix e Pivotal, junto com a library reativa Reactor que atualmente é mantida pela VmWare. Além disso, usaremos o banco DynamoDb localmente para armazenar nossos dados e demonstrarei como realizar testes unitários da sua API com Junit e como gerar documentações simples por meio do Postman e também do Swagger.

# Ferramentas utilizadas
- Java8
- spring webflux
- Spring data
- dynamodb
- junit
- sl4j
- reactor

### Para executar dynamo:
- na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
- para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000
- dcumentação gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
