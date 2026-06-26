Projeto Banco de Dados - Loja Games

Vinicius Lang 

Descrição

Banco de dados relacional para uma loja de produtos gamer. O sistema controla clientes, funcionários, produtos, pedidos e itens de pedidos.

Tabelas

clientes
funcionarios
produtos
pedidos
itens_pedido

Relacionamentos

Um cliente pode realizar vários pedidos.
Um funcionário pode atender vários pedidos.
Um pedido pode possuir vários itens.
Um produto pode aparecer em vários itens de pedido.

Arquivos

loja_games.sql: script completo com criação do banco, tabelas, 50 registros por tabela e consultas.
diagrama/mer_loja_games.png: imagem do modelo entidade-relacionamento.

Como usar

Abra MySQL Workbench, phpMyAdmin ou outro SGBD compatível com MySQL.
Execute o arquivo loja_games.sql.
Teste as consultas no final do script.
