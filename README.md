### Hey, I'm Eugene

  I'm building [**Tessera**](https://tesseraai.io) — a programmable gateway that sits between your code and OpenAI / Anthropic / Mistral / Groq / Cohere, auto-routing requests to cheaper-equivalent models, caching the obvious repeats, compressing prompts losslessly, and
  arbitraging async traffic onto batch APIs.

  You install the SDK, your existing code runs unchanged, and your LLM bill drops 20-40% on real workloads. We charge 20% of measured savings. If we save you nothing, you pay nothing.

  **Free tier:** 60M tokens/month, no card up front. Built for solo devs, side projects, hobbyists who want production-grade infra without a procurement conversation.

  #### What I work on

  - **[tessera-sdk](https://github.com/tessera-llm/tessera-sdk)** — drop-in patcher for `openai`, `anthropic`, `mistralai`, `groq`, `cohere` clients (Python + Node)
  - **Framework adapters** — [LangChain](https://github.com/tessera-llm/tessera-langchain), [Vercel AI SDK](https://github.com/tessera-llm/tessera-vercel-ai), [LlamaIndex](https://github.com/tessera-llm/tessera-llamaindex),
  [Mastra](https://www.npmjs.com/package/@tessera-llm/mastra), [Pydantic AI](https://pypi.org/project/tessera-pydantic-ai/), [CrewAI](https://pypi.org/project/tessera-crewai/), [AutoGen](https://pypi.org/project/tessera-autogen/)
  - **The proxy itself** — 11 production mechanics with per-stack quality canary auto-rollback, audit-immutable pricing snapshots

  #### Background

  Finance background before AI infrastructure. The pricing model (`20% of measured savings`) and the audit-immutability discipline (every dollar number traces back to a pricing snapshot uuid) come from that side of my career — cost work is more credible when the person doing the
  math has done it on someone else's money first.

  Solo right now. Looking for a technical co-founder for the next phase. If you're interested in AI request infrastructure as a category — let's talk.

  #### Find me

  - **Email:** founder@tesseraai.io
  - **Site:** [tesseraai.io](https://tesseraai.io) · [tesseraai.io/dev](https://tesseraai.io/dev) · [tesseraai.io/blog](https://tesseraai.io/blog)

  Tessera is operated by Fintechagency OÜ, Tallinn, Estonia (registry 16638667).
