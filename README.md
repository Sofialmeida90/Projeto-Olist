# 🛍️ Projeto Final – Análise de E-commerce Brasileiro (Olist)

Este projeto foi desenvolvido como parte da UFCD 10804 – Projeto de Business Intelligence. Utilizando uma base de dados real da plataforma Olist (disponível no Kaggle), o objetivo foi criar um dashboard analítico no Power BI que oferecesse insights estratégicos sobre vendas, logística e comportamento do consumidor.

---

## 🎯 Objetivo do Projeto

Desenvolver um painel de Business Intelligence interativo que permita acompanhar o desempenho de vendas da Olist, identificar gargalos e oportunidades, e apoiar a tomada de decisão estratégica com base em dados reais de e-commerce.

---

## 🗂️ Etapas Realizadas

### 1. Planeamento do Projeto

Iniciei o trabalho com um planejamento estruturado, definindo objetivos, prazos, entregas e recursos necessários. Essa etapa foi essencial para guiar todas as fases do projeto com clareza e foco.

### 2. Elaboração do Documento de Projeto

Elaborei um documento técnico contendo:
- **Âmbito do Projeto**: definição dos limites e objetivos da análise;
- **Dicionário de Dados**: descrição dos campos, tabelas e relações no modelo de dados;
- **Protótipo Inicial**: criação de um wireframe de forma manual, antecipando o layout e os elementos visuais do painel no Power BI, para aceite da direção.

### 3. Modelagem e Análise de Dados

A análise prática começou com a importação dos arquivos CSV no Power BI. Modelei os dados com base em uma estrutura estrela, relacionando tabelas fato e dimensão. Em seguida, criei medidas DAX para compor os principais KPIs, incluindo:

- Receita Total
- Número de Pedidos
- Ticket Médio por Pedido
- Tempo Médio de Entrega
- Avaliação Média dos Clientes
- Receita por Categoria e Região

### 4. Criação do Dashboard e Design Visual

Construi o painel no Power BI focando na clareza e interatividade. Para enriquecer a apresentação, desenvolvi um fundo personalizado no **Figma**, integrando elementos visuais que reforçam a identidade da Olist e melhoram a experiência do usuário.

---

## 📈 Insights Obtidos

- Regiões e categorias com maior volume de vendas;
- Impacto do tempo de entrega na satisfação dos clientes;
- Análise de sazonalidade e evolução mensal das vendas;
- Comportamento de pagamento dos consumidores.

---

## 🛠️ Ferramentas Utilizadas

- Power BI Desktop  
- DAX  
- Excel  
- Figma  
- Kaggle  

🔗 [Base de dados – Kaggle: Olist Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Dashboard – Análise de Vendas da Olist

O Dashboard inicia com uma apresentação geral das vendas, nomeadamente, vendas por ano e mês, previsão de vendas nos próximos 3 anos, vendas por região, estado e cidade e vendas por categorias.
O dashboard está organizado com a segmentação de ano, mês, estado Brasil e Categoria de produto, caso seja necessário analisar algo mais detalhado em qualquer um dos dados.
<img src="Projeto BI com alteração - Olist - ANA ALMEIDA_page-0001.jpg" alt="Análise Geral" width="800">
</p>

A seguinte página mostra os indicadores mais relacionados com as encomendas, nomeadamente, tempos de entrega, número de encomendas em espaço temporal, entre outros.

<img src="Projeto BI com alteração - Olist - ANA ALMEIDA_page-0002.jpg" alt="Encomendas" width="800">
</p>

A seguinte página mostra os indicadores relacionados com pagamentos, nomeadamente o tipo de pagamento e a diferença entre os pagamentos e as vendas que a empresa teve. Também mostra a quantidade de clientes por região, assim como os vendedores por estado.

<img src="Projeto BI com alteração - Olist - ANA ALMEIDA_page-0003.jpg" alt="Pagamento/Clientes" width="800">
</p>

E por último temos uma página resumo que engloba as informações gerais das encomendas caso seja necessário fazer uma outra análise que não foi feita.

<img src="Projeto BI com alteração - Olist - ANA ALMEIDA_page-0004.jpg" alt="Report" width="800">
</p>
