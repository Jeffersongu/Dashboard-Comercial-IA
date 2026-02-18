# 🔄 Pipeline de Dados (ETL)
Durante a fase ETL (Extração, Transformação e Carga), nosso foco é assegurar que os dados estejam prontos para análises relevantes. Na etapa de Extração, coletamos dados de diversas fontes; na Transformação, realizamos 
limpeza e adaptação; e na Carga, disponibilizamos os dados em formato propício para análises.


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
