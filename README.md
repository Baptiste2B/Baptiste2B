<img src="https://capsule-render.vercel.app/api?type=rect&height=180&color=0B2A33&text=Baptiste%20Audroin&fontColor=F2EFE8&fontSize=52&fontAlign=22&fontAlignY=44&desc=Co-founder%20%26%20CTO%2C%20Kairo%20AI&descSize=18&descAlign=17&descAlignY=72" width="100%"/>

<a href="https://github.com/Baptiste2B">
  <img src="https://readme-typing-svg.demolab.com?font=Work+Sans&weight=500&size=22&pause=1400&color=0B7A75&vCenter=true&width=560&height=40&lines=Generative+AI+research;Harness+engineering;Agentic+AI" alt="Generative AI research, Harness engineering, Agentic AI"/>
</a>

AI Product Engineer based in Corsica, France.
I build AI products that run in the real world: on real maps, for real local businesses, on European infrastructure.

<br/>

## Research focus

![Generative AI](https://img.shields.io/badge/Generative_AI-0B2A33?style=flat-square)
![Harness Engineering](https://img.shields.io/badge/Harness_Engineering-0B2A33?style=flat-square)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-0B2A33?style=flat-square)
![Model Routing](https://img.shields.io/badge/Model_Routing-0B2A33?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0B2A33?style=flat-square)
![LLM Evaluation](https://img.shields.io/badge/LLM_Evaluation-0B7A75?style=flat-square)

I work on what sits around the model: the loop, the tools, the router, the judge, the guardrails. Most of the reliability of an AI product lives there.

### Sovereign model routing
Can a router pick the right open-weight model per task, and beat a single large model?
- A small sovereign model (**Qwen-32B**) matched or beat **Llama-70B** for **~42% of the cost, 2× faster**, cross-validated.
- Negative result, kept on record: a multi-pass **AB-MCTS** orchestration loop brought **no measurable value** on short, factual, grounded tasks. Routing did the work, not the loop.
- Next question, falsifiable: does a router **learned on real field traces** beat a generic one, and by how much?

### Agentic AI
- In-house **ReAct** agent loop, orchestration migrated to **LangGraph**.
- **Read-only sovereign agent mode**: public-data tools behind a domain allowlist, every outbound call counted and traced.
- **Human-in-the-loop** design for write actions: propose, pause, approve out of band, resume.

### Harness engineering
- Hard quota caps, org-isolated retrieval, hash-chained audit log, per-run agent logs.
- Deterministic by design where it matters: figures computed in code, the LLM only interprets.
- Shipping with parallel coding-agent sessions as a daily engineering workflow.

### Retrieval (RAG)
- Embedding benchmark on French content: **multilingual-e5-base** at **NDCG@10 0.945** vs **0.527** for MiniLM.
- A cross-encoder reranker consistently **degraded** results on this corpus, so it stays off.
- Per-organization vector isolation with verifiable citations.

### LLM evaluation
- LLM judges are **non-deterministic on borderline cases**, even at temperature 0.
- Offline fix: **reference-based judging** against gold answers.
- Open problem: production reward signals are noisy, and must be fixed before any learned router ships.

<br/>

## Now

> [!NOTE]
> **KairoMap is live since June 15, 2026.**
> A hyperlocal AI map for Corsican commerce and tourism, built on a retrieval (RAG) layer and served from sovereign OVH infrastructure. One platform, two audiences: professionals who publish, and people who search.
>
> Under the hood: three proprietary agents, **Atlas**, **Cadence** and **Prisme**.

<br/>

## Stack

<img src="https://skillicons.dev/icons?i=ts,python,react,nextjs,nodejs,fastapi,django,postgres,redis,docker,linux,aws&perline=12" alt="Tech stack"/>

<br/><br/>

![PyTorch](https://img.shields.io/badge/PyTorch-0B2A33?style=flat-square&logo=pytorch&logoColor=F2EFE8)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0B2A33?style=flat-square&logo=tensorflow&logoColor=F2EFE8)
![LangChain](https://img.shields.io/badge/LangChain-0B2A33?style=flat-square&logo=langchain&logoColor=F2EFE8)
![LangGraph](https://img.shields.io/badge/LangGraph-0B2A33?style=flat-square&logo=langchain&logoColor=F2EFE8)
![Qdrant](https://img.shields.io/badge/Qdrant-0B2A33?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-0B2A33?style=flat-square&logo=postgresql&logoColor=F2EFE8)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0B2A33?style=flat-square&logo=scikitlearn&logoColor=F2EFE8)
![OpenCV](https://img.shields.io/badge/OpenCV-0B2A33?style=flat-square&logo=opencv&logoColor=F2EFE8)
![pandas](https://img.shields.io/badge/pandas-0B2A33?style=flat-square&logo=pandas&logoColor=F2EFE8)
![NumPy](https://img.shields.io/badge/NumPy-0B2A33?style=flat-square&logo=numpy&logoColor=F2EFE8)

<br/>

## Central

> [!TIP]
> **Central by Kairo AI**
> Sovereign AI infrastructure for companies. One entry point, the right open-weight model for each task, and every request processed in France.
>
> *Sovereign by design, not by option.*

<br/>

<sub>Building from Corsica, for Europe.</sub>
