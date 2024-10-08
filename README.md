# Relatório de Empresas de Reciclagem
Este projeto tem como objetivo analisar os dados de empresas de reciclagem com base em informações cadastrais e seus métodos de reciclagem, utilizando Python e bibliotecas como pandas, matplotlib, e plotly para manipulação e visualização dos dados.

# 📋 Funcionalidades
Filtragem de Dados:

O dataset original foi filtrado para exibir apenas as empresas que possuem as situações cadastrais "Encerrado" ou "Ativa".
Foram realizadas operações de conversão para garantir que a coluna Quantidade seja numérica.
Análise por Estado:

Foram selecionados apenas os estados com mais de 122 ocorrências.
Gráficos de barras, histogramas e box plots foram gerados para visualizar a distribuição das empresas por estado.
Análise por Método de Reciclagem:

Foram filtrados os métodos de reciclagem com mais de 38 ocorrências.
Gráficos de barras, histogramas e box plots foram gerados para analisar os métodos de reciclagem das empresas.
Análise por Unidade de Medida:

Foram filtradas as empresas cuja unidade de medida seja "kilogramas".
Calculada a média e o desvio padrão das quantidades, com a normalização dos valores de quantidade para "kilogramas".
Gravação dos Dados Tratados:

Após a limpeza e manipulação, os dados foram salvos em um arquivo Excel chamado base_empresas_reciclagem_IA.xlsx.

# 🛠️ Tecnologias Utilizadas
Python: Linguagem de programação principal.
pandas: Biblioteca para manipulação de dados.
matplotlib: Biblioteca para visualização de gráficos.
plotly: Biblioteca interativa para gráficos avançados.
Excel: Formato de saída para os dados tratados.

# 📊 Visualizações
Exemplos de Gráficos Gerados:
Gráfico de Barras: Distribuição de empresas por estado e por método de reciclagem.
Histograma: Frequência das quantidades de empresas.
Box Plot: Análise estatística das quantidades por estado e método de reciclagem.

# 📈 Análise Estatística
Média: Foi calculada a média das quantidades das empresas cuja unidade de medida é "kilogramas".
Desvio Padrão: O desvio padrão das quantidades foi calculado para padronização.

# 💾 Exportação dos Dados
Após a limpeza e manipulação dos dados, o DataFrame final foi salvo em um arquivo Excel:

# 🚀 Como Utilizar
Instale as dependências necessárias:
bash
pip install pandas matplotlib plotly

Execute o código para carregar, limpar e visualizar os dados.
O arquivo tratado será salvo como base_empresas_reciclagem_IA.xlsx.