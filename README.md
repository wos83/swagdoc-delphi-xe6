# SwagDoc
SwagDoc é uma biblioteca Delphi (eu modifiquei para que funcione na versão XE6) para gerar arquivo swagger.json para Swagger Spec versão 2.0. Crie uma API REST de documentação pública usando Swagger 2.0 para Delphi Language. A única responsabilidade do SwagDoc é gerar o arquivo swagger.json. O arquivo swagger.json é responsável por conter toda a documentação da sua API REST. Este arquivo deve ser anexado aos arquivos Swagger UI (User Interface).

## Swagger (Open API) - version 2.0

SwagDoc segue a especificação 2.0 por ser mais popular no mercado e também por ser considerada uma versão mais estável por mais tempo. SwagDoc ainda não suporta a versão Swagger 3.0, mas dependendo da demanda e contribuições para o projeto pode evoluir para suportar a especificação 3.0.

O principal pré-requisito para trabalhar com SwagDoc é conhecer a especificação Swagger 2.0 que pode ser visualizada no link abaixo.

https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md

https://swagger.io/docs/specification/2-0/basic-structure/

Ao criar uma documentação do Swagger para sua API REST, você pode produzir uma página como o exemplo a seguir.

https://app.swaggerhub.com/apis-docs/swagdoc/sample-api/v1

![image](https://user-images.githubusercontent.com/20048296/46588904-c6cd5880-ca79-11e8-8a8a-ec38ba7ff95a.png)


## Json Schema

https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md#schemaObject

http://json-schema.org


## SwagDoc Speeches

https://www.youtube.com/watch?v=9U3HP3B5UT0 (Pt-Br)

https://www.youtube.com/watch?v=PhgMQAd8O6c (Pt-Br)


## Swagger References and Tutorials 

https://swagger.io/swagger/media/blog/wp-content/uploads/2017/02/Documenting-An-Existing-API-with-Swagger-2.pdf

https://idratherbewriting.com/learnapidoc/pubapis_swagger_intro.html


## Swagger Tools

- Swagger:
https://swagger.io

- Swagger Editor:
https://editor.swagger.io

- Swagger Hub:
https://swagger.io/tools/swaggerhub

- Veja a demo rodando:
http://petstore.swagger.io

- Ferramentas e Integrações:
https://swagger.io/tools/open-source/open-source-integrations


## Swagger UI distribution files

Para você produzir uma página contendo uma documentação do Swagger, você precisa dos arquivos de distribuição do Swagger UI.

Esses arquivos você pode encontrar no repositório github swagger-api / swagger-ui.

https://github.com/swagger-api/swagger-ui/tree/master/dist

![image](https://user-images.githubusercontent.com/20048296/39937130-2925f868-5525-11e8-921d-c9ff0f59fefd.png)


Primeiro você precisa baixar os arquivos de interface do usuário swagger e gerar o arquivo swagger.json. Em seguida, você precisa alterar o arquivo index.html para indicar o caminho relativo do local onde o arquivo swagger.json está localizado em seu servidor web que está hospedando os arquivos de interface do usuário swagger.

Veja um exemplo abaixo.

![image](https://user-images.githubusercontent.com/20048296/39946376-49ad0df0-5544-11e8-8a5c-0980f5e6c257.png)
