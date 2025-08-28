README.md
# 📊 Análise de Casos de COVID-19  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellowgreen)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)  
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-brightgreen)

Este repositório contém **scripts em Python** e uma base de dados para análise de casos de COVID-19.  
O objetivo é **limpar, organizar e gerar relatórios visuais** a partir dos dados brutos.  

---

## 📂 Estrutura do Projeto  



📦 Trabalho Matheus
┣ 📄 casos_full.csv → Base de dados original
┣ 📄 clean_casos_full.py → Script de limpeza e tratamento dos dados
┣ 📄 relatorios_covid.py → Script para geração de relatórios


---

## ⚙️ Instalação  

Clone o repositório:  

```bash
git clone https://github.com/usuario/repositorio.git
cd repositorio


Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows


Instale as dependências:

pip install -r requirements.txt


Caso não exista um requirements.txt, você pode instalar manualmente:

pip install pandas matplotlib seaborn

🚀 Como Usar
🔹 Limpeza dos dados

Executar o script de limpeza:

python clean_casos_full.py

🔹 Geração de relatórios

Rodar o script de relatórios após a limpeza:

python relatorios_covid.py


Isso irá gerar gráficos e análises estatísticas sobre os casos de COVID-19.

📊 Sobre os Dados

Arquivo: casos_full.csv

Descrição: Contém registros de casos de COVID-19 (datas, regiões, quantidades, etc.)

Processamento: O arquivo é tratado pelo clean_casos_full.py antes de ser usado em análises.

🛠️ Tecnologias Utilizadas

Python
 🐍

Pandas
 📑

Matplotlib
 📊

Seaborn
 🎨

📌 Melhorias Futuras

 Criar dashboards interativos (Plotly/Dash).

 Documentar exemplos visuais dos relatórios.

 Expandir análises estatísticas avançadas.
