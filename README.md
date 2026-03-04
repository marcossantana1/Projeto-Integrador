# Projeto-Integrador
A atividade acadêmica constituí na estruturação dos dados do COMEX STAT de 2025 e 2026. Nele foi feito a junção das planilhas dos dois anos. A tradução de códigos para nomes de algumas colunas. E a criação de um gráfico de linha para a visualização da quantidade de Kg transportados por mês. 

## Tecnologias utilizadas
Foi utilizado o google.colab para fazer todo o tratamento dos dados e a construção das imagens. 

## Problemáticas inícias
As bases de dados estavam saparadas por ano (2025 e 2026). E as colunas NCM, vias, país, URF e unidade estavam preenchidas com códigos. 
Para resolução desses problemas foi necessário primeiro, fazer a junção das planilhas utlizando a função pd.concat. Depois, foi feito a decodificação dos códigos que estavam nas colunas anteriormente citadas. Essa decodificação foi possível graças as planilhas auxiliares disponilizadas no próprio site do COMEX STAT e a função "merge", cujo a função é pegar colunas com o nomes iguais, de planilhas diferentes e trocar uma informação pela outra. 

## Resultados
<img width="944" height="462" alt="image" src="https://github.com/user-attachments/assets/a9ffe215-7121-406e-88d5-f802c19f9ce4" />

A partir das mineração dos dados foi possível extrair a quantidade em kg que foram exportados desde janeiro de 2025 a janeiro de 2026. 
Analisando o gráfico vemos uma baixa agressiva, e uma parte tem relação com o agronégocio que teve uma baixa expressiva, principalmente na carne bovina e no milho. Fora outros fatores. 

<img width="657" height="311" alt="image" src="https://github.com/user-attachments/assets/a646fb83-3319-4384-991f-2f5ffb292968" />
