# 📲 Análise de Comportamento do Usuário em Aplicativo de Alimentos

Este projeto analisa o comportamento dos usuários de um aplicativo de uma startup de produtos alimentícios. O foco está em entender o **funil de vendas** e avaliar os resultados de um **teste A/A/B** aplicado no design do app.

---

## 🎯 Objetivos do Projeto

### 1. Análise do Funil de Vendas
- Investigar como os usuários chegam até a etapa de compra.
- Descobrir quantos usuários avançam no funil e quantos desistem em cada etapa.
- Identificar gargalos e pontos de atrito na jornada do usuário.

### 2. Análise do Teste A/A/B
- Avaliar o impacto da mudança de fonte no design do app.
- Os usuários foram divididos em três grupos:
  - **Grupo A1 (ExpId: 246)**: fonte atual (controle).
  - **Grupo A2 (ExpId: 247)**: fonte atual (controle).
  - **Grupo B (ExpId: 248)**: nova fonte (grupo de teste).
- Verificar se há diferença significativa entre os grupos.
- Garantir confiabilidade estatística comparando os dois grupos de controle.

---

## 📁 Sobre os Dados

O conjunto de dados `logs_exp_us.csv` é um log de eventos, onde cada linha representa uma ação do usuário no app.

  - `EventName`: Nome do evento realizado pelo usuário
  - `DeviceIDHash`: Identificador único do usuário
  - `EventTimestamp`: Timestamp da ação
  - `ExpId`: Número do experimento: 246 e 247 (controle), 248 (teste com nova fonte) 

---

## 🧪 Metodologia
- Análise do funil de conversão com base na sequência de eventos.
- Comparação entre grupos usando testes estatísticos apropriados (ex: Mann-Whitney, chi-quadrado).
- Verificação de consistência entre os grupos de controle (A/A).
- Interpretação dos resultados para tomada de decisão sobre o design.

---

## 📌 Resultados Esperados
- Visualização clara do funil de conversão.
- Identificação de etapas críticas onde ocorre evasão de usuários.
- Conclusões sobre o impacto (ou não) da nova fonte na experiência do usuário.

---

## 🚀 Ferramentas Utilizadas
- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Visualizações gráficas para análise exploratória

