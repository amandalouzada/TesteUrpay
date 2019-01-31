# Projeto Teste - Urpay
## Veículos

O projeto consiste em criar uma API REST para gerenciamento de veículos. Esta API deve ser feita utilizando Node.js com MongoDB. Sugerimos as seguintes biliotecas Node para este projeto:

* [__Express.js__](https://expressjs.com/) - Framework para aplicações web em Node.js.
* [__Mongoose__](https://mongoosejs.com/) - Modelagem de objetos Mongo para Node.js.

### Estrutura do Banco de dados

O banco deve possuir apenas uma Collection chamada `veiculo`. Dentro dessa Collection deve ter os seguintes campos:

* __placa__: Número da placa do veículo, no formato `AAA9999`. **Este campo deve ser único para cada veículo.**
* __marca__: Marca da construtora do veículo.
* __modelo__: Modelo do veículo.
* __cor__: Cor do veículo.
* __ano_fabricacao__: Ano de fabricação do veículo.
* __data_cadastro__: Data do cadastro do veículo no sistema.
* __revisoes__: Uma lista de objetos contendo informações sobre as revisões do veículo. Os objetos devem conter os seguintes campos:
  * __data_revisao__: Dia em que foi feita a revisão
  * __valor__: Valor pago pelo serviço de revisão.
  
### API WEB

A API do projeto deve possuir os seguintes endpoints:
* [Cadastrar Veículo](#cadastrar-veículo)
* Listar Veículos
* Consultar Veículo
* Editar Veículo
* Deletar Veículo
* Adicionar Revisão
* Consultar Total de gasto em revisões do veículo

#### Cadastrar Veículo

Teste
