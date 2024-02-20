## SWAPI 
Este é o projeto da Parte 2 do processo seletivo da MaxxiData. O projeto acima foi desenvolvido a partir de um ambiente virtual no python `(venv)` e extraído a pasta `src` para compartilhamento dos códigos de `extract`, `main` e `transform.`

## Objetivo?
O projeto tem como intuito a ingestão de dados de uma API pública chamada SWAPI com dados do Star Wars. Dela foi retirado os seguintes dados:
* People (dados dos personagens do filme);
* Planets (planetas do filme);
* Films (descrição e data de lançamento dos filmes).

## Extract
*  Extraem o código da API SWAPI de forma separada e retorna um dataframe para que possa ser utilizado pela main.py.
*  
## Transform
* Extraem os dados em formato CSV da pasta "Raw" (salvos pela main.py) e faz o tratamento dos dados,isto é, tranforma os dados para lower_case e retira caracteres especiais.

## Main
* Para que o código rode, vá até a pasta main e execute o código:
  
```bash
python main.py
```
* A main tem como função receber os dataframes em formato bruto dos extratores e salvar em formato .CSV na pasta RAW;
* Posteriormente, recebe os dados tratados e transformaddos pelo "transform" e salva os dataframes em arquivo .CSV na pasta Work


## Instalação das Dependências
Dependências do código:

```bash
pip install pandas
```
```bash
pip install numpy
```
```bash
pip install requests
```
```bash
pip install os
```
```bash
pip install re
```
