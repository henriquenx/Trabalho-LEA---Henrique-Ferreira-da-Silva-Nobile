# Trabalho LEA - Henrique F. da S. Nobile | RA: 791117

**Descrição do Projeto**

Este projeto realiza a extração de dados de notícias econômicas do site A Cidade ON, passando por 50 páginas de conteúdo. Utilizando as bibliotecas Requests e BeautifulSoup, o script coleta informações como URL, título, data, categoria e uma breve descrição de cada notícia.

Os dados são salvos em um arquivo JSON dentro de uma pasta data e podem ser utilizados para análises posteriores.

**Estrutura do Repositório**
- noticias_cidade_on_rp.ipynb: Notebook responsável pela extração e salvamento dos dados.
- data/noticias.json: Arquivo contendo os dados extraídos.
- analise_noticias_cidade_on_rp.ipynb: Notebook contendo a análise dos dados coletados.
- README.md: Documentação do projeto.

**Tecnologias Utilizadas**
- Python 3.x
- Requests: Para realizar requisições HTTP.
- BeautifulSoup 4: Para fazer o scraping de conteúdo HTML.
- Pandas e Matplotlib (para análises e visualização de dados no Notebook)
