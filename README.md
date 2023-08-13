OBS: mais um exemplo de como se fazer um Dashboard mais antes preparar os dados com Python

# Aeroporto Dashboard de Fluxo Mensal de Passageiros

Este repositório contém um projeto de construção de um dashboard de dados para auxiliar o time de operações de um grande aeroporto na tomada de decisões relacionadas ao fluxo mensal de passageiros. O dashboard utiliza os dados de voos para fornecer informações importantes sobre a movimentação de passageiros ao longo do tempo.

## Extração

### Passo a passo

1. Carregue as bibliotecas Python necessárias para a manipulação de dados.
2. Carregue os dados de voos (flights) no formato de DataFrame.
3. Responda às seguintes perguntas:
   - Qual é a granularidade temporal da base de dados?
   - Qual é o intervalo de tempo (mínimo e máximo)?

## Transformação

### Passo a passo

1. Transforme o texto da coluna "month" para sua representação numérica (por exemplo: Jan para 1 e Dec para 12).
2. Crie uma chave temporal "year-month" no formato YYYY-MM através da concatenação das colunas "year" e "month" (exemplo: 1949-01).

### Passo a passo

1. Salvei o DataFrame em um arquivo chamado "flights.csv" no formato CSV.
2. Certifique-se de que o índice seja descartado durante o salvamento, caso você for fazer.

## Dashboard

### Passo a passo para o Google Data Studio

1. Crie a fonte de dados "flights-data" através do upload do arquivo "flights.csv".
2. Crie o relatório "flights-report" utilizando a fonte de dados "flights-data".
3. Edite o relatório de acordo com sua criatividade, personalizando texto, cores e visualizações.
4. Compartilhe o relatório gerado por meio de um link acessível.

Sinta-se à vontade para adaptar e expandir esse README conforme suas necessidades específicas. Certifique-se de incluir todas as instruções relevantes para que outros colaboradores ou usuários possam entender e contribuir para o projeto de forma eficiente.

<h4 align="center"> 
    :construction:  Projeto em construção  :construction:
</h4>

# AUTOR

[<img loading="height:auto" src="https://avatars.githubusercontent.com/u/134460985?v=4" width=115><br><sub>Luis Fernando </sub>](https://github.com/luisfernandogbraga) 
