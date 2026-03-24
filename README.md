# 🛡️ Reply AI Agent Challenge 2026 - Fraud Detection

Este repositório contém a solução desenvolvida para o **Reply AI Agent Challenge 2026**. O projeto foca na criação de um sistema multi-agente inteligente para detecção e mitigação de fraudes complexas em tempo real.

---

## 🚀 Tecnologias e Ferramentas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![LangChain](https://img.shields.io/badge/LangGraph-121011?style=for-the-badge&logo=chainlink&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC0000?style=for-the-badge&logo=postgresql&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🧠 Arquitetura: The Defender's Loop

O sistema utiliza uma arquitetura de agentes orquestrados via **LangGraph**, seguindo o fluxo:

1.  **Gatekeeper (Ingestão)**: Filtro inicial de transações e normalização de dados.
2.  **Swarm Intelligence (Análise)**: Três agentes especializados atuando em paralelo:
    * **Behavioral Agent**: Analisa padrões históricos do usuário.
    * **Network Agent**: Identifica conexões suspeitas e grafos de fraude.
    * **Heuristic Agent**: Aplica regras de negócio e limites de segurança.
3.  **Adjudicator (Decisão)**: Consolida as análises e emite o veredito final (Aprovado/Fraude).

---

## 👥 Equipe

Reconhecimento aos desenvolvedores que tornaram este projeto possível:

| Integrante | GitHub | LinkedIn |
| :--- | :--- | :--- |
| **Wesley Vitor** | [@CodeByWesley](https://github.com/CodeByWesley) | [LinkedIn](https://www.linkedin.com/in/wesleymendoncabr) |
| **Matheus Mendes** | [@matheusmendes720](https://github.com/matheusmendes720) | [LinkedIn](https://www.linkedin.com/in/matheus-mendes-36ba58214/) |
| **Rodrigo Jeronimo** | [@TheRodrig0](https://github.com/TheRodrig0) | [LinkedIn](https://www.linkedin.com/in/rodrigo-jeronimo-qs) |

---

## 📂 Estrutura do Projeto

* `src/agents/`: Lógica individual dos agentes de IA.
* `src/core/`: Orquestração do grafo de decisão (Adjudicator).
* `src/utils/`: Utilitários de formatação e suporte.
* `requirements.txt`: Dependências do projeto.

---

> *"Equivalência de Troca: Dados brutos por Segurança Total."*
