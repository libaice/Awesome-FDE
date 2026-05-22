# Awesome-FDE

![Awesome](https://awesome.re/badge.svg)

[![Stars](https://img.shields.io/github/stars/yourname/awesome-fde?style=social)](https://github.com/libaice/awesome-fde)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#license)

[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](#contributing)



> A curated list of resources, companies, skills, and interview preparation materials for 
>
> **Forward Deployed Engineers (FDEs)**.



This repo is for engineers who want to understand or transition into Forward Deployed Engineering — especially builders coming from crypto, blockchain, fintech, infrastructure, or backend engineering backgrounds.



FDE is becoming one of the most important roles in the AI era: part software engineer, part technical consultant, part product thinker, and part field operator.



## Table of Contents



[What is a Forward Deployed Engineer?](#what-is-a-forward-deployed-engineer)

[Companies Hiring FDEs (2026)](#companies-hiring-fdes-2026)

[Core Skills Required](#core-skills-required)

[The FDE Interview](#the-fde-interview)

[Resources](#resources)

[From Crypto/Blockchain to FDE](#from-cryptoblockchain-to-fde)

[Contributing](#contributing)

[License](#license)







## What-is-a-forward-deployed-engineer

A **Forward Deployed Engineer (FDE)** is an engineer who works close to customers, often inside or alongside customer teams, to build, integrate, deploy, and iterate on technical solutions in real-world environments. 

The role is most famously associated with [**Palantir**](https://www.palantir.com/), where [Forward Deployed Software Engineers](https://en.wikipedia.org/wiki/Forward_Deployed_Engineer) helped deploy Gotham and Foundry into complex government and enterprise workflows.

 In the AI era, companies like [**OpenAI**](https://openai.com/careers/search/?q=forward+deployed+engineer), [**Anthropic**](https://job-boards.greenhouse.io/anthropic/jobs/4985877008), [**Scale AI**](https://scale.com/careers/4593571005), and many enterprise AI startups are adopting similar models to help customers turn frontier AI capabilities into production systems.



Unlike a traditional **Software Engineer**, an FDE does not only work from a predefined ticket queue. 

Unlike a traditional **Solutions Engineer**, an FDE usually writes production code, designs system architecture, debugs data and integration issues, and owns delivery outcomes. 

The role lives at the intersection of engineering, customer delivery, and product feedback.



```text
Engineering + Consulting + Product Thinking = Forward Deployed Engineering
```

The core capability triangle is: **Engineering** (you can build it) × **Consulting** (you can diagnose the real problem) × **Product Thinking** (you know what's worth building). 

Most people are strong in one or two — FDEs need to be functional in all three. 

Compensation reflects this rarity: in 2026, Palantir FDE total comp averages around **$238K**, while AI-lab FDE roles at OpenAI and Anthropic range from **$350K to $550K+ TC**, with equity being a significant portion at growth-stage companies.





## **Companies Hiring FDEs (2026)**

###  AI Labs

| Company                                            | Notes                                                        |
| -------------------------------------------------- | ------------------------------------------------------------ |
| **[Anthropic](https://www.anthropic.com/careers)** | FDE roles focused on Claude enterprise deployments; strong emphasis on safety-aware implementations |
| **[OpenAI](https://openai.com/careers)**           | One of the largest FDE programs in AI; covers GPT/Assistants API enterprise rollouts |
| **[Cohere](https://cohere.com/careers)**           | Strong FDE culture; enterprise NLP deployments, often in regulated industries |
| **[Mistral](https://mistral.ai/careers)**          | Smaller team, high ownership; European enterprise focus      |



### AI Application Companies

| Company                                     | Notes                                                        |
| ------------------------------------------- | ------------------------------------------------------------ |
| **[Scale AI](https://scale.com/careers)**   | FDE + data program hybrid; heavy on evaluation and fine-tuning deployments |
| **[Glean](https://glean.com/careers)**      | Enterprise search/RAG; FDE role is central to onboarding Fortune 500 customers |
| **[Harvey](https://www.harvey.ai/careers)** | Legal AI; FDE works directly with BigLaw firms and in-house counsel teams |
| **[Writer](https://writer.com/careers)**    | Enterprise content AI; FDEs own end-to-end deployment and model customization |
| **[Sierra](https://sierra.ai/careers)**     | Conversational AI for customer service; FDEs build and tune customer-facing agents |
| **[Decagon](https://decagon.ai/careers)**   | AI customer support agents; small team, high-impact deployments |
| **[Hebbia](https://www.hebbia.ai/careers)** | Document intelligence for finance and law; FDEs deeply embedded with clients |
| **[Cresta](https://cresta.com/careers)**    | Real-time AI coaching for contact centers; FDEs own integration with telephony stacks |

### Enterprise / Legacy

| Company                                           | Notes                                                        |
| ------------------------------------------------- | ------------------------------------------------------------ |
| **[Palantir](https://www.palantir.com/careers/)** | The originator of the FDE model; Gotham/Foundry/AIP deployments; notoriously rigorous hiring |
| **[Anduril](https://www.anduril.com/careers/)**   | Defense tech; FDE equivalent embedded with military and government customers |
| **[Rippling](https://www.rippling.com/careers)**  | HR/IT/Finance platform; FDE-style roles for complex enterprise onboarding |

### China / Asia

This region deserves serious attention. FDE-equivalent roles are growing rapidly across APAC, though they're often listed under different titles.

| Company                                                      | Notes                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **[OKX](https://www.okx.com/zh-hans/join-us/openings)**      | Shenzhen / Hong Kong; <br />actively building AI + crypto infrastructure; <br />roles blend Web3 systems knowledge with LLM deployment — a strong fit for crypto engineers pivoting to FDE |
| **[Siemens Energy](https://jobs.siemens-energy.com/)**       | Shanghai; <br />Industrial AI deployments; <br />FDE-style roles focused on predictive maintenance and digital twin integration |
| **Binance / Bybit / Crypto.com / HashKey / Ant Group / Tencent Cloud / Alibaba Cloud** | Often do not use the title “FDE,” but hire adjacent roles such as AI Engineer, AI Solutions Architect, Technical Delivery Engineer, Customer Engineer, AI Implementation Engineer, and GenAI Solution Consultant. |

> In China, the FDE concept is often translated into roles like:
>
> - **解决方案工程师**
> - **AI 实施工程师**
> - **技术交付工程师**
> - **客户成功工程师**
> - **AI 解决方案架构师**
> - **模型部署工程师**





## Core Skills Required

### **Technical**

* **Python proficiency** — Not just scripting; you need to write clean, reviewable, production-safe code that customer engineers will inherit
* **LLM APIs (Anthropic, OpenAI)** — Deep familiarity with prompt engineering, tool use, context management, and rate-limit handling
* **Agent frameworks (LangGraph, LangChain)** — Ability to build stateful multi-step agents; LangGraph is increasingly the standard for production workflows
* **RAG & vector databases** — End-to-end: chunking strategy, embedding selection, retrieval tuning, re-ranking; Pinecone, Weaviate, pgvector
* **REST API & WebSocket integration** — Connecting LLMs to live customer data sources; streaming is often non-negotiable
* **System design for production environments** — Latency, reliability, cost — all three matter; you need to reason about tradeoffs, not just functionality
* **Evaluation frameworks for LLM outputs** — Knowing how to measure whether your solution is actually working (LangSmith, Braintrust, custom evals)

### **Customer-Facing**

- **Translating business requirements into technical specs** — customers describe pain vaguely; FDEs convert it into scope, architecture, and delivery plans.
- **Running discovery calls and workshops** — ask the right questions before writing code.
- **Stakeholder management** — work with end users, engineering teams, security, compliance, legal, managers, and executives.
- **Technical writing and documentation** — write deployment docs, post-deployment reviews, architecture notes, and customer-facing explanations.

###  Mindset

- **Comfort with ambiguity** — The brief will be incomplete. The data will be messy. You go anyway.
- **Self-directed problem solving** — Nobody gives you a ticket; you figure out what the ticket should have been
- **Fast learning under pressure** — You'll be onboarded to a new customer's stack in 48 hours and expected to have opinions
- **Bias toward shipping** — A working solution in the customer's hands beats a perfect solution in your head