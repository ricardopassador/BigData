# BigData

### Datalake

Este projeto teve a intenção de demonstrar a criação de um DataLake, ferramenta muito utilizada na atualidade para o controle das informações.

O que é um DataLake?

Um repositório divido em camadas para o controle dos dados para a integração, armazenamento e analises.

O conceito é mais amplo que um Data Warehouse, pois aceita dados não estruturados e semi estruturados.

Este projeto foi desenvolvido "on premise" porém pode ser ampliado para Cloud, utilizando-se ferramentas como Nifi.


O projeto esta divido em 04 partes:
- Download de arquivos CSV diretamente para o /FileStore do Databricks
- Criação da camada RAW (1º camada)
- Criação da camada TRUSTED (2º camada)
- Criação da camada REFINE (3º camada)



