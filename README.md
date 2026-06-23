# Jonathan Scholtes

Senior AI Engineer / Architect @ Microsoft  
**Designing enterprise grade, event driven AI systems that integrate autonomous agents, tools, and self healing workflows into production environments.**

[stochasticcoder.com](https://stochasticcoder.com) • [linkedin.com/in/jonathanscholtes/](https://linkedin.com/in/jonathanscholtes/)

---

## 🚀 Featured Patterns

These reference architectures demonstrate how to move past basic prompt and response into structured, tool driven execution and deterministic agent orchestration.

*   **[Azure SRE Agent GitHub Demo](https://github.com/jonathanscholtes/azure-sre-agent-github-demo)**  
    Takes a production failure spike down to an automated code fix and a merged GitHub PR. Self-healing pipelines built on Azure SRE Agent with governed remediation and incident detection.
    *   **Key Patterns:** Agentic reliability · autonomous remediation loops · GitHub Copilot integration

*   **[Fabric + Foundry Insight & Presentation Agents](https://github.com/jonathanscholtes/Fabric-Foundry-Insight-Presentation-Agents)**  
    Turns live enterprise data into natural-language insights and auto-generated PowerPoint business reviews, chaining a Microsoft Fabric Data Agent to Foundry agents through MCP tooling.
    *   **Key Patterns:** Fabric Data Agent interface · multi-turn reasoning over live data · MCP-driven document generation

*   **[BrandSense — Multi Agent Brand Intelligence](https://github.com/jonathanscholtes/Azure-AI-Foundry-BrandSense)**  
    Scores and validates brand intelligence through guardrailed multi-agent collaboration, combining retrieval, scoring, and validation to keep business outputs trustworthy.
    *   **Key Patterns:** Guardrailed multi-agent collaboration · deterministic validation loops

*   **[Contract Risk Analysis](https://github.com/jonathanscholtes/contract-risk-mcp-foundry)**  
    Evaluates contract risk through repeatable, auditable workflows, using MCP for isolated tool-based evaluation and controlled data access.
    *   **Key Patterns:** Tool-based evaluation isolation · auditable decision trees

*   **[ITSM Multi Agent System](https://github.com/jonathanscholtes/Azure-AI-Foundry-ITSM)**  
    Classifies, routes, and resolves IT service tickets end to end through structured multi-agent orchestration and lifecycle handling.
    *   **Key Patterns:** State-machine orchestration · autonomous ticket remediation

*   **[Microsoft Foundry Agentic Workshop](https://github.com/jonathanscholtes/azure-ai-foundry-agentic-workshop)**  
    A hands-on workshop for building agentic systems — vector search, multi-agent orchestration with LangGraph, and evaluation setups.
    *   **Key Patterns:** Developer enablement · multi-agent evaluation frameworks · LangGraph orchestration

---

## 🧭 Full Catalog

Browse everything by area. ⭐ marks the featured patterns above.

### 🔍 Grounding AI in Enterprise Data

| Project | Services | Tech Stack | Pattern & Use Case |
|---|---|---|---|
| [BrandSense](https://github.com/jonathanscholtes/Azure-AI-Foundry-BrandSense) ⭐ | Microsoft Foundry, Azure OpenAI, AI Search, APIM | Python, FastAPI, React, Terraform | Multi-agent brand analysis using retrieval, scoring, and validation workflows |
| [Contract Risk Analysis](https://github.com/jonathanscholtes/contract-risk-mcp-foundry) ⭐ | Microsoft Foundry, AKS | Python, Bicep, MCP, OpenTelemetry | Autonomous multi-agent contract risk evaluation with auditable workflows |
| [Full Stack RAG System](https://github.com/jonathanscholtes/LangChain-RAG-Pattern-with-React-FastAPI-and-Cosmos-DB-Vector-Store) | Cosmos DB (Mongo vCore) | Python, LangChain, FastAPI, React | Enterprise retrieval-augmented generation pattern |
| [Semantic Kernel RAG System](https://github.com/jonathanscholtes/Azure-AI-Foundry-Semantic-Kernel-RAG) | Microsoft Foundry, AI Search, Cosmos DB, Durable Functions | Semantic Kernel, Python, FastAPI, Bicep | RAG orchestration and foundation for agent-based systems |
| [Travel AI Agent](https://github.com/jonathanscholtes/Travel-AI-Agent-React-FastAPI-and-Cosmos-DB-Vector-Store) | Cosmos DB (Mongo vCore) | Python, LangChain, FastAPI, React | Conversational agent with vector search, state management, and transactional workflows |

### 🤖 Agentic Systems & Governance

| Project | Services | Tech Stack | Pattern & Use Case |
|---|---|---|---|
| [Azure SRE Agent GitHub Demo](https://github.com/jonathanscholtes/azure-sre-agent-github-demo) ⭐ | Azure SRE Agent, Container Apps, Cosmos DB, Managed Identity | Python, FastAPI, Terraform, GitHub Actions | Self-healing pipelines and autonomous remediation |
| [Fabric + Foundry Insight & Presentation Agents](https://github.com/jonathanscholtes/Fabric-Foundry-Insight-Presentation-Agents) ⭐ | Microsoft Fabric, Microsoft Foundry, Container Apps, Managed Identity | Python, FastAPI, FastMCP, python-pptx | Fabric Data Agent → conversational insight → MCP-generated PowerPoint business reviews |
| [Microsoft Foundry Agentic Workshop](https://github.com/jonathanscholtes/azure-ai-foundry-agentic-workshop) ⭐ | Microsoft Foundry, AI Search, Container Apps, Azure Functions | Python, LangGraph, Semantic Kernel, MCP | Multi-agent orchestration and evaluation patterns |
| [ITSM Multi Agent System](https://github.com/jonathanscholtes/Azure-AI-Foundry-ITSM) ⭐ | Microsoft Foundry, AI Search, APIM, Managed Identity | Python, FastAPI, React, Terraform | Agent-based ticket classification, routing, and remediation |
| [Agents Audit System](https://github.com/jonathanscholtes/Azure-AI-Foundry-Agents-Audit) | Foundry Agent Service, Azure OpenAI, AI Search, Cosmos DB | Python, FastMCP, Bicep | Agentic Accounts Payable auditing with RAG, explainable reasoning, and policy compliance |

### 🏗️ Platform & Scale Patterns

| Project | Services | Tech Stack | Pattern & Use Case |
|---|---|---|---|
| [MCP YARP Gateway](https://github.com/jonathanscholtes/mcp-yarp-gateway) | AKS, Cosmos DB, Key Vault, Managed Identity | .NET, YARP, Bicep, Python | Secure MCP reverse proxy and controlled agent tool access |
| [Large Document Summarization](https://github.com/jonathanscholtes/Azure-AI-Large-Document-Summarization) | Azure OpenAI, Durable Functions, Blob Storage | Python, Bicep, PowerShell | Distributed fan-out/fan-in processing for large documents |
| [Microsoft Foundry Deployment](https://github.com/jonathanscholtes/Azure-AI-Foundry-Deployment) | Microsoft Foundry, AI Search, Private Endpoints, Managed Identity | Bicep, PowerShell | Enterprise deployment, networking, and security foundations |

---

## 📰 Deep Dives & Engineering Articles

I write regularly about the operational realities of AI engineering, focusing on reliability, session affinity, and self healing pipelines over speculation.

👉 **Read the latest technical breakdowns at [stochasticcoder.com](https://stochasticcoder.com)**

> ### 📌 Core Engineering Philosophy
> *   **System Design > Isolated Prompts:** Prompts are brittle; architectures must be resilient.
> *   **Governed Autonomy:** Agents must operate within explicit operational guardrails.
> *   **Consistent Operational Outcomes:** Observability and reliable tracing are non negotiable for production agent deployment.

---

## 🔗 Microsoft Enterprise AI Ecosystem

The architecture patterns above leverage these core Microsoft frameworks and concepts to build scalable, production ready systems:

*   **[Microsoft Agent Framework Journey](https://learn.microsoft.com/en-us/agent-framework/journey/)**: The architectural pathway for transitioning from basic AI capabilities to governed multi agent orchestration.
*   **[Microsoft Foundry Planning](https://learn.microsoft.com/en-us/azure/foundry/concepts/planning)**: Core concepts for designing structured, tool driven execution and deterministic agent planning loops.
*   **[Microsoft Foundry Observability](https://learn.microsoft.com/en-us/azure/foundry/concepts/observability)**: Foundational practices for tracing execution flow, evaluating decisions, and driving consistent operational outcomes across AI applications.
