# desafio_e-commerce
Projeto Conceitual refinado do e-commerce

Cliente PJ e PF: criei duas entidades especializadas: CPF e CNPJ, que herdam os atributos do cliente.
Pagamento: criei uma entidade Pagamento com relacionamento 1:n com Cliente pois o cliente pode ter vários cartões mas um cartão só pode ter um cliente.
Entrega: criei uma entidade Entrega com relacionamento 1:n com Pedido pois um pedido por gerar várias entregas, a depender dos produtos comprados de diferentes vendedores terceiros, mas uma entrega só pode ter um pedido.
