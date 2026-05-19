# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP" border="0" width=40% height=40%></a>
</p>

<br>

# 🌱 IA aplicada ao Agronegócio — Recomendação de Culturas

## _(Nome do grupo — preencher)_

## 👨‍🎓 Integrantes

- <a href="https://github.com/HenriqueSanchesSilva">Henrique Sanches Silva — RM 570527</a>
- <a href="https://github.com/zjpza">João Pedro Zavanela Andreu — RM 570231</a>
- <a href="https://github.com/Kayckxz">Kayck Gabriel Evangelista da Silva — RM 572331</a>
- <a href="https://github.com/lhboschi">Luis Henrique Laurentino Boschi — RM 571352</a>
- <a href="https://github.com/Trickmelo">Patrick Borges de Melo — RM 574030</a>

## 👩‍🏫 Professores

### Tutor(a)

- <a href="#">_(preencher)_</a>

### Coordenador(a)

- <a href="#">_(preencher)_</a>

---

## 📜 Descrição

Este repositório contém a entrega da atividade do **Capítulo 10 — A primeira técnica de aprendizado de máquina** da Fase 3 do curso TIAOA da FIAP, no contexto da startup fictícia **FarmTech Solutions**.

O projeto utiliza o dataset `Atividade_Cap10_produtos_agricolas.csv` (2.200 amostras, 22 culturas e 7 variáveis ambientais: N, P, K, temperatura, umidade, pH e chuva) para construir um sistema de **recomendação de culturas agrícolas** com base em condições de solo e clima.

O notebook entregue cobre as seguintes etapas:

- **Análise exploratória** do dataset (dimensões, tipos, nulos, duplicados, estatísticas descritivas);
- **Análise descritiva** com cinco conjuntos de visualizações (distribuição das classes, histogramas, boxplots, matriz de correlação e perfil comparativo entre culturas);
- **Definição do perfil ideal de solo e clima**, com comparação detalhada entre três culturas escolhidas (`coffee`, `cotton` e `rice`) e a média geral do dataset;
- **Treinamento de cinco modelos preditivos** (Regressão Logística, KNN, Decision Tree, Random Forest e SVM com três kernels);
- **Avaliação comparativa** dos modelos com acurácia, precisão, recall e F1-score ponderado, matriz de confusão multiclasse e importância das features;
- **Conclusões** com pontos fortes, limitações e sugestões de evolução.

### 🏆 Principais resultados

| Modelo              | Acurácia | F1-score |
| ------------------- | -------- | -------- |
| Random Forest       | 0,9955   | 0,9955   |
| SVM (RBF)           | 0,9864   | 0,9863   |
| Decision Tree       | 0,9795   | 0,9794   |
| KNN                 | 0,9795   | 0,9794   |
| Regressão Logística | 0,9409   | 0,9404   |

O **Random Forest** apresentou o melhor desempenho, e as variáveis mais discriminantes foram `rainfall` e `humidity`, seguidas por `K` e `P`.

---

## 📁 Estrutura de pastas

```
.
├── assets/                       # Imagens (logo FIAP, gráficos exportados)
├── src/                          # Código-fonte principal
│   ├── HenriqueSanchesSilva_RM570527_fase3_cap10.ipynb   # Notebook do trabalho
│   └── Atividade_Cap10_produtos_agricolas.csv            # Dataset
├── .gitignore
├── README.md                     # Este arquivo
└── requirements.txt              # Dependências Python
```

---

## 🔧 Como executar o código

### Pré-requisitos

- Python 3.10 ou superior
- Jupyter Notebook ou JupyterLab (ou abrir o `.ipynb` no Google Colab / VS Code)

### Instalação

1. Clonar o repositório:

   ```bash
   git clone https://github.com/HenriqueSanchesSilva/farm-tech-fase3-cap-10.git
   cd farm-tech-fase3-cap-10
   ```

2. Instalar as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Abrir o notebook:

   ```bash
   jupyter notebook src/HenriqueSanchesSilva_RM570527_fase3_cap10.ipynb
   ```

4. Executar todas as células do notebook (`Kernel → Restart & Run All`).

### Alternativa: Google Colab

1. Abrir o notebook no Colab.
2. Fazer upload do arquivo `Atividade_Cap10_produtos_agricolas.csv` no painel lateral.
3. Executar todas as células.

---

## 📺 Vídeo de apresentação

🎥 _(link do YouTube — a adicionar após gravação)_

---

## 🗃 Histórico de lançamentos

- **1.0.0 — 18/05/2026**
  - Versão final entregue
  - Notebook completo com análise exploratória, descritiva, perfil de culturas e cinco modelos preditivos
  - Conclusões com pontos fortes e limitações
  - README atualizado com integrantes, resultados e instruções de execução

- 0.1.1 — 13/05/2026
  - Ajuste do README para refletir o status atual de notebook base
  - Publicação da estrutura inicial para compartilhamento no GitHub

- 0.1.0 — 12/05/2026
  - Criação do notebook base com estrutura de seções
  - Estruturação do repositório seguindo template FIAP

---

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
