<div align="center">

# Awesome AI Commerce [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### A curated list of AI agents, automation & tooling for e-commerce and small businesses 🛍️🤖

*From conversational commerce to agent frameworks, Shopify AI to autonomous support — the best tools, libraries, and resources for building AI into how businesses sell, support, and source.*

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

</div>

> **Why this list?** AI is reshaping how small and medium businesses sell, support, and source — but the tooling is scattered across app stores, GitHub, and blog posts. This list pulls the best of it into one place, with a bias toward things builders can actually use. Contributions welcome!
>
> ⭐ **Star this repo** to bookmark it and help other builders find it.
>
> 🛠️ = open source · 💰 = commercial/SaaS · 🧩 = framework/library

## Contents

- [AI Agent Frameworks](#ai-agent-frameworks)
- [Conversational Commerce](#conversational-commerce)
- [Customer Support Automation](#customer-support-automation)
- [Voice AI](#voice-ai)
- [Shopify & Storefront AI](#shopify--storefront-ai)
- [Open-Source Commerce Platforms](#open-source-commerce-platforms)
- [Product Media & Imagery](#product-media--imagery)
- [Content & Marketing](#content--marketing)
- [Sales & Lead Generation](#sales--lead-generation)
- [Sourcing & Supply Chain](#sourcing--supply-chain)
- [Inventory & Demand Forecasting](#inventory--demand-forecasting)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

## AI Agent Frameworks

*Building blocks for autonomous and multi-agent commerce workflows.*

- 🧩🛠️ [LangGraph](https://github.com/langchain-ai/langgraph) — Stateful, graph-based orchestration for multi-step and multi-agent workflows; part of the LangChain ecosystem.
- 🧩🛠️ [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent framework in Python; fast path to a "crew" of collaborating agents.
- 🧩🛠️ [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for building agents over your own private documents and product data.
- 🧩🛠️ [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Lightweight framework for single- and multi-agent apps; a simple starting point.
- 🧩🛠️ [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) — Microsoft's consolidated successor to AutoGen + Semantic Kernel, for .NET and Python teams.
- 🧩🛠️ [Dify](https://github.com/langgenius/dify) — Open-source LLM app platform with a visual builder for agents and workflows; self-hostable.
- 🧩🛠️ [Flowise](https://github.com/FlowiseAI/Flowise) — Drag-and-drop UI to build LLM apps and agents visually; great for non-heavy-code teams.
- 🧩🛠️ [n8n](https://github.com/n8n-io/n8n) — Workflow automation with native AI/LLM nodes; wire agents into hundreds of business apps.
- 🛠️ [Specialist Swarm](https://github.com/Manish567Kumar/specialist-swarm) — A coordinator agent that fans an RFP out to specialist sub-agents and returns a finished branded proposal.

## Conversational Commerce

*Chat & messaging automation that sells and supports.*

- 🛠️ [BizBot](https://github.com/Manish567Kumar/bizbot) — Open-source WhatsApp automation for SMBs: auto-reply, bot flows, and a shared inbox (TypeScript, Express, Prisma, BullMQ).
- 🛠️ [Chatwoot](https://github.com/chatwoot/chatwoot) — Open-source customer engagement suite; omnichannel inbox (WhatsApp, IG, web) with automation and AI add-ons.
- 🛠️ [Typebot](https://github.com/baptisteArno/typebot.io) — Open-source conversational form/chatbot builder you can embed or run on WhatsApp.
- 💰 [Manychat](https://manychat.com/) — Popular no-code chat marketing for Instagram, WhatsApp, and Messenger.

## Customer Support Automation

*Agentic tools that resolve tickets end-to-end — orders, returns, WISMO — across chat, email, and messaging.*

- 💰 [Gorgias](https://www.gorgias.com/) — Ecommerce-native helpdesk with AI automation and deep Shopify order actions.
- 💰 [Intercom (Fin)](https://www.intercom.com/fin) — AI agent that resolves support conversations across channels.
- 💰 [Tidio](https://www.tidio.com/) — Chat + AI support widget popular with small stores.
- 💰 [Re:amaze](https://www.reamaze.com/) — Helpdesk + chat with AI replies, aimed at SMB stores.
- 🛠️ [Basjoo](https://github.com/haoyiyin/basjoo) — Open-source AI support platform: RAG knowledge base, multi-provider LLM agents, embeddable chat widget (FastAPI + Next.js + pgvector).

## Voice AI

*Give an agent a phone number — for support lines, order status, or outbound calls.*

- 🧩🛠️ [Vocode](https://github.com/vocodedev/vocode-core) — Open-source library for building real-time voice LLM agents over phone, Zoom, and more.
- 🧩🛠️ [Bolna](https://github.com/bolna-ai/bolna) — End-to-end open-source framework for production voice agents (ASR + LLM + TTS over websockets).
- 🛠️ [Patter](https://github.com/PatterAI/Patter) — MIT-licensed voice-AI SDK; give an agent a phone number in a few lines (Twilio, Telnyx, Plivo).
- 🛠️ [BentoVoiceAgent](https://github.com/bentoml/BentoVoiceAgent) — Phone-calling voice agent built fully on open-source models (Pipecat + BentoML + Twilio).

## Shopify & Storefront AI

- 💰 [Shopify Magic / Sidekick](https://www.shopify.com/magic) — Shopify's built-in AI for product descriptions and store assistance.
- 🛠️ [Shopify Liquid Cookbook](https://github.com/Manish567Kumar/shopify-liquid-cookbook) — Copy-paste Liquid theme customizations, no apps required.
- 💰 [Describely](https://describely.ai/) — Bulk AI product descriptions, titles, and metadata for large catalogs.
- 💰 [Octane AI](https://www.octaneai.com/) — Quizzes and AI-driven personalization for Shopify stores.

## Open-Source Commerce Platforms

*Own your stack — headless/composable engines you can build AI directly into.*

- 🛠️ [Medusa](https://github.com/medusajs/medusa) — Flexible open-source commerce platform (Node.js) with a customization framework for agents and developers.
- 🛠️ [Saleor](https://github.com/saleor/saleor) — High-performance, GraphQL-native, headless commerce API (Python/Django).
- 🛠️ [Vendure](https://github.com/vendure-ecommerce/vendure) — Headless commerce framework built with TypeScript, NestJS, and GraphQL.
- 🛠️ [Svelte Commerce](https://github.com/itswadesh/svelte-commerce) — Open-source headless storefront for Medusa, Shopify, Saleor, Vendure, and WooCommerce.

## Product Media & Imagery

*Turn raw product shots into clean, on-brand catalog images at scale.*

- 🛠️ [rembg](https://github.com/danielgatis/rembg) — Popular open-source tool/library to remove image backgrounds; scriptable for bulk catalogs.
- 💰 [Photoroom](https://www.photoroom.com/) — AI background removal and product-scene generation, strong at batch processing.
- 💰 [remove.bg](https://www.remove.bg/) — Fast, accurate single-image background removal with an API.
- 💰 [Kive](https://kive.ai/) — Re-renders products into consistent studio scenes across a whole catalog.

## Content & Marketing

*AI copy, creative, and campaign tooling for commerce.*

- 🛠️ [Mautic](https://github.com/mautic/mautic) — Open-source marketing automation (email, campaigns, segmentation); self-hosted.
- 💰 [Omnisend](https://www.omnisend.com/) — Email + SMS marketing built for ecommerce, with AI assist.
- 💰 [Klaviyo](https://www.klaviyo.com/) — Ecommerce marketing with best-in-class predictive/AI data.
- 💰 [Brevo](https://www.brevo.com/) — Budget-friendly email + SMS automation for small businesses.

## Sales & Lead Generation

*Agents that find, qualify, and reach out to buyers.*

- 🛠️ [SalesGPT](https://github.com/filip-michalsky/SalesGPT) — Context-aware AI sales agent that engages leads across voice, email, SMS, and WhatsApp.
- 🛠️ [OpenOutreach](https://github.com/eracle/OpenOutreach) — Self-hosted open-source AI lead finder that qualifies prospects and exports a CSV for your cold-email tool.

## Sourcing & Supply Chain

*AI for supplier discovery, RFQ automation, and trade — a fast-growing frontier.*

- 🛠️ [Specialist Swarm](https://github.com/Manish567Kumar/specialist-swarm) — Multi-agent RFP/proposal automation (a sourcing-adjacent pattern: coordinator + specialists).
- _Seed this section — supplier discovery, RFQ/RFP automation, logistics agents. PRs very welcome._

## Inventory & Demand Forecasting

*Predict demand, automate reorders, cut stockouts and overstock.*

- 🛠️ [Inventory Management](https://github.com/Manish567Kumar/inventory-management) — Factory inventory management system.
- 💰 [Prediko](https://www.prediko.io/) — AI forecasting and Shopify-native replenishment workflows.
- 💰 [Inventory Planner](https://www.inventory-planner.com/) — Demand forecasting and purchase-order automation for ecommerce.
- 💰 [Monocle](https://apps.shopify.com/forecast) — ML-based reorder suggestions and PO automation for Shopify.

## Learning Resources

- 📚 [Anthropic — Managed Agents (multi-agent)](https://platform.claude.com/docs/en/managed-agents/multi-agent) — Docs for building coordinator/specialist agent systems.
- 📚 [LangChain — AI agent frameworks guide](https://www.langchain.com/resources/ai-agent-frameworks) — Overview of the current framework landscape.
- 📚 [Shopify — AI content creation](https://www.shopify.com/blog/ai-content-creation) — Practical guide to AI tooling for stores.
- 📚 [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — The master index of awesome lists across every topic.

## Contributing

Contributions make this list great! Please read [CONTRIBUTING.md](CONTRIBUTING.md), then open a PR.

**Quick rules:**
- One tool per line: `[Name](link) — one-line description.`
- Mark it 🛠️ open source · 💰 commercial · 🧩 framework where it helps
- Keep it genuinely useful and commerce/AI relevant
- Alphabetical within a section where possible
- No broken links, no pure self-promo spam

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, contributors have waived all copyright and related rights to this work.
