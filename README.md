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

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto.


## 📜 Descrição

Este repositório reúne a entrega da Sprint 3 do Challenge Ingredion, etapa final do projeto, focada na **validação do modelo de previsão de produtividade agrícola** desenvolvido anteriormente. O objetivo foi verificar se as previsões baseadas em **NDVI (Índice de Vegetação por Diferença Normalizada)** se correlacionam com **dados reais de produtividade agrícola** obtidos de fontes públicas.

  
## 🔍 Metodologia
### 🔸 Coleta de Dados
- NDVI: Obtido a partir do modelo preditivo treinado na Sprint 2.
- Produtividade Real: Dados históricos coletados de fontes públicas, especialmente do IBGE (Instituto Brasileiro de Geografia e Estatística).

### 🔸 Tratamento dos Dados
- Junção dos datasets com base em município e ano-safra.
- Cálculo do NDVI médio por localidade.
- Correção de inconsistências e remoção de outliers.

---

## 📈 Análises Estatísticas Aplicadas
### 🔸 Correlação
- Correlação de Pearson: para verificar relação linear entre NDVI e produtividade.
- Correlação de Spearman: para detectar relações monotônicas (não lineares).

### 🔸 Regressão Linear
- Ajuste de uma regressão linear simples para modelar a produtividade real em função do NDVI médio.
- Cálculo do R² (coeficiente de determinação).

### 🔸 Visualizações
- Gráficos de dispersão (scatter plots) com linha de tendência.
- Gráficos comparativos por região e por safra.

--- 


## 🧠 Principais Resultados
- Correlações moderadas a fortes entre NDVI e produtividade, dependendo da região analisada.
- O modelo mostrou bom desempenho, mas com variações explicadas por fatores externos como clima e qualidade das imagens NDVI.
- R² significativo, sugerindo que o NDVI pode ser um bom preditor em contextos controlados.

---

## 📌 Conclusões e Limitações
- O modelo de IA teve bom desempenho em prever produtividade a partir do NDVI.
- A análise estatística reforçou o uso de sensoriamento remoto como ferramenta de apoio à agricultura de precisão.
- Fatores como eventos climáticos, pragas e amostragem limitada ainda impactam a confiabilidade do modelo.

---

## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2024
    * 
* 0.4.0 - XX/XX/2024
    * 
* 0.3.0 - XX/XX/2024
    * 
* 0.2.0 - XX/XX/2024
    * 
* 0.1.0 - XX/XX/2024
    *

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


