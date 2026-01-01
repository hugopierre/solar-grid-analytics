# ☀️ Solar Grid Analytics

## Contexto de negócio

A gestão eficiente de parques solares distribuídos enfrenta o desafio da descentralização de dados. Inversores solares geram métricas críticas (geração em kWh, temperatura, status) a cada minuto, criando um cenário de Big Data.

O projeto é um pipeline projetado para centralizar essa telemetria, permitindo:

1.  **Monitorar a eficiência:** Comparação da geração real com a nominal.
2.  **Manutenção preditiva:** Detecção de anomalias (ex: queda de eficiência por sujeira nos painéis).
3.  **Relatórios ESG:** Cálculo automatizado de Carbono (CO2) evitado.

## Arquitetura do pipeline

O projeto segue o fluxo clássico de Engenharia de Dados (ELT):

- **Ingestão (Extract):** Simulação de sensores IoT enviando dados brutos.
- **Processamento (Transform):** Limpeza, normalização e validação de qualidade (Data Quality).
- **Armazenamento (Load):** Persistência em Data Lake/Data Warehouse para análise.

## Stack

- **Linguagem:** Python 3.14.2
- **Versionamento:** Git/GitHub
- **Roadmap:** Pandas, SQL, Docker, Apache Airflow.
