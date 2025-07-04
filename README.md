# Análise de Crimes Cibernéticos (IC3 - FBI 2024)

Este repositório contém o MVP da disciplina **Análise Exploratória e Pré-Processamento de Dados**, com foco em crimes cibernéticos reportados ao FBI (IC3) em 2024.

## 🎯 Objetivo

Explorar padrões nos crimes cibernéticos com base em:

- Faixa etária das vítimas
- Tipo de crime mais comum
- Frequência de registros

Os dados foram obtidos do relatório público anual do Internet Crime Complaint Center (IC3), publicado pelo FBI.

## 📊 Dataset

Arquivo: `ic3_2024_crimetypes_age.csv`

O dataset contém a distribuição de crimes cibernéticos por tipo e faixa etária.

Colunas:
- `Crime Type`: tipo de crime (ex: phishing, extorsão, fraude com criptomoeda)
- `Under 20`, `20-29`, ..., `50-59`: número de casos reportados em cada faixa etária

Fonte original: [FBI IC3 2024 Report (PDF)](https://www.ic3.gov/Media/PDF/AnnualReport/2024_IC3Report.pdf)

## 🔍 Etapas realizadas

- Leitura do dataset via URL GitHub
- Tratamento e conversão de dados para formato numérico
- Estatísticas descritivas
- Visualizações com `seaborn` e `matplotlib`
- Análise por faixa etária
- Análise por tipo de crime
- Conclusão e hipóteses levantadas

## 📁 Como executar

Você pode visualizar e executar o notebook diretamente no [Google Colab](https://colab.research.google.com/):

[📎 Acesse o notebook aqui](https://colab.research.google.com/drive/1_ZyEbuZt4sx0AMzzdmorAAjHzmPvgD3b)

---

## ✅ Checklist do MVP

- [x] Definição do problema
- [x] Leitura do dataset e estruturação
- [x] Estatísticas descritivas
- [x] Visualizações com análise textual
- [x] Pré-processamento básico
- [x] Conclusão do projeto

---

## ✍️ Autor

**Bruno Braat**  
Aluno da PUC - Ciência de Dados
