# FIAP - Faculdade de Informatica e Administracao Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP" border="0" width=40% height=40%></a>
</p>

<br>

# IA aplicada ao Agronegocio — Recomendacao de Culturas

## _(Nome do grupo)_

## Integrantes

- Henrique Sanches Silva — RM 570527
- Luis Henrique Laurentino Boschi — RM 571352
- Kayck Gabriel Evangelista da Silva — RM 572331
- Patrick Borges de Melo — RM 574030
- Joao Pedro Zavanela Andreu — RM 570231

## Professores

### Tutor(a)

- Sabrina Otoni

### Coordenador(a)

- Andre Godoi

---

## Descricao

Este repositorio contem a entrega completa da atividade do Capitulo 10 (Fase 3) do grupo. O projeto utiliza o dataset `produtos_agricolas.csv` (2.200 amostras, 22 culturas e 7 variaveis ambientais: N, P, K, temperatura, umidade, pH e chuva) para analise de dados e construcao de modelos de classificacao supervisionada.

O notebook contempla as seguintes etapas entregues:

- **Analise exploratoria** do dataset: verificacao de dimensoes, tipos, nulos, duplicados e estatisticas descritivas;
- **Analise descritiva com graficos**: distribuicao das classes, histogramas das variaveis, boxplots, matriz de correlacao e perfil medio das culturas;
- **Perfil ideal de solo/clima**: comparacao estatistica e visual entre tres culturas escolhidas (`coffee`, `cotton` e `rice`) e a media geral do dataset;
- **5 modelos preditivos**: Regressao Logistica, KNN, Decision Tree, Random Forest e SVM (com selecao do melhor kernel), treinados seguindo boas praticas de Machine Learning (separacao treino/teste, escalonamento, encoding e metricas de avaliacao);
- **Avaliacao comparativa**: tabela e grafico de barras com acuracia, precisao, recall e F1-score dos modelos, alem de matriz de confusao e classification report do modelo vencedor (Random Forest);
- **Conclusoes**: pontos fortes, limitacoes e interpretacao dos resultados.

O dataset e balanceado (100 amostras por cultura), o que reduz o risco de vies forte nas metricas de classificacao.

---

## Estrutura de pastas

```
.
├── assets/                          # Imagens (logo FIAP, graficos exportados)
├── src/                             # Codigo-fonte principal
│   ├── HenriqueSanchesSilva_570527_fase3_cap2.ipynb   # Notebook completo da atividade
│   └── Atividade_Cap10_produtos_agricolas.csv         # Dataset
├── .gitignore
├── README.md                        # Este arquivo
└── requirements.txt                 # Dependencias Python
```

---

## Como executar o codigo

### Pre-requisitos

- Python 3.10 ou superior
- Jupyter Notebook, JupyterLab, VS Code ou Google Colab

### Instalacao local

1. Clonar o repositorio:

   ```bash
   git clone https://github.com/HenriqueSanchesSilva/farm-tech-fase3-cap-10.git
   cd farm-tech-fase3-cap-10
   ```

2. Instalar as dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Abrir o notebook:

   ```bash
   jupyter notebook src/HenriqueSanchesSilva_570527_fase3_cap2.ipynb
   ```

4. Executar todas as celulas em ordem.

### Alternativa: Google Colab

1. Fazer upload do arquivo `.ipynb` no Google Colab.
2. Fazer upload do arquivo `Atividade_Cap10_produtos_agricolas.csv` no painel lateral (arquivos).
3. Ajustar o path de leitura do CSV conforme a localizacao no ambiente Colab.
4. Executar todas as celulas.

---

## Video de apresentacao

_(link do YouTube — nao listado — a adicionar apos gravacao)_

---

## Historico de lancamentos

- 0.1.0 - 12/05/2026
  - Criacao do notebook base com estrutura de secoes
  - Estruturacao do repositorio seguindo template FIAP

- 0.1.1 - 13/05/2026
  - Ajuste do README para refletir o status atual de notebook base
  - Publicacao da estrutura inicial para compartilhamento no GitHub

- 1.0.0 - 17/05/2026
  - Entrega completa da atividade do Capitulo 10
  - Analise exploratoria, descritiva com 5+ graficos, perfil ideal de 3 culturas
  - Treinamento e comparacao de 5 modelos preditivos
  - Conclusoes, pontos fortes e limitacoes documentados

---

## Licenca

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> esta licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
