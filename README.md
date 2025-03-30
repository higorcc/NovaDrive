# 🚀 NovaDrive
Projeto prático que simula a atuação de um engenheiro de dados no contexto de uma concessionária, abrangendo desde a ingestão de dados até a transformação e modelagem para análise.

## 📌 Tecnologias Utilizadas
- Python
- SQL
- Airflow
- dbt
- Snowflake

## 📂 Estrutura do Repositório
📁 **DAG - Airflow** → Contém a DAG utilizada no Airflow  
📁 **dbt** → Scripts SQL utilizados para transformação de dados  

## 🔧 Como Utilizar
1. Baixe ou clone este repositório (caso queira manter localmente).
2. Certifique-se de ter as tecnologias necessárias instaladas.
3. Execute os scripts conforme necessidade.

## ✨ Sobre o Projeto
A base de dados transacional foi armazenada no PostgreSQL. Para orquestrar a extração e carga dos dados no Snowflake, utilizei o Airflow. No Snowflake, os dados foram transformados e organizados na camada analítica com o dbt. Por fim, as visualizações e análises foram criadas no Looker.