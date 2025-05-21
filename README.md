# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# 🌾Validação do Modelo de IA com Dados Reais

## Nome do projeto
Fase 7 - Enterprise Challenge - Sprint 3 - Ingredion

## Nome do grupo
Grupo 34

## 👨‍🎓 Integrantes: 
- [Ana Beatriz Duarte Domingues](https://www.linkedin.com/in/)
- [Junior Rodrigues da Silva](https://www.linkedin.com/in/jrsilva051/)
- [Carlos Emilio Castillo Estrada](https://www.linkedin.com/in/)

## 👩‍🏫 Professores:
### Tutor(a)
- [Lucas Gomes Moreira](https://www.linkedin.com/company/inova-fusca)
### Coordenador(a)
- [André Godoi Chiovato](https://www.linkedin.com/company/inova-fusca)

---


## 📜 Descrição

Este repositório reúne a entrega da Sprint 3 do Challenge Ingredion, etapa final do projeto, focada na **validação do modelo de previsão de produtividade agrícola** desenvolvido anteriormente. O objetivo foi verificar se as previsões baseadas em **NDVI (Índice de Vegetação por Diferença Normalizada)** se correlacionam com **dados reais de produtividade agrícola** obtidos de fontes públicas.

* [Clique aqui para acessar o Relatório Técnico completo (PDF)](./assets/RelatorioTécnico_Sprint3.pdf)
* [Clique aqui para visualizar o notebook com as análises estatísticas](./Enterprise_Challenge_Sprint3_Ingredion.ipynb)


---

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto.

---

  
## 🔍 Metodologia
### Coleta de Dados
- NDVI: Obtido a partir do modelo preditivo treinado na Sprint 2.
- Produtividade Real: Dados históricos coletados de fontes públicas, especialmente do IBGE (Instituto Brasileiro de Geografia e Estatística).

### Tratamento dos Dados
- Junção dos datasets com base em município e ano-safra.
- Cálculo do NDVI médio por localidade.
- Correção de inconsistências e remoção de outliers.

---

## 📈 Análises Estatísticas Aplicadas
### Correlação
- Correlação de Pearson: para verificar relação linear entre NDVI e produtividade.
- Correlação de Spearman: para detectar relações monotônicas (não lineares).

### Regressão Linear
- Ajuste de uma regressão linear simples para modelar a produtividade real em função do NDVI médio.
- Cálculo do R² (coeficiente de determinação).

### Visualizações
- Gráficos de dispersão (scatter plots) com linha de tendência.
- Gráficos comparativos por região e por safra.

--- 


## 🧠 Principais Resultados
- Correlações positivas entre NDVI e produtividade.
- Modelo com bom desempenho, apesar de influências externas.
- Tendência visível nas visualizações por safra e região.

---

## 🗃 Histórico de lançamentos

* 0.1.0 - 19/05/2025
    *

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


