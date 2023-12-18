# Projeto de EAE1106 Métodos Computacionais para Economistas - FEA USP

O objetivo do projeto é investigar a base de dados Global Data Sustainable Energy para buscar uma relação entre PIB e energia. Levantamos duas hipóteses, o PIB influencia o nível de consumo de energia e, o uso de energias renováveis favorece o crescimento do PIB.

Documentos
- *archive(1).zp* refere-se ao arquivo baixado original, contém a base de dados em formato `.zip`
- *global-data-on-sustainable-energy (1).csv* é o arquivo com a base de dados em `.csv`
- *sustainable_energy.ipynb* é o arquivo que trabalharemos, é um arquivo jupyter, portanto, `.ipynb`

Essas hipóteses foram formuladas com base em modelos econômicos conhecidos e podem servir como ponto de partida para análises mais detalhadas usando a base de dados fornecida. A interpretação dos resultados deve considerar a natureza específica das relações propostas por cada hipótese.

# Conteúdo da atividade
Partindo do seu conhecimento acumulado até aqui:

Formule uma hipótese e fundamente com base em um modelo formal. Comece apresentando o contexto no qual essa hipótese se insere, a lógica ou modelo por trás dessa hipótese. Você pode optar por apresentar o contexto e a lógica por trás de uma hipótese já existente (e.g., propensão marginal a consumir é descrescente com a renda) ou formular sua própria hipótese derivada de determinado fato econômico (e.g., propensão marginal a consumir é menor em situações de estresse, como a pandemia). O importante é apresentar de forma clara o contexto e a lógica/modelo formal que justifique essa hipótese.
No Moodle do curso vocês vão ter uma lista de bases de dados que vocês poderão utilizar. Cada grupo pode escolher dentre as bases que estão ali, todas elas retiradas da plataforma Kaggle que tenha relação com a sua hipótese e que lhe permita avaliar as evidências empíricas a respeito dessa hipótese (se quiser você pode procurar por bases fora dessa plataforma também, como resultado, por exemplo, de um exercício de webscraping). No máximo dois grupos poderão escolher a mesma base
Traga a base de dados para dentro do Python usando o Pandas e, antes de qualquer coisa, descreva os dados detalhadamente. Você pode fazer isso da forma que preferir, inclusive utilizando gráficos caso ache mais informativo. No entanto, alguns passos são obrigatórios. Você deve apresentar:

Número de linhas, número de colunas, memória alocada para a base e tipo de dado de cada coluna.
Estatísticas descritivas das principais variáveis numéricas de interesse.
Distribuição dos valores das principais variáveis categóricas/strings.
Realize as limpezas e filtragens que julgar necessário na base de dados. Não esqueça de comentar e justificar cada etapa.
Construa gráficos e medidas estatísticas simples (médias por grupo e distribuição por grupo, por exemplo) para apresentar evidências a favor ou contrárias à hipótese inicial. Argumente e racionalize seus resultados. Lembre-se que você está trabalhando com um conjunto de evidências favoráveis ou contrárias, isso não é um teste formal de causalidade e ou rejeição estrita da hipótese.
Conclua o trabalho levantando possibilidades acerca de outras bases de dados e análises que poderiam auxiliar no trabalho de trazer mais evidências relacionadas à hipótese econômica.


Estrutura do arquivo
O arquivo final entregue deve ter uma estrutura específica e ser composto por 5 seções, nessa ordem:

- *INTRODUÇÃO*: apresentação do contexto e do modelo formal por trás da hipótese a ser testada, seguido da descrição clara da própria hipótese;
- *DADOS*: descrição da base de dados e suas principais características.
- *RESULTADOS*: apresentação das evidências empíricas relacionadas à hipótese (gráficos e estatísticas descritivas).
- *CONCLUSÃO*: considerações finais e sugestão de passos futuros para enriquecimento da análise.
