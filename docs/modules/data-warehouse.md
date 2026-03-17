
# Data Warehouse

## Visão Geral

Esta documentação apresenta a arquitetura e estrutura do Data Warehouse (DW) utilizado no projeto.

## Diagrama da Arquitetura

![Data Warehouse Architecture](./APIDW.png)

## Componentes Principais

### Camada de Origem (Source)
- Arquivos CSV

### Camada de Integração (Integration)
- ETL (Extract, Transform, Load)
- Data cleaning e validação
- Staging area

### Camada de Armazenamento (Storage)
- Fact tables
- Dimension tables
- Data marts

### Camada de Apresentação (Presentation)
- Business Intelligence
- Relatórios analíticos
- Dashboards

## Fluxo de Dados

1. Extração de dados das fontes
2. Transformação e limpeza
3. Carregamento no repositório central
4. Publicação nos data marts
5. Consumo pelos usuários finais
