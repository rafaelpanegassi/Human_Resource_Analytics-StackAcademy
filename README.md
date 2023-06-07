# Objetivo do Projeto

Este projeto aborda todas as etapas de um projeto real de Data Science e tem como objetivo resolver o problema de como utilizar dados para responder a questões importantes, permitindo que uma empresa tenha conhecimento sobre:

- Quais são os fatores que influenciam um colaborador a deixar a empresa?
- Como reter pessoas?
- Como antecipar e identificar se um determinado colaborador vai sair da empresa?

Além disso, o projeto disponibiliza recursos para que a empresa possa realizar a predição de saída de um colaborador com base em atributos como comportamento, carga de trabalho, nível de satisfação com a empresa e resultados de performance.

# Solução Proposta
- Tecnologias:
    - Apache Airflow ✔️
    - Docker ✔️
    - Minio ✔️
    - Pandas ✔️
    - Scikit-learn ✔️
    - Pycaret ✔️
    - SweetViz ✔️
    - Streamlit ✔️
- Arquitetura:
    - Construção de uma solução completa para armazenamento, gestão e           automatização de fluxos de dados. ✔️
- Frameworks:
    - Apache Airflow para automatização de fluxos de dados. ✔️
    - Docker para gerenciamento de containers. ✔️
    - Minio para armazenamento de dados. ✔️
    - Pandas, Scikit-learn, Pycaret, SweetViz e Streamlit para análise de dados e machine learning. ✔️
- Desafios Técnicos:
    - Construção da infraestrutura adequada para suportar o projeto. ✔️
    - Modelagem de atributos relevantes para análise. ✔️
    - Integração de diferentes fontes de dados, como arquivos xlsx, json e um banco de dados MySQL. ✔️
- Soluções Escolhidas:
    - Utilização de tecnologias como Apache Airflow, Docker e Minio para armazenamento, gestão e automatização de fluxos de dados. ✔️
    - Utilização de Pandas, Scikit-learn, Pycaret, SweetViz e Streamlit para análise de dados e machine learning. ✔️

# Resultados
- Insights e Conhecimento Gerado:
    - Identificação de insights importantes durante a Análise Exploratória de Dados, incluindo:
        - A empresa apresenta uma taxa de rotatividade de 24%. ✔️
        - Colaboradores menos satisfeitos tendem a deixar a empresa. ✔️
        - Existe um número considerável de colaboradores insatisfeitos. ✔️
        - A maioria dos colaboradores que saíram tinham salários baixos ou médios. ✔️
        - Os departamentos de vendas, técnico e suporte apresentam os maiores índices de rotatividade. ✔️
        - Colaboradores com baixa performance tendem a deixar a empresa. ✔️
        - Colaboradores insatisfeitos têm maior probabilidade de deixar a empresa. ✔️
    - Desenvolvimento de 3 grupos distintos para agrupar colaboradores que deixaram a empresa por comportamentos similares:
        - Grupo 1 (Empregados insatisfeitos e trabalhadores): Satisfação inferior a 20 e avaliações superiores a 75. ✔️
        - Grupo 2 (Empregados ruins e insatisfeitos): Satisfação entre 35 e 50 e avaliações abaixo de ~58. ✔️
        - Grupo 3 (Empregados satisfeitos e trabalhadores): Representa os empregados ideais, que gostam do seu trabalho e são bem avaliados. ✔️

