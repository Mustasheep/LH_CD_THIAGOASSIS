# LightHouse Ciência de Dados

## Introdução

Desafio da Indicium para o programa LightHouse na trilha de Ciência de Dados.

O objetivo deste repositório, será desenvolver experimentos do dataset `desafio_indicium_imdb.csv`, para compreender sobre a sua estrutura, limpar, aplicar análise exploratória, técnicas de NLP, engenharia de features, preparar os dados para treinamento e criar/treinar um modelo de Machine Learning com `sckit-learn`.

A meta final é responder algumas perguntas do desafio e prever a nota IMDB do filme *The Shawshank Redemption*.

## Estrutura do Projeto

```
LightHouse-DataScience/
├── data/
│   └── desafio_indicium_imdb.csv       # Dataset do desafio
├── img/                                # Pasta com imagens para o README
│   └── diretoriocmd.png
├── models/
│   └── modelo_ridge.pkl                # Modelo de regressão com Ridge
├── notebooks/          
│   └── desafio_indicium.ipynb          # notebook com experimentos
├── .gitignore                          # impede upload de arquivos locais ao git
├── requirements.txt                    # documento para instalar as bibliotecas
└── README.md
```

## Instalação

Certifique-se de instalar essas ferramentas nas versões descritas ou superiores:

- **Python 3.12**
- **Git 2.51**
- **VSCode 1.103.2**
  - Extensões do VSCode:
    - Jupyter Notebook

### 1. Escolha um diretório

Crie uma nova pasta nomeada "Projeto LH" ou um nome de preferência. Ao acessar a pasta, na barra de endereços, digite `cmd`

### 2. Clonando e acessando 

Clone este repositório via terminal após abrir o cmd dos passos anteriores:

```bash
# Clone do repo
git clone https://github.com/Mustasheep/LH-CD-THIAGO-DE-ASSIS.git

# Acessando pasta
cd LH-CD-THIAGO-DE-ASSIS

# Abrir o projeto no VSCode
code .

```

### 3. Ambiente Virtual e bibliotecas

Ao abrir o VSCode com os passos anteriores, tecle `CTRL + J` para acessar o terminal pelo VSCode.

Em seguida, crie um ambiente virtual e instale as bibliotecas python através do `requirements.txt`:

```bash
# Criar o ambiente
python -m venv .venv

# Acessar o ambiente
.\.venv\Scripts\activate

# instalar os pacotes necessários
pip install -r requirements.txt
```

## Acessando o projeto

Finalizada a instalação, acesse o notebook em `notebooks/desafio_indicium.ipynb` e conecte o kernel `.venv` após iniciar a primeira célula do notebook. Após isso, iniciar as demais células para rodar todo o projeto.
