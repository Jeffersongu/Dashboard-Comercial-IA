# 🔄 Pipeline de Dados (ETL)
O pipeline do projeto segue as seguintes etapas:
- Ingestão: Coleta de dados estruturados a partir de arquivos CSV (vendas, equipe, metas e produtos) e XLSX (fotos dos vendedores);
- Transformação (ETL): Tratamento, limpeza e modelagem dos dados brutos utilizando o Power Query;
- Visualização: Consolidação das informações no Power BI para geração de dashboards e análise de indicadores.

<p align="center">
<img src="https://github.com/user-attachments/assets/8ae4c365-ad1e-4b20-99c4-437bd2ce740a" width="700" alt="image">
</p>


---
## 📂 Extração dos Dados - Power Query
### Etapa 1: Ingestão (Extração e Carregamento) ambas executadas pelo Power Query
- equipe csv;
- vendedores csv;
- foto_vendedores xlsx;
- vendas csv;
- metas csv.

---
## 🧹 Tratamento dos Dados - Power Query

### Etapa 1: Tabela dim_equipe, etapas aplicadas:
- Fonte com utilização de parâmetro de campo local;
- Cabeçalhos promovidos;
- Tipo alterado das colunas;
- Consultas Mescladas para retornar a coluna de imagem dos vendedores da tabela de fotos;
- Seleção da coluna específica de imagem dos vendedores.


### Etapa 2: Tabela dim_produtos, etapas aplicadas:
- Fonte com utilização de parâmetro de campo local;
- Cabeçalhos promovidos;
- Tipo alterado das colunas.


### Etapa 3: Tabela dim_foto_vendedor, etapas aplicadas:
- Fonte com utilização de parâmetro de campo local;
- Navegação;
- Cabeçalhos promovidos;
- Nova coluna id_vendedor a partir do texto entre os delimitadores;
- Tipo alterado das colunas.


### Etapa 4: Tabela fato_vendas, etapas aplicadas:
- Fonte com utilização de parâmetro de campo local;
- Cabeçalhos promovidos;
- Tipo alterado com localidade para a coluna de data_venda, formato de origem americano.


### Etapa 5: Tabela fato_metas, etapas aplicadas:
- Fonte com utilização de parâmetro de campo local;
- Cabeçalhos promovidos;
- Coluna Ano e Mês Mescladas;
- Substituindo caracter na coluna de valor_meta;
- Tipo alterado.
