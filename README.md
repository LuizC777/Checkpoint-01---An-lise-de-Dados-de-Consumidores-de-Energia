# Checkpoint01   Anlise de Dados de Consumidores de Energia
# Projeto - Checkpoint 1 SERS

Este repositório contém um **notebook Jupyter (`.ipynb`)** com o código do projeto, um **arquivo de texto (`.txt`)** e um **arquivo de texto (`.csv`)** com os bancos de dados necessários para a execução.

O objetivo é permitir que qualquer pessoa possa abrir e rodar o projeto diretamente no **Google Colab**.

---

## Estrutura do Repositório

├── Checkpoint_1_SERS_sem2.ipynb # Notebook com o código do projeto

├── cp1_SERS_sem2_parte4.ows # Arquivo do orange com exercícios

├── household_power_consumption.txt # Arquivo de banco de dados 

├── energydata_complete.csv # Arquivo de banco de dados 

├── README.md # Instruções de uso

---

## Como Executar no Google Colab

1. Acesse o [Google Colab]([https://colab.research.google.com/](https://colab.research.google.com/drive/1eQmZXiZVf5D7SY6HiWoEbyXIGkp3dakV?usp=sharing)).

2. Faça o upload dos arquivos do repositório:
   - `household_power_consumption.txt`
   - `energydata_complete.csv`

Caso o notebook espere o caminho do banco de dados, ajuste para o local correto.
Exemplo (se o arquivo está no mesmo diretório do notebook)
Execute todas as células do notebook para rodar o projeto.

Observações
Certifique-se de que o arquivo household_power_consumption.txt e energydata_complete.csv estão no mesmo diretório do notebook ou ajuste o caminho no código.

## Como Executar no Orange 3

1. Instale o [Orange 3](https://orangedatamining.com/download/) em seu computador.

2. Abra o Orange 3 e carregue o arquivo do fluxo de trabalho:
   - `cp1_SERS_sem2_parte4.ows`

3. Certifique-se de que o arquivo de dados utilizado no fluxo (`energydata_complete.csv`) está acessível no mesmo diretório ou ajuste os caminhos nos widgets correspondentes.

4. Execute o fluxo clicando no botão **Play** (▶) no canto superior da interface do Orange.
