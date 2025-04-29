📦E-commerce Database
Este projeto descreve o modelo relacional de um sistema de banco de dados para uma plataforma de E-commerce, suportando vendedores terceiros, fornecedores, estoque, clientes, pedidos e pagamentos.

🗂️ Estrutura do Banco de Dados
O modelo é dividido em diversas entidades que se relacionam para formar o fluxo completo de uma operação de comércio eletrônico:

📌 Principais Entidades
Produto: Catálogo de produtos com categoria, descrição e valor.

Fornecedor: Responsável por fornecer produtos.

Terceiro-Vendedor: Representa vendedores terceiros que também ofertam produtos.

Estoque: Locais físicos onde os produtos estão armazenados.

Cliente: Usuários que realizam pedidos, com suporte a múltiplos meios de pagamento.

Pedido: Inclui os produtos comprados, cliente, entrega e status.

Entrega: Controle de rastreio e status de entrega dos pedidos.

Pagamento: Suporta cartão de crédito, débito, boleto e Pix.

🔁 Relacionamentos
Produto_has_Estoque: Indica a quantidade de um produto em determinado estoque.

Disponibilizando_um_Produto: Produtos fornecidos por fornecedores.

Produtos_por_Vendedor: Produtos ofertados por vendedores terceiros.

Relação de Produto por Pedido: Produtos vinculados a um pedido.

Cliente <-> Cartões: Um cliente pode ter mais de um cartão de crédito e débito.

Pedido <-> Pagamento: Pagamento pode envolver diversos métodos e é relacionado ao pedido, cliente e entrega.

🧾 Tipos de Pagamento Suportados
Cartão de Crédito

Cartão de Débito

Boleto Bancário

Pix

📦 Funcionalidades Esperadas
Cadastro e oferta de produtos por fornecedores e vendedores terceiros.

Controle de estoque por localização.

Geração e rastreio de pedidos.

Processamento de múltiplas formas de pagamento por cliente.

Histórico de pedidos, entregas e pagamentos.
