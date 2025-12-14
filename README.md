# 🌟 query routing and query decomposition
<a name="top"></a> ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen) ![Last Updated](https://img.shields.io/badge/Last%20Updated-Dec%2014,%202025-blue)


*Hope to maintain a curated query routing and query decomposition paper repository, collecting recent high-quality research in rag or related topics. It aims to help researchers and practitioners stay updated with cutting-edge trends.*

# query routing
## 🗓️ 2025

- [Causal LLM Routing: End-to-End Regret Minimization from Observational Data](https://arxiv.org/abs/2505.16037) (2025-12-03)(NIPS 2025)<br>*It proposes a unified, end-to-end LLM routing framework that minimizes expected regret directly—integrating performance estimation and routing decision into a single objective, and enables training solely from observational data without requiring costly full-feedback annotations* 

- [Firewall Routing: Blocking Leads to Better Hybrid Inference for LLMs](https://aclanthology.org/2025.emnlp-main.331/) (2025-11)(EMNLP 2025)<br>*Multi-sample pass rates + soft-label + cope with long-tail*  

- [Let the LLM Stick to Its Strengths: Learning to Route Economical LLM](https://openreview.net/forum?id=uC3DI4YPRv) (2025-10-29)(NIPS 2025)<br>*Refactor llm routing as recommendation task, considering more features and extract high-order interactions*  

- [Router-R1: Teaching LLMs Multi-Round Routing and Aggregation via Reinforcement Learning](https://arxiv.org/abs/2506.09033) (2025-10-24)(NIPS 2025)<br>*Router-R1 firstly introduce iterative, multi-round routing, using a small LLM (rl trained) as router to iteratively plan and route*  

- [MESS+: Dynamically Learned Inference-Time LLM Routing in Model Zoos with Service Level Guarantees](https://arxiv.org/abs/2505.19947) (2025-10-23)(NIPS 2025)<br>*MESS+ formulate LLM routing as a cost-minimization problem subject to a long-term service-level agreement (SLA) constraint on response satisfaction*

- [RAGRouter: Learning to Route Queries to Multiple Retrieval-Augmented Language Models](https://arxiv.org/abs/2505.23052) (2025-10-17)(NIPS 2025)<br>*It generalizes standard LLM routing to RAG-aware LLM routing, conditioned on both the query and its retrieved documents, under a fixed retrieval setup*

- [Cost-Aware Contrastive Routing for LLMs](https://arxiv.org/abs/2508.12491) (2025-10-08)(NIPS 2025)<br>*CSCR firstly proposes to represent each model via a static, probe-based embedding instead of a learnable embedding (so can add new llms without retraining), with contrastive learning adapted to preserve cost-accuracy trade-offs*

- [BEST-Route: Adaptive LLM Routing with Test-Time Optimal Compute](https://arxiv.org/abs/2506.22716)(2025-06-28)(ICML 2025)<br>*Multi-head match-probability routing + test-time optimal compute*

- [Learning to Route LLMs with Confidence Tokens](https://arxiv.org/abs/2410.13284)(2025-06-19)(ICML 2025)<br>*Fine-tune llm to grasp when to generate two kinds of confidence token + using internal representation to construct confidence to guide routing*

- [A Unified Approach to Routing and Cascading for LLMs](https://arxiv.org/abs/2410.10347)(2025-05-22)(ICML 2025)

- [RouteLLM: Learning to Route LLMs with Preference Data](https://arxiv.org/abs/2406.18665)(2025-02-23)(ICLR 2025)<br>*Chatbot-Arena human-preference bootstrapping*
## 🗓️ 2024
- [RouterDC: Query-Based Router by Dual Contrastive Learning for Assembling Large Language Models](https://arxiv.org/abs/2409.19886)(2024-09-30)(NIPS 2024)<br>*Dual-contrastive query-LLM embedding alignment + sample clustering for routing-assembled LLM inference*

- [Query Routing for Homogeneous Tools: An Instantiation in the RAG Scenario](https://arxiv.org/abs/2406.12429) (2024-09-30)(EMNLP 2024 findings)<br>*Query-performance forecasting + ILP-based batch assignment for cost-performance optimal routing of homogeneous tools in RAG*

- [Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity](https://arxiv.org/abs/2403.14403) (2024-05-28)(NAACL 2024)<br>*Proxy-labeled three-tier router for adaptive retrieval*

- [Optimistic Query Routing in Clustering-based Approximate Maximum Inner Product Search](https://arxiv.org/abs/2405.12207) (2024-05-20)(NIPS 2024)

- [Hybrid LLM: Cost-Efficient and Quality-Aware Query Routing](https://arxiv.org/abs/2404.14618)(2024-04-22)(ICLR 2024)<br>*BART-scored soft-label routing (classical)*

# query decomposition
## 🗓️ 2025
- [Question Decomposition for Retrieval-Augmented Generation](https://arxiv.org/abs/2507.00355)(2025-07-01)ACL 2025 Workshop)<br>*Decompose the query(using prompt) to expand retrieval results*

- [POQD: Performance-Oriented Query Decomposer for Multi-vector retrieval](https://arxiv.org/abs/2505.19189)(2025-06-01)(ICML 2025)<br>*Optimize the prompt for decomposing query by a llm (zero-order optimization)*

## 🗓️ 2024
- [Decomposition Dilemmas: Does Claim Decomposition Boost or Burden Fact-Checking Performance?](https://arxiv.org/abs/2411.02400)(2024-10-17)(NAACL 2025)

- [Triples as the Key: Structuring Makes Decomposition and Verification Easier in LLM-based TableQA](https://openreview.net/forum?id=UwcZEoNP19)(2024-10-04)(ICLR 2025)<br>*Extract triples from query to constrain the query decomposition and verification*

- [Chain-of-Question: A Progressive Question Decomposition Approach for Complex Knowledge Base Question Answering](https://aclanthology.org/2024.findings-acl.283/)(2024-08)(ACL 2024 findings)<br>*Progressive question decomposition with dependency-aware chain-of-question prompting*

- [RA-ISF: Learning to Answer and Understand from Retrieval Augmentation via Iterative Self-Feedback](https://arxiv.org/abs/2403.06840)(2024-06-06)(ACL 2024 findings)

- [AutoAct: Automatic Agent Learning from Scratch for QA via Self-Planning](https://arxiv.org/abs/2401.05268)(2024-05-26)(ACL 2024)<br>*Self-synthesized planning trajectories + division-of-labor sub-agents + annotation-free*


