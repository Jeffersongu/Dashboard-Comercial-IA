# 🤖 Dashboard Comercial - IA
<!-- Adicionando Gifs: -->
<img width="1437" height="803" alt="image" src="https://github.com/user-attachments/assets/32b5e6e6-36b7-4ac6-881a-4c4c7690f20e" />





---
## 🧩 Problema de Negócio
- Iago é proprietário da TechFlow Store, uma loja especializada na venda de produtos de informática, que vem ampliando seu volume de vendas e variedade de itens. Com o crescimento da operação, a empresa passou a gerar dados em diferentes sistemas e planilhas, dificultando a consolidação das informações e a obtenção de uma visão clara do desempenho do negócio.


---
## 🔍 Contexto
 - O propretário precisa acompanhar o desempenho dos vendedores e comparar o faturamento vs meta.
 - Você como analista de dados propõem um dashboard em Power BI para entregar visão em tempo real em apenas 3 dias.
 - O único problema é que você tem pouco tempo de empresa e não podem acessar os dados reais.

---
## 🎯 Objetivos do Projeto
- Reduzir o tempo para consolidar os dados;
- Ter a visão mais rápida possível para tomada de decisão no tempo certo;
- Identificar padrões para melhorar o planejamento.

---
## 🗂️ Dataset
- Tabela Dimensão Equipe com formato csv;
- Tabela Dimensão Produto com formato csv;
- Tabela Dimensão Fotos Vendedores com formato xlsx;
- Tabela Fato Metas com formato csv;
- Tabela Fato Vendas com formato csv.


---
## 🛠️ Tecnologias Utilizadas
-  ChatGPT → Prompts para base fictícia, análise dos dados, protótipo e apresentação;
-  Lovable → Protótipo de dashboard;
-  Gamma → Apresentação do projeto;
-  GitHub → Versionamento;
-  Figma → Designer;
-  Power BI → Dataviz.

---
## 🧱 Modelagem de Dados
A modelagem foi construída visando performance e clareza analítica, utilizando:
- Modelo estrela;
- Tabelas fato e dimensões;
- Relacionamentos otimizados para análise no Power BI.

 
---
 ## 📍 Premissas da Análise
Para a condução desta análise, foram estabelecidas algumas premissas com o objetivo de garantir consistência, confiabilidade e alinhamento com o contexto do negócio. 
- Primeira versão com dados fictícios desenvolvidos por IA;
- A estrutura será auxiliada por IA;
- Período de análise de 2025 a janeiro de 2026;
- Proposta feita em três dias para apresentação e validação.

---
## 🔄 Pipeline de Dados (ETL)
O pipeline do projeto segue as seguintes etapas:
- Ingestão: Coleta de dados estruturados a partir de arquivos CSV (vendas, equipe, metas e produtos) e XLSX (fotos dos vendedores);
- Transformação (ETL): Tratamento, limpeza e modelagem dos dados brutos utilizando o Power Query;
- Visualização: Consolidação das informações no Power BI para geração de dashboards e análise de indicadores.


<p align="center">
<img src="https://github.com/user-attachments/assets/8ae4c365-ad1e-4b20-99c4-437bd2ce740a" width="700" alt="image">
</p>


---
 ## 💡 Estratégia da Solução
O método selecionado para implementar a solução baseia-se em um ciclo de vida estruturado em etapas sequenciais e controladas.

**A Inteligência Artificial** será aplicada de forma integrada ao longo de todo o ciclo do projeto. Ela será utilizada para criar uma base de dados fictícia realista que permita a modelagem inicial e o alinhamento das expectativas. Em seguida, apoiará a análise exploratória, identificando padrões e propondo visualizações relevantes, o que viabilizará a construção ágil de um dashboard protótipo como prova de conceito visual. Por fim, a IA contribuirá na síntese e na apresentação final, destacando insights-chave e ajudando a estruturar uma narrativa clara e persuasiva para comunicar os resultados obtidos.

O plano contempla as fases de Análise, para entendimento do contexto e definição de métricas; ETL, para ingestão e transformação dos dados; Modelagem, para estruturação analítica; Design, para construção das visualizações e consumo; e Governança de Dados, para assegurar padronização, versionamento e confiabilidade das informações.


 ### Etapa 1: Análise de Projeto
 Nesta etapa, o foco é compreender profundamente o negócio do cliente. Isso envolve pesquisas, entrevistas e análises de documentos. O objetivo é identificar os desafios e necessidades do cliente, criando uma base sólida para as tarefas subsequentes.

 Etapa completa: [Análise de Projeto](https://github.com/Jeffersongu/Dashboard-Comercial-IA/tree/main/An%C3%A1lise%20de%20Projeto)

<p align="center">
<img src="https://github.com/user-attachments/assets/4ec35d2d-b6fc-4a4d-9c62-1672a4c20d36" width="800" alt="image">
</p>



 ### Etapa 2: ETL
 Durante a fase ETL (Extração, Transformação e Carga), nosso foco é assegurar que os dados estejam prontos para análises relevantes. Na etapa de Extração, coletamos dados de diversas fontes; na Transformação, realizamos limpeza e adaptação; e na Carga, disponibilizamos os dados em formato propício para análises.

Etapa completa: [ETL](https://github.com/Jeffersongu/Dashboard-Comercial-IA/tree/main/ETL)

<p align="center">
<img src="https://github.com/user-attachments/assets/6d719167-8bcb-4266-b3d4-7299acb5cbac" width="450" alt="image">
</p>




 ### Etapa 3: Modelagem
A Modelagem dos Dados representa a espinha dorsal do sistema, estabelecendo relacionamentos sólidos entre as tabelas e definindo a estrutura que suportará a análise de dados. Nessa fase, o foco está na criação de um modelo coeso e eficiente que atenda às necessidades específicas do negócio.

Etapa completa: [Modelagem](https://github.com/Jeffersongu/Dashboard-Comercial-IA/tree/main/Modelagem)

<p align="center">
<img src="https://github.com/user-attachments/assets/244d39b0-296d-4674-aece-a5df73778e82" width="500" alt="image">
</p>



### Etapa 4: Designer do Projeto
 A fase de Design é fundamental para moldar a arquitetura e a estética da solução. Durante essa etapa, é crucial definir a estrutura da interface, os componentes visuais e a lógica de interação para proporcionar uma experiência eficiente aos usuários finais. Essas decisões têm um impacto significativo na usabilidade e na eficácia da solução, influenciando diretamente a qualidade da experiência do usuário final e a efetividade do projeto de BI como um todo.

Etapa completa: [Designer do Projeto](https://github.com/Jeffersongu/Dashboard-Comercial-IA/tree/main/Designer)

<p align="center">
<img src="https://github.com/user-attachments/assets/587ed337-6a3a-4d51-94c1-e1874c1edfd4" width="460" alt="image">
</p>

### Etapa 5: Governança dos Dados
 A fase de Governança dos Dados é essencial para garantir a qualidade, integridade e segurança das informações manipuladas no projeto de BI. Nesse contexto, estabelecer políticas, normas e processos claros para a gestão dos dados é fundamental. A governança visa assegurar a confiabilidade das fontes de dados, promover a conformidade com regulamentações e padrões, além de definir papéis e responsabilidades na administração dos ativos de informação. Ao adotar práticas robustas de governança, a organização potencializa a tomada de decisões baseada em dados confiáveis e mitigação de riscos, contribuindo para o sucesso contínuo do projeto de BI.

Etapa completa: [Governança dos Dados](https://github.com/Jeffersongu/Dashboard-Comercial-IA/tree/main/Governan%C3%A7a%20dos%20Dados)

<p align="center">
<img src="https://github.com/user-attachments/assets/5ac82bc3-880f-4df2-99c0-ea3f53e5acba" width="500" alt="image">
</p>

---
 ## 5° Insights da Análise
 Não basta somente apresentar os dados ou visuais, é extremamente importante explicar com palavras o que o gráfico quer dizer, não acredite que os stakeholders entenderam os gráficos simplesmente observando, a parte técnica deve ser abstraída para que todos entendam. A análise dos dados permitiu identificar padrões relevantes como:


---
 ## 6° Resultados
 Conclusão das análises, depois que descrevemos os visuais e encontramos pontos de melhoria, qual é a conclusão geral, qual será a recomendação para solucionar o problema.
 Link para o relatório completo:


---
 ## 7° Próximos Passos
 O que faríamos com mais tempo para trabalhar neste projeto por exemplo:

-
