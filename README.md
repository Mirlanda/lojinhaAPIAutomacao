## Lojinha API Automação

Esse é um repositório que contém alguns testes de API Rest de um software chamado Lojinha. Os subtópicos abaixo descrevem algumas decisões tomadas na estruturação do projeto.

# Tecnologias utilizadas

-Java
https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html
-JUnit
https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-engine/5.7.2

-RestAssured
https://mvnrepository.com/artifact/io.rest-assured/rest-assured/4.4.0

-Maven
https://maven.apache.org/

##Testes Automatizados
- Testes para validar as partições de equivalência relacionados ao valor do produto na Lojinha, que estão vinculados diretamente a regra de negocio que diz que o valor do produto deve estar entre 0.01 e 7.000,01.

# Notas Gerais
Sempre utilizamos a notação beforeEach para capturar o token que será utilizado posteriormente nos métodos de testes.

POJO
Criamos dados iniciais através do uso da classe Data Factory para facilitar a criação e controle dos mesmos. 

