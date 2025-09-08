📌 Descrição do Projeto

Este repositório contém um pipeline de dados desenvolvido no Azure Databricks utilizando PySpark, com orquestração via Apache Airflow (executado localmente em WSL2 e integrado ao VS Code).

O pipeline realiza a ingestão de dados da Exchange Rates Data API (APILayer) como fonte primária, processa e organiza o histórico de cotações de moedas e disponibiliza os resultados em dois formatos principais:

📂 Arquivo CSV exportado para consumo externo.

📊 Gráficos analíticos enviados ao Slack através da API e bot da plataforma.

🔧 Principais Tecnologias

Azure Databricks – processamento distribuído em PySpark

Apache Airflow – orquestração de tarefas

WSL2 + VS Code – ambiente local de desenvolvimento

APILayer - Exchange Rates Data API – fonte de dados de cotações

Slack API & Bot – integração para envio de análises gráficas

🚀 Objetivo

Automatizar a coleta, transformação e distribuição de dados de câmbio, garantindo insights acessíveis tanto em formato estruturado (CSV) quanto em dashboards dinâmicos diretamente no Slack.

<img width="1918" height="596" alt="Airflow" src="https://github.com/user-attachments/assets/fcc11d36-d452-4aac-bd6d-eccdbd7146c7" />
<img width="1916" height="924" alt="Slack" src="https://github.com/user-attachments/assets/6d5f60f5-8d50-475d-aca4-fb6a9e19d909" />
