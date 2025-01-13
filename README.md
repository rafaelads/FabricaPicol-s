# FabricaPicolés

Um sistema de gerenciamento de banco de dados para uma fábrica de picolés, utilizando SQL Server. Este projeto inclui a criação de tabelas, inserção de dados, consultas, views e cálculos para gerenciar as retiradas e devoluções de produtos pelos vendedores.

## Tabelas

O banco de dados inclui as seguintes tabelas:
- **Vendedores**: Contém informações sobre os vendedores.
- **Produtos**: Contém informações sobre os produtos (picolés, sorvetes, garrafinhas).
- **Retiradas**: Registra as retiradas de produtos pelos vendedores.
- **Itens_de_Retirada**: Registra os detalhes dos itens retirados e devolvidos.

## Scripts SQL

Os scripts SQL estão organizados nos seguintes arquivos:
- `create_tables.sql`: Criação das tabelas.
- `insert_data.sql`: Inserção de dados iniciais.
- `views.sql`: Definição das views para cálculos.

## Views

O projeto inclui views para facilitar os cálculos das vendas diárias:
- `vw_CalculoVendas`: Calcula as vendas diárias de cada vendedor com base nas retiradas e devoluções de produtos.

## Como usar

1. **Criação do Banco de Dados**: Execute o script `create_tables.sql` para criar as tabelas no seu banco de dados SQL Server.
2. **Inserção de Dados**: Execute o script `insert_data.sql` para inserir os dados iniciais nas tabelas.
3. **Views**: Execute o script `views.sql` para criar as views necessárias.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou novas funcionalidades, sinta-se à vontade para criar um pull request.

## Licença

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Se precisar de mais alguma coisa ou tiver outras dúvidas, estou aqui para ajudar!
