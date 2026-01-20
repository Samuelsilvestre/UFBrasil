Data Analytics – Indicadores Educacionais e Sociais

## Visão geral
Este projeto analisa indicadores educacionais (IDEB) e sua relação com fatores socioeconômicos (PIB) e de segurança (Taxa MVI) no Brasil.

## Tecnologias usadas
* **Python**
* **Jupyter Notebook / Google Colab**
* **Pandas**
* **Matplotlib**
* **Seaborn**

---

## Análises e Visualizações

### 1. Distribuição dos Indicadores IDEB
![Quartis IDEB](image/Quartil_IDEB.png)
**Descrição:** Boxplot comparando a distribuição das notas. O desempenho decresce conforme as etapas avançam (Iniciais > Finais > Médio).

### 2. Desempenho Regional (IDEB)
![IDEB Anos Iniciais](image/IDEB_Regiao_Inicial.png)
![IDEB Anos Finais](image/IDEB_Regiao_Final.png)
![IDEB Ensino Médio](image/IDEB_Regiao_Ensino_Medio.png)
**Descrição:** Médias por região. Sul e Sudeste lideram os índices, enquanto Norte e Nordeste apresentam os maiores desafios.

### 3. Indicadores Socioeconômicos (PIB)
![Média PIB](image/Regiao_PIB.png)
![PIB Percapita](image/_Regiao_PIB_PERCAPITA.png)
**Descrição:** Disparidade econômica regional. O Sudeste possui o maior PIB total e o Centro-Oeste o maior PIB per capita.

### 4. Taxa de Mortes Violentas Intencionais (MVI)
![Taxa MVI](image/MVI_Medio_Regiao.png)
**Descrição:** O Nordeste e o Norte apresentam as taxas de violência mais elevadas do país em 2024.

### 5. Regressão Linear: Educação vs. Violência
![Regressão Iniciais](image/Regressao_Linear_IDEB_Inicial_MVI.png)
![Regressão Finais](image/Regressao_Linear_IDEB_Final_MVI.png)
![Regressão Médio](image/Regressao_Linear_Ensino_Medio_MVI.png)
**Descrição:** As linhas de tendência indicam que quanto maior o IDEB, menor tende a ser a taxa de violência (MVI) na região.

---

## Conclusões
Os dados demonstram que o desempenho educacional está fortemente atrelado ao contexto socioeconômico e regional.

---
Projeto para demonstração de competências em ciência de dados e estatística.
