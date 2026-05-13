# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href="https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP" border="0" width=40% height=40%></a>
</p>

<br>

# 🌱 IA aplicada ao Agronegócio — Recomendação de Culturas

## _(Nome do grupo)_

## 👨‍🎓 Integrantes

- <a href="#">Henrique Sanches Silva — RM 570527</a>
- <a href="#">João — RM _(preencher)_</a>
- <a href="#">Kayque — RM _(preencher)_</a>
- <a href="#">Luis — RM _(preencher)_</a>
- <a href="#">Patrick — RM _(preencher)_</a>

## 👩‍🏫 Professores

### Tutor(a)

- <a href="#">_(preencher)_</a>

### Coordenador(a)

- <a href="#">_(preencher)_</a>

---

## 📜 Descrição

Este repositório contém a **base inicial do notebook do grupo** para a atividade do Capítulo 10, organizada para facilitar a divisão das entregas entre os integrantes.

O projeto utiliza o dataset `produtos_agricolas.csv` (2.200 amostras, 22 culturas e 7 variáveis ambientais: N, P, K, temperatura, umidade, pH e chuva) para uma futura análise de dados e construção de modelos de classificação.

Nesta versão, o foco é disponibilizar a estrutura do trabalho com seções preparadas para:

- análise exploratória do dataset;
- análise descritiva com gráficos;
- definição do perfil ideal de solo e clima;
- treinamento de modelos preditivos;
- avaliação comparativa dos resultados.

O desenvolvimento completo dessas etapas será preenchido pelo grupo ao longo da atividade.

---

## 📁 Estrutura de pastas

```
.
├── assets/                       # Imagens (logo FIAP, gráficos exportados)
├── src/                          # Código-fonte principal
│   ├── HenriqueSanchesSilva_570527_fase3_cap2.ipynb   # Notebook do trabalho
│   └── Atividade_Cap10_produtos_agricolas.csv                          # Dataset
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
   jupyter notebook src/HenriqueSanchesSilva_570527_fase3_cap2.ipynb
   ```

4. Executar as células já disponíveis e usar a estrutura do notebook como base para o desenvolvimento das próximas etapas.

### Alternativa: Google Colab

1. Abrir o notebook no Colab.
2. Fazer upload do arquivo `produtos_agricolas.csv` no painel lateral.
3. Executar todas as células.

---

## 📺 Vídeo de apresentação

🎥 _(link do YouTube — não listado — a adicionar após gravação)_

---

## 🗃 Histórico de lançamentos

- 0.1.0 - 12/05/2026
  - Criação do notebook base com estrutura de seções
  - Estruturação do repositório seguindo template FIAP

- 0.1.1 - 13/05/2026
  - Ajuste do README para refletir o status atual de notebook base
  - Publicação da estrutura inicial para compartilhamento no GitHub

---

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
