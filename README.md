# Project: Personal AI Job Application Assistant

> A practical project to help you switch your career to AI engineering — while literally helping your own job search.

## Why This Project?

- **Self-serving** — literally helps your own career switch
- **Deeply practical** — covers the full AI engineer stack
- **Rich in complexity** — RAG, agents, evals, all naturally fit
- **Impressive to demo** — recruiters *will* ask about it

---

## 🟢 Phase 1 — Vibe Coding (Week 1–2)
*Goal: Get something working fast, feel the momentum*

- [ ] Scaffold a basic Python CLI app with Claude Code
- [ ] Accept a job description (URL or paste) as input
- [ ] Accept your resume as a PDF input
- [ ] Send both to Claude API, get a fit analysis back ("you match 7/10 requirements")
- [ ] Print a gap analysis — what you have vs what they want
- [ ] Save output to a markdown file
- [ ] **Learn**: Claude API basics, PDF handling, fast prototyping

---

## 🟡 Phase 2 — Prompt Engineering (Week 3–4)
*Goal: Make the outputs genuinely useful, not generic*

- [ ] Write a structured system prompt defining Claude as a "senior tech recruiter"
- [ ] Extract structured data from job descriptions (skills, seniority, tech stack, red flags)
- [ ] Generate a **tailored cover letter** matched to the specific job
- [ ] Generate **suggested resume bullet rewrites** to better match the JD language
- [ ] Add a "tone detector" — is this company formal, startup casual, etc.
- [ ] Experiment with chain-of-thought prompting for better reasoning
- [ ] **Learn**: persona prompting, structured extraction, output shaping

---

## 🟠 Phase 3 — RAG & Memory (Week 5–7)
*Goal: Give the assistant long-term knowledge about you*

- [ ] Build a **personal knowledge base** — upload past projects, skills, achievements
- [ ] Chunk and embed documents using Claude or an embedding model
- [ ] Store embeddings in a local vector DB (ChromaDB or pgvector)
- [ ] Implement **retrieval** — pull relevant experience when analysing a job
- [ ] Let Claude reference your actual past work in cover letters automatically
- [ ] Add a "learn from feedback" loop — mark which applications got responses
- [ ] **Learn**: RAG architecture, embeddings, vector search, memory patterns

---

## 🔴 Phase 4 — Agentic Workflows (Week 8–10)
*Goal: The assistant takes actions, not just gives advice*

- [ ] Give Claude a `search_linkedin_jobs` tool (via LinkedIn API or scraping)
- [ ] Give Claude a `score_job_fit` tool that returns a structured fit score
- [ ] Build a daily agent that finds 5 relevant jobs and ranks them for you
- [ ] Give Claude a `draft_outreach_message` tool for LinkedIn cold messages
- [ ] Build a **multi-step agent loop**: search → score → draft → save → notify
- [ ] Add human-in-the-loop confirmation before any message is sent
- [ ] **Learn**: tool use, agent loops, human-in-the-loop design

---

## 🔴 Phase 5 — Harness Engineering (Week 11–13)
*Goal: Measure and prove your system actually works*

- [ ] Build an eval dataset — 20 job descriptions with manually scored fit levels
- [ ] Write automated scoring — does Claude's fit score match your human score?
- [ ] A/B test prompt versions, track which generates better cover letters
- [ ] Add **observability** — log every API call, token usage, latency, cost
- [ ] Add **regression tests** — ensure prompt changes don't break output quality
- [ ] Track application outcomes (applied → response → interview → offer)
- [ ] Use outcome data to improve the scoring model over time
- [ ] **Learn**: evals, LLMOps, feedback loops, cost optimisation

---

## 🟣 Phase 6 — Scale & Polish (Week 14+)
*Goal: Ship it like a real product*

- [ ] Build a simple web UI (Next.js) — dashboard of all tracked applications
- [ ] Add a browser extension to analyse any job page in one click
- [ ] Implement a weekly email digest of top matched jobs
- [ ] Add **multi-user support** — could become a real SaaS
- [ ] Write architecture docs and a public README
- [ ] Deploy on Railway or Fly.io
- [ ] Open source it — this is your portfolio centrepiece
- [ ] **Learn**: full-stack integration, deployment, product thinking

---

## Skills Mapped to Phases

| Phase | Skills Gained |
|---|---|
| Vibe Coding | Claude API, PDF parsing, fast prototyping |
| Prompt Engineering | Structured extraction, persona prompting, chain-of-thought |
| RAG & Memory | Embeddings, vector DBs, retrieval, knowledge management |
| Agentic Workflows | Tool use, agent loops, human-in-the-loop |
| Harness Engineering | Evals, observability, regression testing, LLMOps |
| Scale & Polish | Full-stack, deployment, open source, SaaS thinking |

---

## Why This Beats a Generic Tutorial

| Generic Tutorial | This Project |
|---|---|
| Fake dataset | Real data — your own resume & jobs |
| No stakes | High stakes — your actual career |
| Isolated concepts | Every AI concept connected end-to-end |
| Nothing to show | Deployable product + rich GitHub repo |

---

## The Meta-Advantage

By the time you finish, you can walk into any AI engineer interview and say:

> *"I built a RAG-based agentic system with evals and observability, and I used it to land this interview."*

That's a story no bootcamp can give you.
