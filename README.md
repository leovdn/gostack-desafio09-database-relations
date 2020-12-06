 # GoStack 13: Desafio 09 - Database Relations

Desafio proposto para treinar o que foi aprendido em Node.js junto ao TypeScript, incluindo uso de banco de dados com TypeORM e relacionamentos.

A aplicação que deve permitir a criação de clientes, produtos e pedidos, onde o cliente pode gerar novos pedidos de compra de determinados produtos. Baseado no funcionamento de um pequeno e-commerce.

### Tecnologias utilizadas
- **Nodemon** para monitoramento de alterações no server;
- **Express** como Framework para otimizar o desenvolvimento com Node.js;
- **Cors** para autorização do uso da api em chamadas externas;
- **UUID** como dependência para lidar com criação de identificação única;

_Porta Utilizada: **3333**_

## Requisitos de aprovação :

- [x] should be able to create a new customer

- [x] should not be able to create a customer with one e-mail thats already registered

- [x] should be able to create a new product

- [x] should not be able to create a duplicated product

- [x] should be able to create a new order

- [x] should not be able to create an order with a invalid customer

- [x] should not be able to create an order with invalid products

- [x] should not be able to create an order with products with insufficient quantities

- [x] should be able to subtract an product total quantity when it is ordered

- [x] should be able to list one specific order

