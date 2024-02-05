Análise e Resultados 

Este repositório abrange análises conduzidas em dois conjuntos de dados, utilizando principalmente a biblioteca pandas em Python, com adição de seaborn e matplotlib para visualizações gráficas. Abaixo, fornecemos uma visão geral das análises realizadas:

DataFrame 'carros':
Carregamento de Dados:

Utilizando a biblioteca pandas, foram carregados dados relacionados à quantidade de carros por estado. O conjunto de dados inclui informações sobre a região, população e a quantidade de carros por habitante.
Ordenação e Proporção:

Os dados foram ordenados pela quantidade de carros em ordem decrescente.
Uma nova coluna foi adicionada para representar a proporção de carros por habitante em cada estado.
Proporção de Carros por Habitante:

Um novo conjunto de dados foi criado, contendo as colunas 'Estado' e 'Proporção de Carros por Habitante', destacando a relação entre carros e população em cada estado.
DataFrame 'df_concurso':
Verificação de Colunas:

Houve uma análise preliminar das colunas disponíveis no DataFrame 'df_concurso'. No entanto, algumas colunas essenciais para análises adicionais não estavam presentes.
Análises Adicionais e Resultados:

Foram realizadas diversas análises no DataFrame 'df_concurso', incluindo porcentagem de pessoas com deficiência, quantidade de inscritos por estado, e dados dos inscritos como número de inscrição, nome e idade.
Tratamento de Dados Faltosos:

Valores faltosos foram tratados no DataFrame 'df_concurso', preenchendo valores nulos em colunas do tipo string com 'Falta informação' e valores numéricos com a mediana.
Visualização de Dados Faltosos:

Foi criada uma visualização gráfica mostrando a porcentagem de dados faltosos por coluna, proporcionando uma visão clara da distribuição de valores ausentes.
Observações Gerais:
Algumas análises no DataFrame 'df_concurso' não foram realizadas devido à ausência de colunas necessárias.
O tratamento de dados faltosos foi aplicado para garantir a integridade das análises subsequentes.
Este resumo proporciona uma visão abrangente das análises conduzidas nos conjuntos de dados. Para uma compreensão mais detalhada, explore os notebooks de análise disponíveis no repositório.

# Clone o Repositório
git clone https://github.com/RaquelFonsec/Challenge-.git

# Acesse o Diretório
cd Challenge-

# Explore os Notebooks
jupyter notebook
