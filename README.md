# 👥 Projeto: Análise de Dados de RH (People Analytics) com Power BI

## 📋 Descrição do Projeto
Este projeto consiste no desenvolvimento de um dashboard interativo focado em Inteligência de Recursos Humanos (People Analytics). O objetivo principal é transformar dados cadastrais e comportamentais de colaboradores em insights visuais estratégicos, auxiliando os gestores no planeamento de equipas, retenção de talentos e análise salarial.

O projeto foi construído como o Mini-Projeto 3 durante a minha formação na **Data Science Academy (DSA)**.

---

## 🎯 Desafio de Negócio
A área de gestão de pessoas de uma organização necessitava de um mecanismo ágil para monitorizar e cruzar informações críticas da sua força de trabalho:
* Qual é a volumetria total de funcionários e o perfil de diversidade por género?
* Como estão distribuídos os colaboradores pelas funções técnicas e qual o tempo médio de experiência na empresa?
* Qual o salário médio global e qual a percentagem de profissionais disponíveis para a realização de horas extra?

O painel necessitava de controlos dinâmicos para permitir filtros profundos, como a segmentação por faixas etárias.

---

## 🛠️ Tecnologias e Ferramentas (Stack)
* **Power BI Desktop:** Construção do ambiente visual e organização dos componentes analíticos.
* **Power Query:** Carga, limpeza, renomeação de colunas e tipagem dos dados de RH.
* **Modelagem Star Schema / Relacional:** Organização das informações divididas em duas tabelas (tabela de dados `DatasetRH` e uma tabela exclusiva para armazenamento de `Medidas`), garantindo melhor performance e governança do projeto.
* **Linguagem DAX:** Criação de cálculos personalizados para métricas como a percentagem de colaboradores masculinos e femininos.

---

## ⚙️ Processo de Desenvolvimento (Ações Executadas)

### 1. Engenharia de Dados e Modelagem Avançada
* Importação e saneamento da base histórica de funcionários.
* **Abordagem Profissional de Modelagem:** Em vez de utilizar uma tabela única, os dados foram estruturados de forma relacional. Foi criada uma tabela isolada focada apenas em organizar as fórmulas e `Medidas` (como a `% Feminino`), mantendo o projeto limpo e escalável para auditorias.

### 2. Design de UX e Data Storytelling
* **Layout Clean (Light Mode):** Estruturação do painel utilizando blocos cinzentos de cantos arredondados sobre fundo claro, permitindo uma leitura corporativa leve e imediata.
* **Filtros Avançados:** Acoplamento de um segmentador dinâmico de idade no canto superior direito para filtragem em tempo real de gerações de profissionais.
* **Métricas em Destaque:** Uso de cartões grandes de KPI no topo para responder rapidamente às perguntas macro de negócio (Total de Funcionários, Média de Experiência e Salário Médio).

---

## 📈 Insights e Resultados Obtidos
* **Raio-X Demográfico:** O painel consolidou uma força de trabalho robusta composta por **1.400 funcionários**, composta por **59,86% de homens (838)** e **40,14% de mulheres (562)**.
* **Retenção de Conhecimento:** Foi verificada uma alta estabilidade e maturidade corporativa, com o registo de **11 anos de experiência média** entre os colaboradores.
* **Análise de Funções:** O gráfico de barras horizontais indicou claramente que o cargo de **Cientista de Dados** possui a maior concentração de profissionais na estrutura atual da empresa.
* **Mapeamento de Esforço:** Identificação visual através do gráfico de rosca de que **28,43%** dos funcionários mapeados possuem total disponibilidade para a realização de horas extra.
* **Equilíbrio de Custos:** Monitorização instantânea do salário médio global fixado em **6.927,51**.

---

## 📷 Visualização do Painel

Abaixo está o registo da tela principal de análise de RH:

![Análise de Dados de RH](https://raw.githubusercontent.com/rodrigoifs/analise-dados-rh-powerbi/refs/heads/main/imagens/analise-rh.png)
