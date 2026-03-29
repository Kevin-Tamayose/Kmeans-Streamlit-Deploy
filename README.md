# Projeto de Clustering com Streamlit

Este projeto consiste em uma aplicação interativa que utiliza algoritmos de Machine Learning para a identificação de agrupamentos (clusters) em conjuntos de dados, com deploy em **Streamlit**.

## Pré-requisitos

Antes de começar, certifique-se de ter o **Python 3.8+** instalado em sua máquina.

## 1. Criação do Ambiente Virtual

É recomendável utilizar um ambiente virtual para isolar as dependências do projeto. No terminal, execute:

```bash
# Criar o ambiente virtual (venv)
python -m venv venv

# Ativar o ambiente virtual
# No Windows:
.\venv\Scripts\activate
# No Linux/MacOS:
source venv/bin/activate
```

## 2. Instalação de Dependências

Com o ambiente virtual ativo, instale todas as bibliotecas necessárias listadas no arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## 3. Estrutura do Arquivo `requirements.txt`

Certifique-se de que seu arquivo de texto contenha as seguintes bibliotecas básicas:

```text
streamlit
pandas
scikit-learn
matplotlib
seaborn
```

## 4. Como Executar a Aplicação

Para iniciar o servidor do Streamlit e visualizar o projeto no seu navegador, utilize o comando:

```bash
streamlit run app.py
```

## 5. Disponibilidade

O Modelo está rodando no servidor Streamlit na url: https://kmeans-app-deploygit-7baqxwhvsdcc4b38aucmm8.streamlit.app/