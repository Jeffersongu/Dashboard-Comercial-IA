# 🧊 Modelagem

A Modelagem dos Dados representa a espinha dorsal do sistema, estabelecendo relacionamentos sólidos entre as tabelas e definindo a estrutura que suportará a análise de dados. Nessa fase, o foco está na criação de um modelo coeso e eficiente que atenda às necessidades específicas do negócio.


---
## 📑-📑 Relacionamentos

Nesta etapa realizei a modelagem de dados do dashboard, organizando as tabelas no padrão fato e dimensão (star schema). Também configurei e validei os relacionamentos entre as tabelas para garantir cálculos corretos e consistência dos KPIs.

- Entendimento da regra de negócio e definição do nível de detalhamento (grão) das tabelas;
- Separação das tabelas em Fato (vendas e metas) e Dimensões (produto, equipe e calendário);
- Definição de chaves primárias e estrangeiras;
- Criação da tabela calendário via DAX;
- Organização dos relacionamentos no modelo (1:N);
- Validação dos relacionamentos com matriz/tabela;

<br/>

<p align="center">
<img src="https://github.com/user-attachments/assets/cab07be1-e532-4b24-8ae8-3db8443802b6" width="800" alt="image">
</p>


---
## 📖 Definição do StoryTelling

Nesta etapa estruturei o Storytelling do dashboard, organizando os dados em uma narrativa clara e estratégica, alinhada às necessidades e ao ponto de vista do cliente. O esboço foi validado seguindo o ponto de vista (PDV) do cliente, utilizando como referência o protótipo criado no Lovable. Também foram estruturadas as métricas, visuais e organização do relatório para garantir clareza, objetividade e foco em decisão:

- Esta página foi definida na etapa de análise do projeto para apresentar uma visão executiva do desempenho comercial, permitindo ao gestor entender rapidamente se a meta foi atingida, onde estão os principais desvios e quais ações devem ser priorizadas.
  - Primeira página (Visão Geral – Performance Comercial): contém KPI principal de Atingimento de Meta (Faturamento x Meta), além dos indicadores de Faturamento, Meta e Percentual de Atingimento. Visual de Faturamento vs Meta ao longo do tempo. Tabela de Performance por Vendedor com Quantidade de Vendas, Faturamento e % de Meta. Tabela de Análise de Produtos com Produto, Categoria, Quantidade Vendida, Faturamento e % de Participação. Bloco de Principais Insights estratégicos;
  - Filtros Globais: Período e Gerente para contextualização da análise em toda a página;
  - Distribuição Estratégica: KPI principal posicionado no canto superior esquerdo (foco executivo). Análise temporal logo abaixo para leitura de tendência. Performance por vendedor na base esquerda (visão tática). Análise detalhada de produtos no lado direito (visão analítica). Insights posicionados ao final para direcionamento de decisão.
- Validação do esboço (mockup) alinhado ao PDV do cliente;
- Desenvolvimento do dashboard;
- Criação e organização dos cálculos e medidas (KPIs);
- Padronização da nomenclatura das medidas;
- Ocultação de campos e medidas não utilizados pelo usuário final;
- Documentação das medidas com descrição, explicação e fórmula;
- Validação dos cálculos;
- Seleção e organização estratégica dos visuais.


<p align="center">
<img src="https://github.com/user-attachments/assets/e71e0b3e-4d17-475c-9c0d-450a0a9ea0e7" width="400" alt="image">
</p>

---
## 📋 Documentação 

Desenvolver prompt!
