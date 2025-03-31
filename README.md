# Projeto Conceitual: Modelagem de Banco de Dados para um E-commerce
- Descrição do Projeto
  - MEste projeto tem como objetivo criar um modelo de banco de dados conceitual utilizando a modelagem Entidade-Relacionamento Estendida (EER) para um sistema de e-commerce. O modelo visa representar de forma estruturada as principais entidades e seus relacionamentos, garantindo a integridade e a eficácia dos dados.
- Modelagem EER
  - A modelagem EER foi desenvolvida para abranger as principais funcionalidades de um e-commerce, incluindo:
    - Cliente: Representa os usuários cadastrados na plataforma.
    - Pedido: Registro de compras realizadas pelos clientes.
    - Entrega: Dados relacionados ao envio dos produtos.
    - Produto: Itens disponíveis para venda.
    - Estoque: Controle da quantidade de produtos disponíveis.
    - Fronecedor: Empresas ou indivíduos que fornecem os produtos.
  - Na modelagem temos também as principais entidade e seus relacioanamentos.
    - Um cliente pode realizar vários pedidos, mas um pedido pertence a apenas um cliente
    - Um pedido pode conter vários produtos, e um produto pode estar em vários pedidos
    - Um pedido está associado a uma entrega, contendo informações sobre o endereço de destino.
    - Os produtos estão vinculados a um estoque, que controla sua disponibilidade.
   - Esses são alguns dos principais relacionamentos na modelagem, podendo haver outros dependendo das regras de negócio.
      
      
- Tecnologias Utilizadas
  - MySQL
  - MySQL Workbench
