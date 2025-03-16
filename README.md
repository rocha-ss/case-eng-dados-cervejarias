Projeto criado para elaborar Pipeline de dados utilizando como fonte a API Open Brewery DB, passando por uma série de processos que elaboraram as camadas Bronze (dados brutos e padronizados), Prata (dados submetidos a limpezas e ajustes) e Ouro (dados prontos para consumo).

O objetivo final foi preparar um ambiente que recebe os dados brutos e os preparam para serem utilizados na montagem de relatórios/dashboards em ferramentas de DataViz (Power BI, Looker Studio, Tableau, etc.)

Este projeto utilizou os seguintes recursos:

- Spark: Para lapidação e trabalhos de grande volume de dados (Big Data)

- PySpark: Biblioteca do Python para trabalhar com as funções do Spark

- Azure Data Lake: Para o armazenamento dos dados 

- Databricks: Usado para fazer a orquestração do pipeline, registrando agendamentos, repetições e erros

- GitHub: Serviço responsável por monitorar o versionamento do projeto (armazena histórico de alterações, etc.)

- Fabric: Ecossistema da Microsoft que compila todas as funções necessárias para elaborar o projeto (Pipeline, armazenagem, notebooks para rodar código, etc.)

Criador do projeto: Samuel Silva da Rocha
- E-mail: rocha.samu.97@gmail.com
- LinkedIn: https://www.linkedin.com/in/samuel-rocha-97
- GitHub: https://github.com/rocha-ss/
