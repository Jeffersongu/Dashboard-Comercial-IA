# 🤖 Dashboard-IA
<!-- Adicionando Gifs: -->




---
## 🧩 Problema de Negócio
- Iago é proprietário da TechFlow Store, uma loja especializada na venda de produtos de informática, que vem ampliando seu volume de vendas e variedade de itens. Com o crescimento da operação, a empresa passou a gerar dados em diferentes sistemas e planilhas, dificultando a consolidação das informações e a obtenção de uma visão clara do desempenho do negócio.


---
## 🔍 Contexto
 - O propretário precisa acompanhar o desempenho dos vendedores e comparar o faturamento ano vs ano.
 - Você como analista de dados propõem um dashboard em Power BI para entregar visão em tempo real em apenas 3 dias.
 - O único problema é que você tem pouco tempo de empresa e não podem acessar os dados reais.

---
## 📦 Discovery
Entendimento de Negócio com o cliente (reunião):
- Você tem alguma amostra dos dados para disponibilizar? Não, pois a política de Compliance da empresa não permite e a equipe de Tecnologia leva entorno de um mês para disponibilizar a base!
- Você pode disponibilizar pelo menos um print da informações do PDV, pois com isso podemos produzir um paínel com essas informações simuladas? Sim, consigo disponibilizar!

<p align="center">
<img src="https://github.com/user-attachments/assets/4a9124b6-55ec-4d64-9636-571747a142a1" width="800" alt="image">
</p>

- Qual o tipo de decisão você precisa tomar, que informações você precisa ter assim que chega na empresa? A principal informação que eu procuro é em relação a meta do mês!
- Como você obtém essa informação? Peço para assistente acessar o PDV, exporte os arquivos csv, ela me envia pelo whatsapp. Assim, inicio as análises para verificar se batemos ou não a meta!
- Essa rotina é realizada todos os dias? Não, pois essa análise leva uma ou duas horas para ser concretizada, e dependo do dia não é garatindo que seja feita!
- Que outras perguntas ou informações você precisa reponder no seu dia a dia? Como estou na estrutura de Finanças e Vendas, preciso saber qual vendedor esta performando, qual produto está vendendo mais e qual categoria esta perfomando melhor. Por fim, se existe algum padrão, pois tem mês que vendemos muito um determinado produto e dois meses depois parece que ninguém sabe que vendemos ele, entender esses padrões ajudaria muito.
- Você consegue responder essas perguntas de forma rápida? A primeira sim, saber se os vendedores estão performando e o KPI principais tenho uma planilha de controle pessoal, porém as outras duas perguntas tenho muito trabalho para conseguir chegar num caminho.
- Isso impacta quanto no resultado? Por exemplo, o CEO estava me cobrando o porquê o tablet não estava saindo, no entanto até o dia 20 estavamos vendendo diversos outros produtos e o tablet não estava saindo e eu não consegui enxergar, quando ele me avisou no dia 20 não tive tempo hábil para fazer uma estratégia seja ligar para os clientes ou fazer uma promoção, como ele me falou tarde demais e pela rotina eu não consegui ver antes.


---
## 🎯 Objetivos do Projeto
- Reduzir o tempo para consolidar os dados;
- Ter a visão mais rápida possível para tomada de decisão no tempo certo;
- Identificar padrões para melhorar o planejamento.

---
## 🗂️ Dataset
- Tabela Dimensão Equipe com formato csv;
- Tabela Dimensão Produto com formato csv;
- Tabela Fato Metas com formato csv;
- Tabela Fato Vendas com formato csv.


---
## 🛠️ Tecnologias Utilizadas
-  Notion;
-  ChatGPT;
-  Lovable
-  GitHub;
-  Figma;
-  Power BI.

---
## 🧱 Modelagem de Dados
A modelagem foi construída visando performance e clareza analítica, utilizando:

- Modelo estrela;
- Tabelas fato e dimensões;
- Relacionamentos otimizados para análise no Power BI

---
## 📝 Modelo de Requisitos
O Modelo de Requisitos foi adotado para garantir alinhamento claro entre o problema de negócio, os objetivos analíticos e as entregas finais do projeto.

<p align="center">
<img src="https://github.com/user-attachments/assets/f384cbe7-20c4-454c-a949-4698d7688b99" width="800" alt="image">
</p>


---
## 📅 Definição do Cronograma do Projeto
 O cronograma do projeto será desenvolvido em cinco etapas: Análise, ETL, Modelagem, Designer e Governança dos Dados.

<p align="center">
  <img src="https://github.com/user-attachments/assets/9cccf3b5-b26e-42c2-889a-bb2ac1fd8964" width="700" alt="image">
</p>

 
---
 ## 📍 Premissas da Análise
Para a condução desta análise, foram estabelecidas algumas premissas com o objetivo de garantir consistência, confiabilidade e alinhamento com o contexto do negócio. 
- Construir um dashboard de performance de vendas, com um paínel rápido com meta de faturamento, performance do time, melhores produtos com visuais interativos.
- Prmeira versão com dados fictícios desenvolvidos por IA;
- Toda a estrutura será realizada por IA e Power BI;
- Período de análise de 2025 a janeiro de 2026;
- Proposta feita em três dias para apresentação e validação.

---
## 🔄 Pipeline de Dados (ETL)
O pipeline do projeto segue as seguintes etapas:

- 



---
 ## 💡 Estratégia da Solução
A estratégia da solução foi estruturada com base em um Modelo de Requisitos, garantindo alinhamento entre o problema de negócio, os objetivos analíticos e as entregas finais do projeto.

A execução foi organizada em etapas sequenciais e controladas, permitindo rastreabilidade, qualidade e evolução contínua da solução de dados.

O plano contempla as fases de Análise, para entendimento do contexto e definição de métricas; ETL, para ingestão e transformação dos dados; Modelagem, para estruturação analítica; Design, para construção das visualizações e consumo; e Governança de Dados, para assegurar padronização, versionamento e confiabilidade das informações.

 ### Etapa 1: Análise de Projeto
 Nesta etapa, o foco é compreender profundamente o negócio do cliente. Isso envolve pesquisas, entrevistas e análises de documentos. O objetivo é identificar os desafios e necessidades do cliente, criando uma base sólida para as tarefas subsequentes.

 Etapa completa:


 ### Etapa 2: ETL
 Durante a fase ETL (Extração, Transformação e Carga), nosso foco é assegurar que os dados estejam prontos para análises relevantes. Na etapa de Extração, coletamos dados de diversas fontes; na Transformação, realizamos limpeza e adaptação; e na Carga, disponibilizamos os dados em formato propício para análises.

Etapa completa:


 ### Etapa 3: Modelagem
A Modelagem dos Dados representa a espinha dorsal do sistema, estabelecendo relacionamentos sólidos entre as tabelas e definindo a estrutura que suportará a análise de dados. Nessa fase, o foco está na criação de um modelo coeso e eficiente que atenda às necessidades específicas do negócio.

Etapa completa:

### Etapa 4: Designer do Projeto
 A fase de Design é fundamental para moldar a arquitetura e a estética da solução. Durante essa etapa, é crucial definir a estrutura da interface, os componentes visuais e a lógica de interação para proporcionar uma experiência eficiente aos usuários finais. Essas decisões têm um impacto significativo na usabilidade e na eficácia da solução, influenciando diretamente a qualidade da experiência do usuário final e a efetividade do projeto de BI como um todo.

Etapa completa:

### Etapa 5: Monitoramento
 A fase de Governança dos Dados é essencial para garantir a qualidade, integridade e segurança das informações manipuladas no projeto de BI. Nesse contexto, estabelecer políticas, normas e processos claros para a gestão dos dados é fundamental. A governança visa assegurar a confiabilidade das fontes de dados, promover a conformidade com regulamentações e padrões, além de definir papéis e responsabilidades na administração dos ativos de informação. Ao adotar práticas robustas de governança, a organização potencializa a tomada de decisões baseada em dados confiáveis e mitigação de riscos, contribuindo para o sucesso contínuo do projeto de BI.

Etapa completa:


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
