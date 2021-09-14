# Projeto PIB - 2010-2018
## Extração de dados do PIB por municípios brasileiros 

### Dados extraídos do site do IBGE com dados de 2010 à 2018, com valores corrigidos para 2018

### O projeto atualmente está dividido em três notetbooks:

ETL.ipynb - Realiza download do arquivo do site do IBGE, realiza alguns tratamentos e salva o resultado em um arquivo stage no formato .parquet
<p>
ETL-2.ipynb - Utiliza o arquivo da stage para gerar arquivo com características dimensão/ fato em formato .parquet
<p>
Analise_Regiao.ipynb - Utiliza o arquivo da stage para realizar análises gráficas consolidados por macro região


### O projeto atualmente tem três diretórios:

/datalake - Local onde está armazenado arquivo de download do IBGE
<p>
/stage - Local onde está armazenado arquivo de stage .parquet
<p>
/dw - Local onde está armazenado arquivo com características dimensão/ fato em formato .parquet para posterior utilização por ferramenta de BI
