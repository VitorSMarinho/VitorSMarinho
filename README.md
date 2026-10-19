# Olá, eu sou o Vitor Marinho 👋

### Engenheiro de Dados & IA | Databricks · PySpark · Delta Lake · Azure · Microsoft Fabric | RAG

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitor-marinho)
[![Portfólio](https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vitormarinho.vercel.app)
[![Outlook](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:vtechdata.solutions@outlook.com.br)

---

## 👨‍💻 Sobre mim

Engenheiro de Dados desde 2023, construindo pipelines **ETL/ELT** e **Data Lakes no Azure** (**Synapse Analytics, Data Lake Storage Gen2, Data Factory**) e **Lakehouses em Databricks** (PySpark, Delta Lake, Medallion), com governança sob **LGPD**. Na **CBMM**, tratei dados do **SAP** em Databricks com **Unity Catalog**, da camada raw até o consumo no Power BI. Conduzi a migração de um ambiente de dados para um **novo tenant Azure**, de Dev a Prod, e atuei na POC do **Microsoft Fabric** com a Microsoft.

Atuei em projetos reais com grandes volumes de dados nos setores de **saúde (A.C.Camargo Cancer Center, oncologia)** e **mineração e metalurgia (CBMM)**, desenvolvendo soluções ponta a ponta, da ingestão nas camadas Bronze, Silver e Gold até a disponibilização para times de Analytics, Ciência de Dados e áreas de negócio.

Nos projetos recentes levo essa base para a IA: pipelines que alimentam **RAG** e agentes, com dado vetorial em PostgreSQL/pgvector. A resposta do modelo parte do dado real, e dado real precisa ser confiável.

- 🔭 Buscando oportunidades como **Engenheiro de Dados**
- 🌱 Estudando **inglês** e aprofundando conhecimentos em **AWS e MLOps**
- 💬 Aberto a oportunidades **CLT e PJ**, remoto ou híbrido
- 📍 Taquaritinga, SP, Brasil

---

## 🚀 Projetos em Destaque

### 🏥 A.C.Camargo Cancer Center: Saúde (Oncologia)

| Projeto | Descrição | Tecnologias |
|---|---|---|
| **Migração de tenant Azure** | Mapeamento completo do ambiente antigo (Synapse, pipelines, triggers, tabelas, Storage, Key Vault, acessos por usuário), migração gradual de Dev, Prod tabela a tabela e validação de paridade de linhas, tamanhos e tipos de arquivo; esteira CI/CD reconfigurada | Synapse, Storage, Key Vault, Azure DevOps, SQL |
| **Microsoft Fabric: POC e governança** | POC com a Microsoft e o time de Arquitetura: configuração inicial, workspace do projeto, documentação de governança (nomenclatura, padrões, acessos por nível) e habilitação de engenheiros pleno e sênior | Microsoft Fabric, RBAC |
| **Automação de Ingestão via E-mail** | Pipeline automatizado para captura de anexos via Logic Apps, armazenamento no Data Lake e transformação nas camadas raw/silver | Logic Apps, Data Factory, Data Lake Storage Gen2, Azure Synapse |
| **Sustentação e Otimização de Pipelines** | Notebooks PySpark e SQL pools no Azure Synapse sobre origens Oracle e o Data Warehouse do cliente: monitoramento contínuo, resolução de incidentes e otimização de performance com dados volumosos | Azure Synapse, PySpark, SQL pools, Oracle, Azure Monitor, Log Analytics |

### ⛏️ CBMM: Mineração e Metalurgia

| Projeto | Descrição | Tecnologias |
|---|---|---|
| **Lakehouse SAP: custo de produção e suprimentos** | Dados do SAP (Material Ledger e MM), orçamento via catálogo federado e preços de mercado tratados da camada raw até as views dos relatórios Power BI. Padrão de higiene do cliente implementado em funções PySpark reutilizáveis (chave MD5, metadados, soft delete), dimensões na camada de serviço, manutenção dos jobs de orquestração, validação de linhagem via information_schema e gestão das entregas em sprints no Azure Boards (tasks, horas, relatório semanal ao cliente) | Databricks, Unity Catalog, PySpark, Delta Lake, Databricks Jobs, Power BI, Azure DevOps |

### 🧪 Projetos próprios

| Projeto | Descrição | Status |
|---|---|---|
| **ARIA** | Pipeline Medallion em Databricks sobre dados clínicos fictícios, alimentando um agente de IA com RAG (Supabase + pgvector) | Em breve |
| **payments-data-harness** | Harness para produtos de dados de pagamentos com dados públicos do Banco Central: qualidade como portão, guardrails de PII/PCI e aprovação humana antes da camada gold | Em desenvolvimento · [Código](https://github.com/VitorSMarinho/payments-data-harness) |

---

## 🏗️ Arquitetura que domino

```
Fontes de Dados          Ingestão              Processamento           Consumo
─────────────           ─────────             ─────────────           ───────
SAP          ──►                              ┌─ Bronze (Raw)
SharePoint   ──►   Azure Data Factory   ──►  ├─ Silver (Cleaned)  ──► Analytics
Excel        ──►   Logic Apps                └─ Gold (Aggregated)     BI / DS / IA
APIs         ──►   PySpark / Databricks                               Negócio
```

---

## 🛠️ Tecnologias & Ferramentas

### Engenharia de Dados & Plataformas
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=databricks&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Synapse](https://img.shields.io/badge/Azure_Synapse-0078D7?style=for-the-badge&logo=microsoft&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Logic_Apps-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

### Linguagens
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=sqlite&logoColor=white)

### Cloud
![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

### Banco de Dados
![Azure SQL](https://img.shields.io/badge/Azure_SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### DevOps, CI/CD & Monitoramento
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

### IA aplicada a dados
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

---

## 🤖 Dados que alimentam IA

O agente de consulta usa **RAG** para buscar contexto real nas camadas Gold antes de qualquer resposta chegar ao LLM. Por isso a qualidade da IA depende da qualidade do pipeline.

```mermaid
flowchart LR
    F[Fontes] --> B[Bronze]
    B --> S[Silver: limpeza e validação]
    S --> G[Gold]
    G --> D[(Databricks / Supabase)]
    P[Pergunta de negócio] --> A[Agente de Consulta]
    A --> RAG[[RAG: busca contexto\nnas camadas Gold]]
    RAG --> D
    RAG --> L[LLM]
    L --> R[Resposta com dado real + fonte]
```

---

## 📚 Certificações em Progresso

- 🔄 **Databricks Certified: Associate Data Engineer**
- 🔄 **Microsoft Certified: Azure Data Engineer Associate (DP-203)**
- 🔄 **Big Data e Analytics na Prática**

---

## 🎯 Objetivo

Construir soluções de dados escaláveis, confiáveis e orientadas ao negócio. Acredito que dados bem estruturados são a base tanto para decisões estratégicas quanto para uma IA que realmente entrega valor.

---

> "Dados bem estruturados não são um produto de TI, são uma vantagem competitiva."

---

⭐ **Aberto a oportunidades como Engenheiro de Dados: CLT ou PJ | Remoto ou Híbrido**
