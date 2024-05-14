# Resolução do Desafio de Engenharia de Dados
Este repositório contém a minha solução para o desafio de engenharia de dados proposto por Magrathea Labs.  <br /> 
O desafio original pode ser encontrado aqui: https://github.com/magrathealabs/desafio-engenharia-dados

## Descrição do Desafio
O desafio consiste em duas partes: 

1. Carregamento e armazenamento dos dados
2. Construção de visualizações dos dados carregados.

Alguns pontos que achamos relevante:
- Utilizando a linguagem de sua preferência construa programas para:
  - Efetuar o download e carregamento automatizado dos dados em um banco para análise de forma periódica.
  - Realizar uma rotina de verificação de qualidade dos dados importados.
- Utilizando a ferramenta de sua preferência construa um dashboard mostrando as seguintes informações:
  - Mostre qual os top 3 produtos mais exportados por estado nos anos de 2017, 2018 e 2019;
  - Mostre qual os top 3 produtos mais importados por estado nos anos de 2017, 2018 e 2019;
  - Mostre qual os top 3 produtos exportados em cada mês de 2019 por estado;
  - Representatividade em valor de exportação por estado no ano de 2019 em relação ao total exportado pelo país no mesmo ano;
  - Representatividade em valor de importação por estado no ano de 2019 em relação ao total importado pelo país no mesmo ano.

Links importantes:
- [Informações sobre layout de dados](https://www.gov.br/produtividade-e-comercio-exterior/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta
)
- [Dados de Exportações](https://balanca.economia.gov.br/balanca/bd/comexstat-bd/ncm/EXP_COMPLETA.zip)
- [Dados de Importações](https://balanca.economia.gov.br/balanca/bd/comexstat-bd/ncm/IMP_COMPLETA.zip)

## Resultados
Após a implementação da minha solução, os resultados obtidos foram a exibição dos gráficos separadamente  <br />
e ao final do código, um dashboard com os todos os gráficos requisitados.

## Como Executar
Para executar o código fornecido neste repositório, siga as etapas abaixo:

- Certifique-se de ter o Python instalado em seu ambiente. Este projeto foi desenvolvido usando Python 3.x.
- instale o VsCode
- instale a extenção jupyter no VScode, caso tenha dúvidas na hora da instalação, siga o tutorial: <br />
  https://www.hashtagtreinamentos.com/jupyter-notebook-no-vscode-python?gad_source=1&gclid=CjwKCAjwl4yyBhAgEiwADSEjeAfQpwlWm5V68Q6j09bPEJ9P8GusIoLWf8EOyFRFkb4tZjsDuJkrHBoCATsQAvD_BwE 
- Instale as dependências necessárias (se houver) especificadas no arquivo requirements.txt.
-

Clone este repositório para o seu ambiente local.
Instale as dependências necessárias (se houver) especificadas no arquivo requirements.txt. E
Execute o script principal no VScode.

## Estrutura de Pasta

A estrutura de pastas do projeto está organizada da seguinte maneira:

```bash
-   `README.md`: Documentação explicando o projeto, instruções de uso e informações gerais.
-   `DesafioGov.ipynb`: Script que contém o código fonte do projeto.
-   `requirements.txt`: Lista todas as dependências do projeto para facilitar a instalação.
