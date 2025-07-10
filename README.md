# 📊 Análise de Segurança Pública no Brasil (2018–2022)

Projeto desenvolvido para a disciplina **Banco de Dados II** na **PUCRS**, com o objetivo de aplicar conceitos de modelagem dimensional e análise de dados a partir de fontes públicas sobre criminalidade no Brasil.

---

## 👩‍🏫 Informações Acadêmicas

- **Disciplina**: Banco de Dados II  
- **Professora**: Denise Bandeira  
- **Aluna**: Emile Vargas Bordin  
- **Turma**: 30  

---

## 🎯 Objetivo

Compreender padrões e tendências dos crimes registrados nas diferentes regiões do Brasil entre 2018 e 2022. A análise visa apoiar políticas públicas, ações preventivas e o planejamento estratégico da segurança pública.

---

## ❓ Questões de Negócio Respondidas

1. Quais os meses com mais crimes cometidos no Rio Grande do Sul em 2022?
2. Houve aumento no roubo de veículos de 2018 a 2022?
3. Qual estado teve mais homicídios dolosos em 2022?
4. Qual estado teve o menor índice de homicídios dolosos em 2022? Quantos?
5. Quais foram os três tipos de crime mais registrados no Brasil em 2022?
6. Qual foi o total de ocorrências de crimes no estado de São Paulo em 2021?
7. Como variou o número de ocorrências de estupro no Brasil entre 2018 e 2022?

---

## 📂 Fonte dos Dados

- **Origem**: [SINESP - Ministério da Justiça e Segurança Pública](https://dados.gov.br/dados/conjuntos-dados/sistema-nacional-de-estatisticas-de-seguranca-publica)
- **Bases utilizadas**:
  - Ocorrências (crimes por UF, ano e mês)
  - Vítimas (vítimas por UF, ano e mês)

---

## 🛠️ Limpeza e Preparação dos Dados

- Remoção de valores nulos em colunas essenciais (`UF`, `Tipo Crime`, `Ano`, `Mês`, `Ocorrências`)
- Eliminação de registros duplicados
- Padronização dos dados (formatação dos campos, nomes de estados e tipos de crime)

---

## 🧱 Modelagem Multidimensional

- **Fato**: Ocorrências Criminais
- **Dimensões**: Tempo (Ano, Mês), Localidade (UF), Tipo de Crime

---

## 📈 Visualização dos Dados

A versão com dashboards interativos no **Power BI** está disponível neste repositório:

🔗 [projeto-powerbi-crimes-brasil](https://github.com/emivargxs/projeto-powerbi-crimes-brasil)

---

## 🧾 Licença

Projeto acadêmico sem fins lucrativos. Dados utilizados de fonte pública.
