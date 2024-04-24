# Análise e Previsão de Preço do Gás de Cozinha

Este projeto tem como objetivo analisar o impacto do preço do gás de cozinha (GLP) no bolso dos brasileiros, comparando a média de preços com o salário mínimo vigente. Utilizando uma série histórica de preços de GLP disponibilizada pela [Agência Nacional do Petróleo (ANP)](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis) e dados de salário mínimo do [Ipeadata](http://www.ipeadata.gov.br/exibeserie.aspx?stub=1&serid1739471028=1739471028), o projeto realiza análises e previsões para entender a relação entre o preço do gás de cozinha e o salário mínimo no Brasil.

## Objetivos do Projeto

- Analisar a evolução do preço médio do GLP ao longo dos anos.
- Comparar o preço médio do GLP com o salário mínimo vigente para determinar a proporção em relação ao salário mínimo.
- Realizar previsões do preço do GLP para os próximos meses.

### Relatórios

O projeto visa produzir os seguintes relatórios:

- Artigo sobre Web Scraping para obter dados de preços de GLP.
- Artigo sobre o uso da biblioteca Prophet para previsão de séries temporais.
- Relatório completo das análises realizadas e das previsões obtidas neste projeto.

## Fontes de Dados Utilizadas

- **Série Histórica de Preços de GLP:** [ANP - Agência Nacional do Petróleo](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis)
- **Série Histórica de Salário Mínimo:** [Ipeadata](http://www.ipeadata.gov.br/exibeserie.aspx?stub=1&serid1739471028=1739471028)

## Ferramentas Utilizadas

Python Libraries:
- Pandas: Manipulação e análise de dados.
- Matplotlib: Visualização de gráficos.
- Seaborn: Visualização estatística de dados.
- Requests: Para fazer solicitações HTTP.
- BeautifulSoup: Para fazer Web Scraping de páginas HTML.
- Prophet: Biblioteca para previsão de séries temporais.
- Scikit-learn (utilizado em parte do código não mostrado): Para métricas de avaliação de modelos.

## Executando o Projeto

Para executar este projeto, é necessário ter o Python instalado, juntamente com as bibliotecas listadas no arquivo `requirements.txt`.

- Utilize o arquivo `Análise_de_dados_gás_cozinha_(GLP).ipynb` para seguir o fluxo de análise.
- Certifique-se de ter conexão com a internet para baixar os dados necessários.
- Cada seção do notebook está separada por objetivos específicos e explicações detalhadas.

## Resultados

Disponibilizado o arquivo `relatorio_analitico.pdf` com o relatório com a análise completa.
O projeto inclui análises visuais da evolução do preço do GLP ao longo dos anos.
Comparações entre o preço do GLP e o salário mínimo, fornecendo insights sobre a fatia do salário mínimo destinada ao gás de cozinha.
Previsões do preço do GLP para os próximos meses usando a biblioteca Prophet.

## Conclusão

Este projeto oferece uma análise abrangente sobre o preço do gás de cozinha e sua relação com o salário mínimo no Brasil. As previsões ajudam a entender as tendências futuras e o possível impacto econômico no orçamento das famílias brasileiras.

Para mais detalhes, consulte o arquivo `Análise_de_dados_gás_cozinha_(GLP).ipynb` e os gráficos gerados durante o processo.
