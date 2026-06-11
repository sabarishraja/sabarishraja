# Sabarish Raja

**Data & AI Engineer** · MS in Data Science @ Illinois Institute of Technology, Chicago

I build data platforms and AI systems that turn messy, multi-source data into answers people can actually use — automated analytics pipelines, LLM-powered query layers, and agentic applications with real engineering discipline behind them (schema design, idempotent syncs, evals, CI).

---

## What I work on

- **Data pipelines & warehousing** — API ingestion (GA4, Search Console, Meilisearch), idempotent upserts, scheduled syncs with GitHub Actions, PostgreSQL/Supabase modeling
- **LLM application engineering** — text-to-SQL query engines, structured vision extraction, prompt caching, multi-step agent orchestration with the Claude API
- **Full-stack AI products** — FastAPI backends, React/Expo clients, Supabase Edge Functions as secure AI proxies (API keys never touch the client)

---

## Featured work

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Data Intelligence Platform**](https://github.com/sabarishraja/StC-date-blend-project) | Natural-language analytics for a climate-education nonprofit: blends Google Analytics 4, Search Console, and Meilisearch site-search data into Supabase, then lets non-technical staff ask plain-English questions. Claude generates guarded, read-only SQL (CTE pre-aggregation rules, strict date windows) and summarizes results. Daily GitHub Actions cron keeps data current. | Python · FastAPI · Supabase (PostgreSQL) · Claude API · GA4/GSC APIs · GitHub Actions |
| [**CanterburyGPT**](https://github.com/sabarishraja/MedievalTransformer) | A GPT-style transformer language model written from scratch in PyTorch — multi-head self-attention, positional embeddings, training + fine-tuning for style-conditioned generation (Middle English ↔ Victorian drama), evaluated with perplexity, ROUGE, and BERTScore. | PyTorch · Python |
| **Agentic Video Pipeline** *(private — happy to demo)* | Turns a product URL into a finished marketing video: CrewAI agents on Claude write the script, a schema-constrained director model plans scenes, Vertex AI (Imagen, Veo, TTS) generates assets, and a React/Remotion renderer composites the final MP4 — with human-in-the-loop checkpoints before every paid generation step and a fully mocked pytest suite in CI. | Python · CrewAI · Claude · Vertex AI · Remotion (React/TS) |
| **StyleSense** *(private — happy to demo)* | AI wardrobe app: photograph a garment and Claude vision classifies it into structured relational data (typed schema, CHECK constraints, RLS-enforced isolation) via a Supabase Edge Function proxy, then composes outfit suggestions from your closet. | Expo/React Native · Supabase · Claude vision · Deno Edge Functions |

---

## Tech I use

**Languages** — Python · TypeScript/JavaScript · SQL

**Data & Backend** — FastAPI · Supabase / PostgreSQL · REST API ingestion (GA4, Search Console) · GitHub Actions (CI + scheduled jobs) · pandas

**AI / ML** — Claude API (tool use, vision, prompt caching) · PyTorch · CrewAI · Vertex AI (Gemini, Imagen) · text-to-SQL · structured output & eval design

**Frontend & Mobile** — React · Expo / React Native · Vite

---

## GitHub stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=sabarishraja&show_icons=true&theme=default&rank_icon=github&hide_border=true" height="160" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sabarishraja&layout=compact&hide_border=true&langs_count=6" height="160" alt="Top languages" />
</p>

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sabarishraja03-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sabarishraja03)
[![Medium](https://img.shields.io/badge/Medium-@sabarishds03-12100E?logo=medium&logoColor=white)](https://medium.com/@sabarishds03)
[![Email](https://img.shields.io/badge/Email-skarthikeyan1@hawk.illinoistech.edu-EA4335?logo=gmail&logoColor=white)](mailto:skarthikeyan1@hawk.illinoistech.edu)

Open to Data Engineering, AI Engineering, and ML platform roles.
