# Awesome-FDE

![Awesome](https://awesome.re/badge.svg)

[![Stars](https://img.shields.io/github/stars/libaice/awesome-fde?style=social)](https://github.com/libaice/awesome-fde)

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



## The FDE Interview

This is the most important section of this list. 

FDE interviews are unlike anything in standard SWE hiring, and most people fail not because of technical weakness but because they've never been trained for this format.

### The Palantir-Style Problem

Palantir invented a format now copied by almost every company hiring FDEs.

You're given a **vague, real-world problem** — no data schema, no clear success metric, no defined scope. Examples:

- *"A large hospital system wants to use AI to reduce medication errors. How do you approach this?"*

- *"A hedge fund wants to use LLMs to improve their research process. Where do you start?"*

- *"A logistics company's AI dispatch system has been live for 6 months and adoption is at 30%. What's happening and what do you do?"*

  

The interview is not testing whether you know the right answer. 



It's testing:

> 1. **How you decompose an ambiguous problem** — Do you ask good clarifying questions, or do you charge into assumptions?
> 2. **How you design a solution** — Is your architecture reasonable, or are you over-engineering a toy?
> 3. **How you think about rollout** — Do you understand change management, or only the technical layer?
> 4. **How you measure success** — Can you define a metric that actually maps to the customer's business outcome?



Spend as much time on diagnosis and framing as on the solution. Interviewers are specifically watching to see if you slow down.

### 10 Common FDE Interview Questions

1. Tell me about a time you delivered a technical solution to a non-technical customer. What made it succeed or fail?
2. How would you diagnose why an AI agent is performing poorly in production?
3. A customer says "the AI doesn't work." Walk me through your debugging process, step by step.
4. How do you balance building a fully custom solution versus pushing the customer toward the standard product?
5. You're on-site at a customer and discover their data quality is far worse than they described in the sales process. What do you do?
6. How would you design a RAG system for a law firm's internal document library? What are the failure modes?
7. A customer needs real-time market data feeding into their agent. What architecture would you use and why?
8. How do you handle a customer who wants features that are on the product roadmap but not shipped yet?
9. You shipped a solution last week. How do you actually know it's working?
10. Walk me through how you'd write a post-deployment technical review. What does it contain, and who is it for?



### How to Prepare

- **Build and deploy at least one real agent** — Not a tutorial, not a Jupyter notebook. Something with a real user, real failure modes, and a feedback loop you can talk about. Bonus points if it has a customer (even an internal one).
- **Be able to explain every architecture decision you made** — Not just what you built, but why you made each tradeoff. Why did you use streaming vs. batch? Why this chunk size? Interviewers will probe.
- **Practice the "diagnosis under ambiguity" format** — Take a vague problem (pick one from above), set a 20-minute timer, and structure a response: clarifying questions → root cause hypotheses → proposed solution → success metric. Do this out loud.
- **Have 3 customer/user stories ready** — Even if they're from open source projects, freelance clients, or internal stakeholders at a previous job. The story arc is: situation → what the customer actually needed (vs. what they asked for) → what you built → how you knew it worked.



## Resources

### Learning

- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/) — The go-to framework for building stateful, production-grade agents
- [Anthropic Tool Use Guide](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) — Essential reading for building Claude-powered agentic workflows
- [LangSmith / LLM Evaluation](https://docs.smith.langchain.com/) — Learn how to instrument and evaluate LLM applications in production
- [Anthropic Prompt Engineering Overview](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Solid foundation for prompting at a production level

###  Reading

- *"[The Hottest Tech Role of 2026](https://medium.com/@apoorvdubey757/the-hottest-tech-role-of-2026-forward-deployed-engineer-3b072f600714)"* — Medium (Apoorv Dubey) — Good overview of how the FDE market has evolved
- *"[How to Become a Forward Deployed Engineer in 2026](https://skillscouter.com/how-to-become-a-forward-deployed-engineer/)"* — SkillScouter — Practical career path breakdown
- [Palantir's early engineering blog posts on the FDE model](https://fde.academy/blog/how-palantir-invented-the-forward-deployed-engineer-model) — dated but foundational for understanding the original philosophy

### Job Boards

- **[Wellfound](https://wellfound.com)** — Search "forward deployed engineer"; best coverage of startup FDE roles
- **[LinkedIn](https://linkedin.com)** — Search "FDE" or "forward deployed engineer"; set alerts for new postings
- **[Anthropic Careers](https://www.anthropic.com/careers)** — Direct application; FDE roles listed under "Deployment" or "Applied AI"
- **[OpenAI Careers](https://openai.com/careers)** — Applied Engineering team
- **[Scale AI Careers](https://scale.com/careers)** — Forward Deployed Engineer and Solutions roles



## From Crypto/Blockchain to FDE

If you're coming from crypto — whether you were building DeFi protocols, writing Solidity contracts, running trading infrastructure, or integrating exchange APIs 



**You are a stronger FDE candidate than you probably realize.**

The skills don't translate in obvious ways, but they translate deeply.



**Why the crypto background actually fits:**

* You've shipped production systems where failure has immediate, real-money consequences.

* You haven't worked in "sandbox mode." 

* You've debugged WebSocket feeds at 2am during a market event, integrated underdocumented third-party APIs, and built tools that had to survive adversarial conditions. 

  

**That's exactly the muscle FDE work demands** — except instead of a DeFi protocol going down, it's a customer's AI deployment failing in front of their CEO.

*Crypto engineers also tend to be end-to-end builders.*

You've touched the smart contract, the indexer, the API layer, and the frontend. 

That breadth — even if you're not deep in every layer — is rare and valuable when a customer hands you an unfamiliar tech stack and expects you to have opinions within a week.

Finally, you're used to operating without perfect documentation. You've read EIPs, traced contract bytecode, and figured out how an undocumented protocol actually works by reading the source. That instinct for self-directed, source-level understanding is a direct superpower in FDE work.



### Skills Translation Table

*The key is to translate your experience into language that enterprise AI teams understand.*

| Crypto Background                      | FDE Translation                                              |
| -------------------------------------- | ------------------------------------------------------------ |
| Smart contract development             | Low-level system constraints & security mindset; <br />thinking about what can go wrong, not just what works |
| Order book / matching engine work      | Real-time data pipelines; low-latency architecture; understanding of event ordering and consistency |
| WebSocket feed integration             | Streaming data & event-driven architecture; you already know how to handle connection drops and reconnection logic |
| On-chain monitoring & alerting tools   | Production observability; you've already built the equivalent of a customer's LLM output monitoring system |
| Working with underdocumented protocols | Fast onboarding to new customer tech stacks; you're comfortable reading source code, not waiting for docs |
| Solo builder / open source contributor | End-to-end ownership; you've shipped full systems, not just features inside someone else's codebase |
| Cross-chain integrations               | Multi-system integration; every FDE deployment involves connecting heterogeneous systems that weren't designed to talk to each other |



### The one gap to close:

Most crypto engineers haven't had to explain their systems to non-technical stakeholders at a business level. 

The translation work — from "here's how the mempool works" to "here's why your transaction confirmation time matters for your checkout flow" — is exactly the communication muscle FDE work requires. 
Practice this deliberately. 

Take a system you've built and explain it to someone with no technical background. 

Then explain the business tradeoffs. 

That's the skill to develop.



## Contributing

Contributions are welcome and encouraged. If you:

- Know of a company running an FDE program that isn't listed here
- Have real interview questions to add (especially from non-US companies)
- Want to add resources in languages other than English
- Have a "crypto → FDE" story to share

Please open a PR or file an issue. 

**The goal is for this list to be maintained by people who are actually in or moving toward this role — not scraped from job boards.**

For additions, please follow the existing format and include a brief note on why the resource is valuable.

------

## License

[MIT](LICENSE) © awesome-fde contributors

