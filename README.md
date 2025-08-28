📊 Projeto de Análise de Dados COVID-19

Este repositório contém um projeto de análise de dados relacionado à pandemia de COVID-19, com foco em tratamento, organização e geração de relatórios estatísticos.

🔹 Estrutura do Projeto

casos_full.csv → Conjunto de dados bruto com registros de casos.

tabela_mortes.csv → Dados específicos sobre óbitos.

clean_casos_full.py → Script responsável por limpar e padronizar os dados.

relatorios_covid.py → Gera relatórios, gráficos e estatísticas a partir dos dados tratados.

relatorios/ → Pasta com os resultados finais (gráficos, resumos de cidades e análises de mortalidade).

🔹 Funcionalidades

Limpeza e padronização de dados de casos de COVID-19.

Geração de relatórios estatísticos em texto.

Criação de gráficos de evolução populacional e mortalidade.

Identificação das cidades com maior número de mortes.

🔹 Tecnologias Utilizadas

Python 3

Pandas → manipulação e análise de dados

Matplotlib / Seaborn → geração de gráficos

CSV como formato principal de entrada/saída

🔹 Como Executar

Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio


Instale as dependências:

pip install pandas matplotlib seaborn


Execute o script de limpeza:

python clean_casos_full.py


Gere os relatórios:

python relatorios_covid.py

🔹 Resultados

Gráficos comparativos de evolução.

Listagem das 10 cidades com mais mortes.

Relatórios salvos em .txt e .png.
