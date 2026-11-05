<!-- Status: finished (GitHub profile; reviewed 2026-11-05). -->
# Guillermo Martín de Oliva

**Behavioural data scientist — I build data systems that show their work, so a complex and opaque
reality becomes legible for the people who actually have to act on it.**

What I care about isn't the model — it's whether the output can be *trusted*: does it cite its
source, does it know how sure it is, and does it fail loudly instead of overselling. I work at the
intersection of **behavioural science, rigorous measurement, and dependable data engineering**.

*A note on AI, since everyone claims it:* in my projects the model is rarely more than a thin layer —
deliberately. Every decision and every alert is computed by deterministic code; the model handles
background memory and summarisation. The work I actually do is the
unglamorous part underneath: pipelines, measurement, provenance, and **evaluating** when a system is
genuinely ready rather than good-on-average.

I hold a postgraduate Master's in **Behavioural Data Science** (IL3 – Universitat de Barcelona, 9.17/10).
Before specialising, I spent **almost three years in pre-production QA** on Santander's Confirming
platform, checking credit-limit calculations against production data in SQL — where I learned
institutional rigour. One of those checks caught a tax-configuration defect that would have
miscalculated credit limits across markets.

### What I build

- **Figures checker** — checks figures quoted in Spain's Congress against official statistics (INE,
  Eurostat, Social Security, the Ministry of Labour, the BOE), as they were published on the day each
  figure was said. Where a stored official series covers a claim, a language model only reads the
  sentence and code makes the comparison; where none does, a research agent proposes an answer from
  official sources. A named reviewer approves every verification before it is published. Web
  interface, public API and a read-only MCP server for AI assistants. Built with a mentor. *(The code
  is private; the live product is coming and I will link it here.)* *(My main line of work.)*
- **Acceptance infrastructure for AI agents** — AI agents write code in some of my projects on a schedule,
  unattended. Every task carries the command that decides whether it is done, and an agent cannot
  commit until that command passes. **More than 160 automated checkers** across four of my systems,
  and the harness breaks its own checkers on purpose to find the ones that fail to notice.
  "Could not measure" is a verdict of its own, never counted as a pass.
  *(Private — happy to walk through it.)*
- **Retrieval systems you can trust** — a retrieval (RAG) system with its own **evaluation harness
  and a deterministic regression gate** (it hard-fails if retrieval quality drops), so the system catches
  its own regressions instead of finding out in production. *(Private — happy to walk through it.)*
- **Responsible AI in real apps** — an **endurance training and nutrition platform** built end-to-end
  (FastAPI, PostgreSQL, Supabase, Garmin/Strava, **over 2,500 automated tests**). Every decision and
  every alert that matters is computed by deterministic code. The model does background memory and
  summarisation, and nothing that decides anything. *(Private — available on request.)*
- **Geospatial for decisions** — a dashboard built for a **UN ESCWA** assignment over Lebanon
  (Leaflet.js, **1,545 ADM3 localities**), with a rule-based demographic classifier and prompt-level
  defenses so answers stay grounded in the data.
- **Making data legible** — end-to-end analytics for **Project RYSE** in R (clustering, Random
  Forest, XGBoost, GLM, ETL), surfacing a *decision* gap rather than a skill one.

### Stack I reach for

Python · R · SQL · FastAPI · PostgreSQL · SvelteKit · Leaflet.js / GIS · R Shiny · Git

### What I'm looking for

Roles where data has to be **trustworthy to matter** — reliable systems, honest measurement,
provenance without overselling causality. That spans **information integrity & accountability**,
**evidence & impact**, and **behavioural insights**, in teams that publish their methods and
welcome scrutiny, and above all in public institutions. Based in Seville, fully mobile across the EU.
