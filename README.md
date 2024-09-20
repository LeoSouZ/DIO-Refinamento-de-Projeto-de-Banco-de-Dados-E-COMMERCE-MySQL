Narrativa do Esquema EER:

Cliente escolhe o produto:
Relacionamento: O cliente navega pelo catálogo de produtos disponíveis.
Cardinalidade: Um cliente pode escolher vários produtos (1:N), e cada produto pode ser escolhido por vários clientes (N:M).

Cliente realiza um pedido:
Relacionamento: Após escolher os produtos, o cliente realiza um pedido.
Cardinalidade: Um cliente pode realizar vários pedidos (1:N), mas cada pedido é realizado por um único cliente (N:1).

Pedido contém produtos:
Relacionamento: O pedido feito pelo cliente contém um ou mais produtos.
Cardinalidade: Um pedido pode conter vários produtos (1:N), e cada produto pode estar em vários pedidos (N:M).

Cliente fornece endereço de entrega:
Relacionamento: O cliente fornece um endereço para a entrega do pedido.
Cardinalidade: Um cliente pode ter vários endereços (1:N), mas cada endereço pertence a um único cliente (N:1).

Vendedor processa o pedido:
Relacionamento: O vendedor recebe o pedido e começa a processá-lo.
Cardinalidade: Um vendedor pode processar vários pedidos (1:N), mas cada pedido é processado por um único vendedor (N:1).

Fornecedor fornece produtos:
Relacionamento: Os produtos no pedido são fornecidos por um ou mais fornecedores.
Cardinalidade: Um fornecedor pode fornecer vários produtos (1:N), e cada produto pode ser fornecido por vários fornecedores (N:M).

Cliente efetua o pagamento:
Relacionamento: O cliente efetua o pagamento do pedido.
Cardinalidade: Um pedido pode ter vários pagamentos (1:N), mas cada pagamento está relacionado a um único pedido (N:1).

Pedido é entregue ao cliente:
Relacionamento: O pedido é entregue ao endereço fornecido pelo cliente.
Cardinalidade: Um pedido é entregue a um único endereço (1:1), mas um endereço pode receber vários pedidos ao longo do tempo (N:1).

Cancelamento do Pedido
Cliente solicita o cancelamento do pedido:
Relacionamento: O cliente pode solicitar o cancelamento do pedido antes que ele seja entregue.
Cardinalidade: Um cliente pode solicitar o cancelamento de vários pedidos (1:N), mas cada pedido pode ser cancelado apenas uma vez (1:1).

Processamento do cancelamento:
Relacionamento: O vendedor processa a solicitação de cancelamento.
Cardinalidade: Um vendedor pode processar várias solicitações de cancelamento (1:N), mas cada solicitação de cancelamento é processada por um único vendedor (N:1).

Reembolso do pagamento:
Relacionamento: Se o pagamento já foi efetuado, o cliente recebe um reembolso ou um vale crédito.
Cardinalidade: Um pedido cancelado pode gerar um ou mais reembolsos (1:N), mas cada reembolso está relacionado a um único pedido (N:1).


Exemplo de Fluxo
Maria (Cliente) acessa o site e escolhe três produtos diferentes.
Ela realiza um pedido que contém esses três produtos.
Maria fornece seu endereço para a entrega.
João (Vendedor) recebe o pedido e começa a processá-lo.
Os produtos são fornecidos por dois fornecedores diferentes.
Maria efetua o pagamento do pedido usando seu cartão de crédito.
O pedido é entregue no endereço de Maria.

Exemplo de Fluxo com Cancelamento
Maria (Cliente) acessa o site e escolhe três produtos diferentes.
Ela realiza um pedido que contém esses três produtos.
Maria fornece seu endereço para a entrega.
João (Vendedor) recebe o pedido e começa a processá-lo.
Os produtos são fornecidos por dois fornecedores diferentes.
Maria efetua o pagamento do pedido usando seu cartão de crédito.
Antes da entrega, Maria decide cancelar o pedido.
Maria solicita o cancelamento do pedido.
João processa a solicitação de cancelamento.
Maria recebe o reembolso do valor pago ou um vale crédito (Cliente escolhe a forma de reembolso).
