# FabricaPicolés-DB

Este é um projeto pessoal desenvolvido para gerenciar o banco de dados de uma fábrica de picolés pertencente à nossa família. Utilizamos SQL Server para organizar e controlar as retiradas e devoluções de produtos pelos vendedores, bem como para calcular as vendas diárias.

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

Como este é um projeto familiar, sinta-se à vontade para contribuir com sugestões de melhorias ou novas funcionalidades. Crie um pull request se quiser adicionar algo ao projeto.

## Licença

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Se precisar de mais alguma coisa ou tiver outras dúvidas, estamos à disposição!
