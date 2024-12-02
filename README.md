# Projeto E-Commerce

## Narrativa - Produto

- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter **vendedores distintos (terceiros)**.
- Cada produto possui um **fornecedor**.
- Um ou mais produtos podem **compor um pedido**.

## Narrativa - Cliente

- O cliente pode se cadastrar no site com seu **CPF ou CNPJ**.
- O **endereço do cliente** irá determinar o valor do frete.
- Um cliente pode comprar mais de um pedido. Este possui um período de carência para **devolução do produto**.

## Narrativa - Pedido

- Os pedidos são criados por clientes e possuem informações de **compra, endereço e status da entrega**.
- Um ou mais produtos podem **compor o pedido**.
- O pedido pode ser **cancelado**.

---

## Refinando o Modelo

### Cliente PJ e PF
- Uma conta pode ser **Pessoa Jurídica (PJ)** ou **Pessoa Física (PF)**, mas **não pode ter as duas informações ao mesmo tempo**.

### Pagamento
- Um pedido pode ter cadastrada **mais de uma forma de pagamento**.

### Entrega
- A entrega possui:
  - **Status** (ex.: Em trânsito, Entregue, Aguardando retirada).
  - **Código de rastreio** para acompanhamento da entrega.







