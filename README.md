# Olá, eu sou o Vitor Marinho 👋

### Engenheiro de IA & Dados | Agentes de IA · RAG · LLMs | Python · PySpark · Databricks · Azure · AWS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vitor-marinho)
[![Portfólio](https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vitormarinho.vercel.app)
[![Outlook](https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:vtechdata.solutions@outlook.com.br)
[![Agient](https://img.shields.io/badge/Agient-111111?style=for-the-badge&logoColor=white)](https://agient.com.br)
![novo](https://img.shields.io/badge/novo-f3e8ff?style=flat-square)

---

## 👨‍💻 Sobre mim

Engenheiro de IA & Dados com experiência construindo desde a base, com pipelines **ETL/ELT escaláveis** e arquitetura **Lakehouse (Medallion)** em Azure e AWS, até a camada de inteligência por cima dela: agentes de IA orquestrados com **RAG** consultando esses mesmos dados em tempo real.

Atuei em projetos reais com grandes volumes de dados nos setores de **saúde (oncologia)** e **mineração e metalurgia**, desenvolvendo soluções ponta a ponta, da ingestão nas camadas Bronze, Silver e Gold até a disponibilização para times de Analytics, Ciência de Dados e áreas de negócio.

- 🔭 Atualmente buscando novas oportunidades como **Engenheiro de IA & Dados**
- 🚀 Fundador da [Agient](https://agient.com.br), estúdio de automação e IA para comércio local
- 🌱 Estudando **inglês** e aprofundando conhecimentos em **AWS e MLOps**
- 💬 Aberto a oportunidades **CLT e PJ**, remoto ou híbrido
- 📍 Taquaritinga, SP, Brasil

---

## 🤖 Orquestração Multi-Agente: IA & Dados ![novo](https://img.shields.io/badge/novo-f3e8ff?style=flat-square)

Aplico o mesmo princípio de orquestração aos meus próprios pipelines de dados: um orquestrador central distribui a tarefa entre agentes especializados, e o agente de consulta usa **RAG** para buscar contexto real nas camadas Gold antes de qualquer resposta chegar ao LLM. A resposta parte do dado real, não da memória do modelo.

```mermaid
flowchart LR
    P[Pergunta de negócio] --> M[Orquestrador]
    M --> A1[Agente de Ingestão\nBronze → Silver → Gold]
    M --> A2[Agente de Consulta]
    A2 --> RAG[[RAG: busca contexto\nnas camadas Gold]]
    A1 --> D[(Databricks / Supabase)]
    RAG --> D
    RAG --> L[LLM]
    L --> R[Resposta com dado real + fonte]
```

## 🤖 Orquestração Multi-Agente: IA & Marketing ![novo](https://img.shields.io/badge/novo-f3e8ff?style=flat-square)

O mesmo padrão, aplicado agora a atendimento e geração de demanda: o agente de atendimento usa **RAG** sobre a base de produtos e FAQ da empresa para responder ao lead com informação real, enquanto os agentes de conteúdo e qualificação atuam em paralelo, cada um dentro do seu próprio contexto.

```mermaid
flowchart LR
    P[Lead / Mensagem] --> M[Orquestrador]
    M --> A1[Agente de Atendimento]
    A1 --> RAG[[RAG: busca contexto\nna base de produtos/FAQ]]
    M --> A2[Agente de Conteúdo]
    M --> A3[Agente de Qualificação]
    RAG --> K[(Base de conhecimento)]
    RAG --> L[LLM]
    L --> R[Resposta personalizada]
    A3 --> W[(WhatsApp / CRM)]
```

---

## 🚀 Produtos que Construí ![novo](https://img.shields.io/badge/novo-f3e8ff?style=flat-square)

Projetos próprios, no ar, do início ao fim: arquitetura, backend, frontend e deploy.

| Projeto | Descrição | Link |
|---|---|---|
| **ARIA** | Agente de IA com RAG sobre dados reais (Databricks + Supabase), suporte à decisão em saúde | [Demo](https://agient-aria-health.vercel.app) · [Código](https://github.com/VitorSMarinho/agient-aria-health) |
| **Lazer Livre** | Marketplace de espaços para eventos, em produção | [Demo](https://lazer-livre.vercel.app) |
| **VITRX OS** | Plataforma full-stack de operações de segurança | [Demo](https://vitrixsecuritystaff.vercel.app) |

---

## 🛠️ Tecnologias & Ferramentas

### IA & Agentes
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A1F?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_%2F_Anthropic-D97757?style=for-the-badge&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=for-the-badge&logo=openai&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-1C69FF?style=for-the-badge&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge&logoColor=white)

### Linguagens
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=sqlite&logoColor=white)

### Cloud & Plataformas
![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

### ETL/ELT & Pipelines
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=databricks&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Logic_Apps-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Synapse](https://img.shields.io/badge/Azure_Synapse-0078D7?style=for-the-badge&logo=microsoft&logoColor=white)

### Banco de Dados
![Azure SQL](https://img.shields.io/badge/Azure_SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### DevOps & CI/CD
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Monitoramento
![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

---

## 🚀 Projetos em Destaque

### 🏥 Setor: Saúde (Oncologia/Hematologia)

| Projeto | Descrição | Tecnologias |
|---|---|---|
| **Migração Synapse → Microsoft Fabric** | Transição completa de workloads analíticos com foco em governança, segurança e validação de integridade pós-migração | Fabric, Synapse, PySpark, RBAC |
| **Automação de Ingestão via E-mail** | Pipeline automatizado para captura de anexos via Logic Apps, armazenamento em Data Lake e transformação nas camadas raw/silver | Logic Apps, Data Factory, PySpark |
| **Sustentação e Otimização de Pipelines** | Monitoramento contínuo, resolução de incidentes e otimização de performance em ambiente com dados volumosos | Azure Monitor, Log Analytics, SQL |

### ⛏️ Setor: Mineração e Metalurgia

| Projeto | Descrição | Tecnologias |
|---|---|---|
| **Estruturação de Dados a partir de Planilhas Excel** | Consolidação de dados descentralizados em planilhas para camadas Bronze/Silver/Gold, apoiando a área financeira na tomada de decisão | PySpark, Data Factory, Delta Lake |

---

## 🏗️ Arquitetura que domino

```
Fontes de Dados          Ingestão              Processamento           Consumo
─────────────           ─────────             ─────────────           ───────
SAP          ──►                              ┌─ Bronze (Raw)
SharePoint   ──►   Azure Data Factory   ──►  ├─ Silver (Cleaned)  ──► Analytics
Excel        ──►   Logic Apps                └─ Gold (Aggregated)     BI / DS
APIs         ──►   PySpark / Databricks                               Negócio
```

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=VitorSMarinho&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=6699dd&icon_color=6699dd)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=VitorSMarinho&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=6699dd)

---

## 📚 Certificações em Progresso

- 🔄 **Databricks Certified: Associate Data Engineer**
- 🔄 **Microsoft Certified: Azure Data Engineer Associate (DP-203)**
- 🔄 **Big Data e Analytics na Prática**

---

## 🎯 Objetivo

Construir soluções de dados e agentes de IA escaláveis, confiáveis e orientados ao negócio. Acredito que dados bem estruturados são a base tanto para decisões estratégicas quanto para agentes de IA que realmente entregam valor.

---

> "Dados bem estruturados não são um produto de TI, são uma vantagem competitiva."

---

⭐ **Aberto a oportunidades: CLT ou PJ | Remoto ou Híbrido**
