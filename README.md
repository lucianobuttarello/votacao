# Funcionalidade 

O projeto foi criando para Klabin que enfrenta um grande problema. Como eles são muito democráticos, todos os dias eles gastam 30 minutos decidindo onde eles irão almoçar.

## Build
Para executar este projeto, execute na linha de comando:

``` mvn clean compile exec:java```

## O Swagger para acessar é o seguinte:

```http://localhost:8080/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config#/```

## Melhorias
Foi implementado um banco H2 onde é salvo em memoria os dados do banco.
para acessar o console basta acessar o link
```http://localhost:8080/h2-console/login.do?jsessionid=d37be510bed4f22ea9f6164c4698d96f```

## Melhorias
Não foi possivel implementar a validação de datas, e escolher o restaurante mais votado da semana, não foi feita nenhum interface de front.


## Faltantes
Devido alguns problemas pessoais, não tive tempo habil de atuar na api, peço desculpas, poderia ter feito algumas melhorias no codigo, mas como o tempo estava apertado não consegui.

