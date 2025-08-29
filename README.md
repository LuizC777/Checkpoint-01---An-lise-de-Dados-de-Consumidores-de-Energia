# Checkpoint01   Anlise de Dados de Consumidores de Energia
# Projeto - Checkpoint 1 SERS

Este repositório contém um **notebook Jupyter (`.ipynb`)** com o código do projeto e um **arquivo de texto (`.txt`)** com o banco de dados necessário para a execução.

O objetivo é permitir que qualquer pessoa possa abrir e rodar o projeto diretamente no **Google Colab**.

---

## 📂 Estrutura do Repositório

├── Checkpoint1_SERS_sem2_(1).ipynb # Notebook com o código do projeto
├── banco_dados.txt # Arquivo de banco de dados (entrada do projeto)
├── README.md # Instruções de uso

yaml
Copiar código

---

## 🚀 Como Executar no Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com/).

2. Faça o upload dos arquivos do repositório:
   - `Checkpoint1_SERS_sem2_(1).ipynb`
   - `banco_dados.txt`

   > Alternativamente, você pode clonar este repositório diretamente no Colab (se estiver público):
   ```python
   !git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   %cd SEU-REPOSITORIO
Abra o arquivo Checkpoint1_SERS_sem2_(1).ipynb no Colab.

Caso o notebook espere o caminho do banco de dados, ajuste para o local correto.
Exemplo (se o arquivo está no mesmo diretório do notebook):

python
Copiar código
with open("banco_dados.txt", "r") as f:
    dados = f.readlines()
Execute todas as células do notebook para rodar o projeto.

⚠️ Observações
Certifique-se de que o arquivo banco_dados.txt está no mesmo diretório do notebook ou ajuste o caminho no código.

Se preferir usar Google Drive para armazenar os arquivos, monte o drive no Colab com:

python
Copiar código
from google.colab import drive
drive.mount('/content/drive')
📜 Licença
Defina aqui a licença do projeto (ex.: MIT, GPL, Apache 2.0, etc.).
