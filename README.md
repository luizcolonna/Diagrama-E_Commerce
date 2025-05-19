# 🛒 Projeto de Banco de Dados - E-commerce

Este projeto apresenta o modelo de banco de dados de um sistema de **e-commerce**, desenvolvido para simular uma plataforma de vendas online com múltiplos fornecedores, vendedores terceiros e controle de estoque.

## 📌 Objetivo

O objetivo principal é praticar e demonstrar conhecimentos em modelagem de banco de dados relacional, utilizando diagramas ER e estrutura lógica, visando aplicações acadêmicas ou como base para sistemas reais.

## 🧱 Estrutura do Banco de Dados

O modelo contempla as principais entidades e seus relacionamentos:

- **Cliente**: Armazena informações pessoais e dados bancários.
- **Cartão de Crédito**: Relacionado ao cliente, usado como forma de pagamento.
- **Pedido**: Registro das compras realizadas pelo cliente.
- **Status**: Representa a situação atual do pedido (ex: entregue ou não).
- **Produto**: Itens disponíveis para venda, com categoria, valor e descrição.
- **Relação Produto x Pedido**: Permite pedidos com múltiplos produtos e quantidades.
- **Estoque**: Controle da quantidade de produtos em diferentes locais.
- **Produto_has_Estoque**: Relacionamento entre produtos e estoques.
- **Fornecedor**: Empresas fornecedoras dos produtos.
- **Disponibilizando**: Relacionamento entre fornecedores e produtos que oferecem.
- **Terceiro Vendedor**: Vendedores terceiros que também oferecem produtos.
- **produtosPorVendedor**: Relacionamento entre vendedores terceiros e seus produtos.

## 🔄 Relacionamentos Principais

- Um cliente pode fazer vários pedidos.
- Um pedido pode conter vários produtos (relação N:N com tabela intermediária).
- Um produto pode estar disponível em diferentes estoques.
- Um fornecedor pode fornecer diversos produtos.
- Um produto pode ser vendido por diferentes vendedores terceiros.

## 🛠️ Tecnologias Utilizadas

- Diagrama ER feito com ferramenta de modelagem visual (como MySQL Workbench).
- Modelagem compatível com bancos relacionais como MySQL.
