# Projeto de BI | MRV: Panorama de Vendas e Empreendimentos

Este projeto foi desenvolvido em **Microsoft Power BI** e tem como objetivo facilitar a tomada de decisão a partir de dados de vendas imobiliárias e andamento de empreendimentos.  

O dashboard integra três bases principais (*vendas, empreendimentos e cidades*) e entrega uma visão clara e dinâmica com KPIs, tendências e alertas de inconsistências.  

Aviso: As bases utilizadas neste projeto são **fictícias** e foram fornecidas apenas para fins acadêmicos e de portfólio. Nenhum dado real ou confidencial foi utilizado.

---

## Estrutura do Repositório
- **bases/** → arquivos utilizados para o modelo (dados fictícios):  
  - `base_vendas.xlsx`  
  - `base_empreendimentos.xlsx`  
  - `base_cidades.xlsx`  
- **prints/** → capturas de tela do dashboard e da modelagem (relacionamentos, medidas e etapas do ETL no Power BI).  
- **dashboard.pbix** → arquivo principal do Power BI (relatório interativo).  

---

## Funcionalidades do Dashboard
### Página Inicial
- Apresentação e contextualização do projeto.  

### Análise de Vendas
- Evolução mensal de vendas por cidade e regional.  
- Ranking de cidades com maiores e menores volumes.  
- Histórico de vendas por ano e trimestre.  
- KPIs globais de vendas e % vendido.  

### Análise de Empreendimentos
- Total de empreendimentos (iniciados, em andamento e finalizados).  
- Distribuição por cidade, status da obra e faixa de atraso.  
- Tempo médio de atraso (com evolução histórica).  
- Classificação de empreendimentos por faixas de atraso.  

### Documentação
- Linha de raciocínio utilizada na modelagem.  
- Principais insights do dashboard.  
- Recomendações de negócio a partir dos indicadores.  

---

## Fontes de Dados
As análises foram construídas a partir de três bases em **Excel** (todas fictícias):  
1. **Base de Vendas** → identificador do empreendimento, data da venda e quantidade de unidades vendidas.  
2. **Base de Empreendimentos** → identificador do empreendimento, cidade, total de apartamentos e datas de obra (quando disponíveis).  
3. **Base de Cidades** → identificador, nome da cidade e regional associada.  

---

## Principais Insights do Dashboard
- Apenas 1,65% dos empreendimentos foram vendidos majoritariamente na planta, abaixo do ideal estratégico.  
- Tempo médio de atraso subiu de 36 dias (2021) para 180 dias em 2023 (+389%).  
- Atrasos concentrados principalmente nas faixas de 91 a 180 dias e acima de 180 dias.  
- Regiões críticas identificadas: Belo Horizonte, São Paulo e Campinas.  
- A maioria das vendas está concentrada em poucas cidades, limitando o crescimento orgânico.  

---

## Recomendações
- Realizar pré-venda mais agressiva antes do início da obra.  
- Reforçar o planejamento em regiões críticas com mais reincidência de atrasos.  
- Ajustar precificação e ritmo de obras com base no aproveitamento e tipologia.  
- Despriorizar empreendimentos de baixo desempenho, realocando recursos para os de maior retorno.  

---

## Como a Inteligência Artificial pode ajudar
- Previsão de risco de atraso por empreendimento.  
- Classificação de empreendimentos mais propensos ao sucesso na planta.  
- Geração de alertas proativos de risco de atraso.  
- Automatização de recomendações de alocação de equipe e investimentos com base em ROI histórico.  

---

## Exemplos do Dashboard
As capturas de tela estão disponíveis na pasta [`prints/`](prints/).  

---

## Licença
Livre para uso acadêmico e portfólio. 
