🛠️ Apache Spark & Engenharia de Dados - Guia de Estudos 🚀

📌 Sobre este Repositório

Este repositório foi criado para centralizar estudos e experimentos com Apache Spark no contexto de Engenharia de Dados. Aqui, você encontrará anotações, exemplos de código, desafios práticos e links úteis para aprofundar o conhecimento na área.

📖 Conteúdo

1️⃣ Fundamentos do Apache Spark

Arquitetura e componentes do Spark

Spark Core e RDDs

Transformações e Ações

Comparação: RDDs vs. DataFrames vs. Datasets

2️⃣ Processamento Distribuído

Lazy Evaluation e DAG (Directed Acyclic Graph)

Particionamento e Paralelismo

Gerenciamento de memória e otimizações

3️⃣ Spark SQL e DataFrames

Introdução ao Spark SQL

Operações com DataFrames

Funções SQL no Spark

Otimização com Catalyst Optimizer

4️⃣ Processamento de Streaming

Introdução ao Spark Streaming

Estrutura de Micro-batches

Integração com Kafka

5️⃣ Engenharia de Dados na Prática

ETL com Spark

Integração com bancos de dados (Delta Lake, PostgreSQL, etc.)

Uso de ferramentas complementares (Airflow, AWS/GCP/Azure)

6️⃣ Desafios e Projetos Práticos

Processamento de grandes volumes de dados

Análise de logs e eventos em tempo real

Criação de pipelines de dados escaláveis

🛠️ Configuração do Ambiente

📌 Requisitos

Python 3.x ou Scala

Apache Spark instalado (Guia de Instalação)

Jupyter Notebook ou PyCharm para desenvolvimento

Docker (opcional, para testes com clusters locais)

📦 Instalando Dependências

pip install pyspark
pip install pandas numpy
pip install findspark

🚀 Rodando o Spark Localmente

import findspark
findspark.init()

from pyspark.sql import SparkSession
spark = SparkSession.builder.appName("EstudosSpark").getOrCreate()
spark

🔗 Recursos Úteis

📚 Documentação Oficial: Apache Spark Docs

🎥 Cursos Online: Udemy, DataCamp, Coursera

📖 Livros: "Learning Spark", "Spark in Action"

💬 Comunidades: Stack Overflow, Databricks Forum
