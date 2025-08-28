📊 Projeto de Análise de Dados COVID-19

Este repositório contém um projeto de análise de dados relacionado à pandemia de COVID-19, com foco em tratamento, organização e geração de relatórios estatísticos.

📂 Estrutura do Projeto
Trabalho_matheus/

│── casos_full.csv              # Base de dados bruta

│── clean_casos_full.py         # Script para limpeza e preparação dos dados

│── relatorios_covid.py         # Script para geração de relatórios e gráficos

│── tabela_mortes.csv           # Tabela processada (gerada automaticamente)

│── relatorios/                 # Resultados: gráficos e relatórios em texto


⚙️ Funcionalidades

Limpeza e padronização de dados de casos de COVID-19.

Geração de tabela consolidada com mortes e populações por cidade.

Relatórios em texto sobre cidades com mais e menos mortes.

Gráficos:

Top 10 cidades com mais mortes.

População inicial x final das cidades com mais mortes.

🛠️ Tecnologias Utilizadas

Python 3

Pandas
 → Manipulação e análise de dados

Matplotlib
 → Geração de gráficos

▶️ Como Executar
1. Clonar o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

2. Instalar dependências
pip install pandas matplotlib

3. Gerar a tabela de mortes
python clean_casos_full.py


Isso criará o arquivo tabela_mortes.csv.

4. Criar relatórios e gráficos
python relatorios_covid.py

📈 Resultados Esperados

Após a execução, serão gerados:

resumo_cidades.txt → Cidades com mais e menos mortes.

top10_mortes.png → Gráfico de barras com as 10 cidades que mais registraram mortes.

populacao_inicial_final.png → Comparativo da população inicial e final das mesmas cidades.

📜 Licença

Este projeto é de uso educacional e pode ser adaptado livremente.
