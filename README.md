# EER_E-COMMERCE

Relação	Tipo
Cliente ↔ ClientePF/PJ	1:1
Cliente ↔ FormaPagamento	1:N
Produto ↔ Fornecedor	N:N
Produto ↔ Estoque	N:N
Produto ↔ VendedorExterno	N:N
Produto ↔ Pedido	N:N
Cliente ↔ Pedido	1:N
Pedido ↔ Entrega	1:1
