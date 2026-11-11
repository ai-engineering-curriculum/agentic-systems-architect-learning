# Job Requirements — Agentic Systems Architect

**Role level:** 48 (design-altitude architect rung — top of the individual-contributor architect stack for production agentic AI systems)
**Track:** `agentic-systems-architect-learning`
**Research window:** 2026-08-13 → 2026-11-11 (last 90 days)
**Today:** 2026-11-11
**Prior refresh:** 2026-10-08 (31-posting incremental refresh; this is a 30-day incremental refresh of that work).

This file maps verbatim requirements from current L48-altitude agentic-architect job postings to the existing curriculum. Raw normalized data lives in [`.aicg/job-requirements.json`](.aicg/job-requirements.json); the strictly-additive proposal lives in [`.aicg/curriculum-plan-delta.json`](.aicg/curriculum-plan-delta.json).

## Summary

- Postings sampled: **41** (30 in the 2026-08-13 → 2026-11-11 window; 11 retained from prior-cycle window because the themes they anchor are also carried by in-window postings — dropping them would not change any theme past the ≥30% threshold).
- **New postings observed this cycle (2026-10-11 → 2026-11-11):** Caterpillar (Principal Architect — AI Factory / Physical AI), Verizon (Principal Engineer — AI Platform Architect), OpenAI (Applied AI Architect, OpenAI for Government), Brady Corporation (Cloud & AI Platforms Architect), phData (Applied AI Solution Architect), Capgemini (Managing / Principal AI Architect), LPL Financial (Principal Solution Architect — AI), BMO (Principal Architect AI Platform), Banyan Software (Lead AI Architect — Data Platform), GSK (Senior Principal Architect — AI ML and Cloud Security).
- Equivalent titles counted per research packet: `Agentic Systems Architect`, `Agentic AI Architect`, `AI Agent Architect`, `Solution Architect - Agentic AI`, `Multi-Agent Systems Architect`, `Principal AI Engineer - Agents` — plus close-adjacent architect-altitude titles (`Distinguished Engineer / Distinguished AI Engineer (Agentic Platform)`, `Principal AI Architect / Principal Enterprise Architect (AI, majority-agentic)`, `Chief AI Architect`, `Head of Applied AI Architecture`, `Manager / Head of Applied AI Architecture`, `Staff AI Architect`, `Agentic Operations Architect`, `Principal Conversational & Agentic AI Architect`, `Applied AI Architect (public sector)`, `Lead AI Architect (portfolio / holdco)`, `Principal AI Platform Architect`, `Principal AI Architect — AI Factory / Physical AI`).
- **Proposed delta this cycle: 0 modules, 0 exercises, 0 projects.** Every load-bearing theme (≥ 30% frequency AND ≥ 3 distinct postings) either (a) is already owned by an existing L48 module (mod-301..310) or an existing L48 project, (b) belongs at a lower L30/L40 rung and is linked as a prerequisite, or (c) belongs at a sibling architect track and is linked out. **Nothing has materially shifted in the 30-day incremental window that reframes the scope decision made in the 2026-09 exhaustive pass.**
- **Two themes crossed above threshold this cycle.** *Observability & tracing* rose from ~27% to ~34% (Caterpillar 'DCGM / Prometheus / Grafana / Loki, SRE practices and SLOs'; Verizon, Brady, phData, LPL, BMO, Banyan all cite agent observability as architecture-level) — already covered by [`mod-305`](lessons/mod-305-observability-tracing); no delta. *Design authority / architecture review board / gate reviews* rose from ~23% to ~32% (Verizon 'formal layer boundaries, interface contracts'; LPL 'architecture review cycles across Enterprise Architecture and risk forums'; BMO 'architectural governance for major AI initiatives'; GSK 'Your specifications are what Engineering builds from') — still bundled in the architect-leadership cluster `needs-research`, reinforcing the 2026-12 human-decision question but not creating a new technical gap.
- **Two themes dropped below threshold this cycle.** *Publish / evangelize / thought leadership* fell from ~38% to ~24% (external publication is less common in product/platform/consulting postings; internal pattern-library authorship, which carries over to theme-02, has replaced external evangelism in many new postings). *Pre-sales / RFP / GTM enablement* fell from ~31% to ~27% (new in-window product/platform postings — Caterpillar, Brady, LPL, BMO, Banyan, GSK — don't require it). Both drops confirm existing coverage decisions (publish/evangelize stays in architect-leadership cluster needs-research; pre-sales stays linked out as sub-role specialization).
- **Theme 16 (TCO / cost architecture / build-vs-buy) rose from ~31% to ~39% this cycle.** Verizon's explicit *"comprehensive 3-year TCO models"* template is echoed by LPL ('LLMOps and AgentOps: FinOps'), BMO ('cost residency'), Brady ('FinOps best practices'), Banyan ('keep the bill rational'). Still carried by [`mod-307`](lessons/mod-307-cost-latency-architecture); if it rises above 55% next cycle, extend `mod-307 exercise-01` to require a 3-year TCO model as deliverable — no new module.
- The **strongest uncovered signal cluster** remains *architect leadership & influence at L48*. Updated component frequencies this cycle: executive stakeholder advisory (**~54%**), practice-level mentoring of architects (**~46%**), design-authority / ARB / gate reviews (**~32%** — NEW: crossed above threshold), architecture thought leadership / publishing (~24% — dropped below threshold). **Union frequency ~68%** (up from ~62%). This cluster is a **curriculum-scope-boundary question, not a market-drift signal** — the L48 curriculum was designed by intent as a technical-architecture spine; leadership content may belong to sibling generic-architect tracks (e.g., `senior-ai-governance-architect-learning/mod-112-program-design-and-org-shape`, `ai-infra-senior-architect-learning`, `cto-curriculum`). The REINFORCEMENT this cycle raises the stakes of the 2026-12 human-decision cycle but does not change the architectural answer this cycle: PREFER ZERO ADDITIONS over weakly-justified ones. Still flagged `needs-research`.
- **New sub-threshold signals observed this cycle:**
  - *EU-data-residency / sovereign-inference architecture* (~25%): GSK 'network designs that keep an inference call inside the EU'; BMO 'residency across AWS+Azure'; OpenAI Gov (explicit Munich/London posting). Already carried by [`mod-309 exercise-05`](lessons/mod-309-governance-compliance-domain) (data-handling-residency-design). If it crosses 40% next cycle, extend that exercise with a sovereign-inference worked example (private endpoints, CMK, in-region inference) — no new module.
  - *Pattern-library-published-as-RFC* (~45% of new in-window postings): GSK 'Author the pattern library entries...that engineering teams build from'; Verizon 'Contribute high-impact reference architectures to the enterprise library'; phData 'Design reusable agentic accelerators and reference architectures'. Reinforcement of theme-02 (71%) + theme-19 (29%); already carried by [`mod-301 exercise-04`](lessons/mod-301-agentic-systems-foundations) + [`project-301`](projects/project-301-production-agentic-reference-architecture) + [`project-303`](projects/project-303-extensible-agent-platform).
  - *Design-authority-as-contract* (~40% of new in-window postings): drives theme-20 above threshold; stays in architect-leadership cluster.
  - *3-year TCO modeling as explicit L48 duty* (~33% of new in-window postings): drives theme-16 above 30%; still covered by mod-307.
  - *Physical AI / autonomy-at-scale architect* (~9%, Caterpillar-anchored): sub-threshold and adjacent to the chat-architect pool — watch item only.
  - *Portfolio/holdco multi-company architecture* (~8%, Banyan-anchored): sub-threshold — watch item only.
- **MCP continues to appear as universal-baseline** (~32% explicit callouts in the full sample; >40% in new in-window postings) — still carried by [`mod-302 exercise-03`](lessons/mod-302-multi-agent-orchestration) and [`mod-310 exercise-02`](lessons/mod-310-agentic-developer-platforms). If MCP-tool-governance (versioning MCP servers, MCP-server catalog, cross-MCP-server auth) becomes an explicit L48 architectural concern in >50% of postings next cycle, consider a focused exercise under mod-310. Not this cycle.

## Methodology

- **This cycle (2026-11):** 30-day incremental refresh of the 2026-10-08 pass. Window shifted to 2026-08-13 → 2026-11-11. Prior 31-posting sample preserved where postings remain in-window; 10 new Oct/Nov 2026 postings appended (Caterpillar, Verizon AI Platform, OpenAI Gov, Brady, phData, Capgemini, LPL Financial, BMO, Banyan Software, GSK). Postings dated before 2026-08-13 (Cognizant Agentic AI Architect 2026-06-29, Capital One Distinguished pair est:2026-06, Deloitte Google AI Architect est:2026-07, Lenovo 2026-06-03, OKX est:2026-07, Cognizant Bedrock 2026-06-11, Salesforce est:2026-07, UiPath est:2026-07, Anthropic est:2026-06, KPMG est:2026-07, Guidehouse est:2026-07) fell outside the new window_start but were retained with `in_prior_window:true` because the themes they anchor are also carried by in-window postings — dropping them would not change any theme past the ≥30% threshold.
- Sources: `job-boards.greenhouse.io` (Anthropic, Airtable, OKX, Banyan Software), `jobs.smartrecruiters.com` (ServiceNow, Experian), `careers.cognizant.com`, `builtin.com` (Brady, phData), `builtinnyc.com` (BMO), `builtinchicago.org` (Vertex Inc), `jobs.lenovo.com`, `careers.airindia.com`, `pwc.wd3.myworkdayjobs.com`, `guidehouse.wd1.myworkdayjobs.com`, `apply.deloitte.com`, `kpmguscareers.com`, `capitalonecareers.com`, `careers.zoom.us`, `careers.ingrammicro.com`, `mycareer.verizon.com`, `remotive.com`, `dentsuaegis.wd3.myworkdayjobs.com`, `openai.com/careers`, `jobs.a16z.com` (OpenAI Gov), `himalayas.app`, `ats.rippling.com`, `jobs.ashbyhq.com`, `jobs.scotiabank.com`, `jobs.nvidia.com`, `careers.salesforce.com`, `careers.caterpillar.com`, `career.lpl.com`, `dreamworkhq.com` (GSK), `freehire.me` (Capgemini), `linkedin.com/jobs`, and secondary aggregators (Built In, jobright, remoterocketship) for Google-snippet triangulation where SPAs blocked WebFetch.
- Per-posting capture: employer, title, URL, `date_observed`, `date_posted` (marked `estimated:YYYY-MM` when only "posted N days/weeks ago" was visible), location, 6–10 verbatim/near-verbatim requirement quotes prioritized on **L48-distinguishing altitude** — reference-architecture ownership, portfolio/practice scope, C-suite advisory, authored standards, mentoring of architects, cross-team/cross-organization influence, TCO/multi-cloud tradeoffs, governance embedded at architecture — NOT L30 build fundamentals which would double-count against lower-rung tracks.
- Frequency = distinct postings citing the theme ÷ 41 sampled postings (30 in-window + 11 retained from prior-cycle window per the sample-size note above). Prior-cycle percentages are shown in-line as "(prior ~XX%)" where the change crosses the ±1-posting noise band or a load-bearing threshold.
- Threshold for a new curriculum item: ≥ 3 postings AND ≥ 30% frequency AND no existing module/exercise/project can be incrementally extended to cover it AND primary ownership belongs at this L48 rung (ownership rule).
- Continuity bias applied strictly: for every above-threshold theme, checked (a) existing L48 coverage first, (b) whether the theme belongs at a lower level (L30/L40) per the ownership rule, (c) whether the theme belongs at a sibling architect track.
- Source-quality caveats documented in `summary.source_quality_caveats` in `.aicg/job-requirements.json`.

## Ownership rule applied

Where a requirement is genuinely needed at multiple levels, primary ownership sits with the **lowest-level role where it is required**. This L48 track:
- Links **down** to L30 `agentic-ai-engineer-learning` / `rag-engineer-learning` / `ai-eval-engineer-learning` for build fundamentals (framework mechanics, RAG pipeline implementation, single-agent evaluation) — named as prerequisites, not re-taught.
- Links **down** to L40 `senior-agentic-ai-engineer-learning` for production-hardening build skills (fleet observability implementation, eval infrastructure at production scale, incident response) — named as recommended on-ramp, not re-taught.
- Links **sideways** to sibling architect tracks: `agentic-safety-engineer-learning` for frontier-safety depth (dangerous-capability evals, jailbreak engineering, control evaluation) and `senior-ai-governance-architect-learning` for AIMS/policy-as-code/audit-architecture depth.

## Requirement themes → curriculum ownership

**Bold frequencies** are ≥ 30% (load-bearing under continuity bias).

| # | Theme | Freq | Owner role | Coverage |
|---|---|---|---|---|
| 1 | Multi-agent orchestration architecture (patterns, coordination, tool interfaces) | **61%** (prior 85%)† | `agentic-systems-architect` (this) | [`mod-301`](lessons/mod-301-agentic-systems-foundations), [`mod-302`](lessons/mod-302-multi-agent-orchestration), [`project-301`](projects/project-301-production-agentic-reference-architecture) |
| 2 | Reference architectures & reusable solution blueprints as first-class deliverable | **71%** (prior 73%) | `agentic-systems-architect` (this) | [`mod-301/exercises/exercise-04-reference-architecture-teardown`](lessons/mod-301-agentic-systems-foundations), [`project-301`](projects/project-301-production-agentic-reference-architecture), [`project-303`](projects/project-303-extensible-agent-platform) |
| 3 | C-suite / executive stakeholder advisory & influence | **54%** (prior 62%) | under-review — L48 candidate or sibling generic-architect track | **Not currently covered explicitly.** Bundled in the architect-leadership-cluster `needs-research` (see below). |
| 4 | AI governance frameworks embedded in architecture (responsible AI, model risk, regulatory compliance) | **56%** (prior 58%) | `agentic-systems-architect` (this) | [`mod-309`](lessons/mod-309-governance-compliance-domain), especially `exercise-01-horizontal-framework-controls-mapping` and `exercise-04-governance-accountability-spec` |
| 5 | Mentor architects / develop architectural capability at practice level | **46%** (prior 50%) | under-review — L48 candidate or sibling generic-architect track | **Not currently covered explicitly.** L40 `senior-agentic-ai-engineer-learning/mod-405` owns mentoring of ENGINEERS; mentoring of ARCHITECTS is a distinct L48 skill. Bundled in the architect-leadership-cluster `needs-research`. |
| 6 | Guardrails architecture (prompt injection defense, guardrail services, red-team harnesses) | **41%** (prior 50%) | `agentic-systems-architect` (this) — architectural placement; `agentic-safety-engineer` for frontier-safety depth | [`mod-306`](lessons/mod-306-guardrails-safety-security). Cross-link to [`agentic-safety-engineer-learning`](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) for dangerous-capability evals, jailbreak engineering, and frontier-monitor design. |
| 7 | Regulated-domain architecture (healthcare/finance/PCI/HIPAA/FedRAMP/banking/crypto/aviation/pharma/public-sector) | **41%** (prior 50%) | `agentic-systems-architect` (this) | [`mod-309`](lessons/mod-309-governance-compliance-domain), [`project-302`](projects/project-302-regulated-domain-agent-architecture) (learner-selected sector). Deeper GRC/AIMS depth in [`senior-ai-governance-architect-learning`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning). |
| 8 | Vendor-agnostic multi-framework fluency (LangGraph, ADK, OpenAI Agents SDK, Claude Agent SDK, AutoGen, CrewAI, Semantic Kernel, Strands, MCP, Azure AI Foundry, Copilot Studio, Agent 365) | **37%** (prior 46%) | `agentic-ai-engineer` (L30) — build mechanics; `agentic-systems-architect` (L48) — portability/lock-in tradeoffs | **Prerequisite:** [`agentic-ai-engineer-learning/mod-202-frameworks`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) for framework mechanics. L48 architectural lens (MCP/A2A protocol integration, platform-portability analysis) in [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration) and [`project-303`](projects/project-303-extensible-agent-platform) (justify against alternative platform). |
| 9 | Multi-cloud / hyperscaler architecture (AWS + Azure + GCP for agentic AI) | **44%** (prior 42%) | `agentic-systems-architect` (this) | Implicitly covered — the curriculum is cloud/vendor-neutral by design. Learners exercise cross-cloud tradeoffs in [`project-301`](projects/project-301-production-agentic-reference-architecture) and routing architecture in [`mod-307/exercises/exercise-02-caching-and-routing-architecture`](lessons/mod-307-cost-latency-architecture). See "Themes just below threshold" below for the sub-cycle plan. |
| 10 | Evaluation infrastructure / harnesses / metrics at architecture level | **41%** (prior 42%) | `agentic-systems-architect` (this) — architecture strategy; `senior-agentic-ai-engineer` (L40) — build infrastructure; `ai-eval-engineer` (L30) — specialist evaluation | [`mod-304`](lessons/mod-304-evaluation-harnesses). Build-level eval infrastructure at L40 [`mod-402-eval-observability-infra`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning). Specialist-eval depth at L30 [`ai-eval-engineer-learning`](https://github.com/ai-engineering-curriculum/ai-eval-engineer-learning). |
| 11 | Memory / context / RAG architecture as architectural concern | **41%** (prior 42%) | `agentic-systems-architect` (this) — architectural placement; `rag-engineer` (L30) + `agentic-ai-engineer` (L30) — implementation | [`mod-303`](lessons/mod-303-memory-context-architecture). RAG pipeline implementation is prerequisite: [`agentic-ai-engineer-learning/mod-203-rag-and-memory`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) and specialist depth in [`rag-engineer-learning`](https://github.com/ai-engineering-curriculum/rag-engineer-learning). |
| 12 | Tool integration / MCP / function calling architecture (tool schemas as architectural interface) | **32%** (prior 38%) | `agentic-systems-architect` (this) | [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration), [`mod-310`](lessons/mod-310-agentic-developer-platforms) especially `exercise-02-secure-tool-use-and-context-hydration`. MCP-server authoring at L30 [`agentic-ai-engineer-learning/mod-202-frameworks/exercises/exercise-04-mcp-tool-server`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning). |
| 13 | Publish / evangelize / architecture thought leadership (conferences, blogs, POVs, office hours) | 24% (prior 38%) ↓ | under-review — L48 candidate or sibling generic-architect track | DROPPED BELOW THRESHOLD. **Not currently covered explicitly.** Still bundled in the architect-leadership-cluster `needs-research`. |
| 14 | Enterprise integration / legacy systems / API bridging | **32%** (prior 38%) | `agentic-systems-architect` (this) | [`mod-310/exercises/exercise-03-workflow-toolchain-integration`](lessons/mod-310-agentic-developer-platforms) |
| 15 | Vertical / domain-specific architecture (industry expertise as architectural input) | **34%** (prior 35%) | `agentic-systems-architect` (this) | [`project-302`](projects/project-302-regulated-domain-agent-architecture) (learner-selected sector — the balanced-menu design is what carries this theme; new verticals this cycle: industrial physical AI, public sector, pharma) |
| 16 | TCO / cost architecture / build-vs-buy at portfolio level | **39%** (prior 31%) ↑ | `agentic-systems-architect` (this) | [`mod-307`](lessons/mod-307-cost-latency-architecture). Build-level cost defense at L40 [`mod-403/02-token-and-latency-budgets`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning). |
| 17 | Pre-sales / RFP / GTM enablement (customer-facing sales engineering) | 27% (prior 31%) ↓ | not-curriculum-worthy universally — sub-role specialization | DROPPED BELOW THRESHOLD. **Link out.** Concentrated at consulting shops (Slalom, KPMG, PwC, Lenovo, phData, Capgemini) and vendor-SA roles (NVIDIA, Anthropic Applied AI, OpenAI Gov). Product-team architects (Airtable, Gusto, Experian, Airline, Caterpillar, Brady, LPL, BMO, Banyan, GSK) don't need it. External resources: AWS SAA, GCP Professional Cloud Architect certifications, and SPIN Selling (Rackham) for the advisory-discovery pattern. |
| 18 | Observability & tracing (fleet-level, drift detection, monitoring) | **34%** (prior 27%) ↑ | `agentic-systems-architect` (this) | [`mod-305`](lessons/mod-305-observability-tracing) — CROSSED ABOVE THRESHOLD this cycle; already owned, no delta. |
| 19 | Central platform / paved-road / shared-service agentic architecture | 29% (prior 23%) ↑ | `agentic-systems-architect` (this) | Still just below threshold. [`mod-310`](lessons/mod-310-agentic-developer-platforms), [`project-303`](projects/project-303-extensible-agent-platform) |
| 20 | Design authority / architecture review board / gate reviews for agentic changes | **32%** (prior 23%) ↑ | under-review | CROSSED ABOVE THRESHOLD this cycle. Bundled in the architect-leadership-cluster `needs-research` — reinforces the cluster, does not create a new technical gap. |
| 21 | Human-in-the-loop / approval boundaries in architecture | 15% (stable) | `agentic-systems-architect` (this) | [`mod-306`](lessons/mod-306-guardrails-safety-security), [`mod-308/exercises/exercise-02-hitl-approval-architecture`](lessons/mod-308-deployment-durable-execution) |
| 22 | EU-data-residency / sovereign-inference architecture (private endpoints, CMK, in-region inference) | 25% (new signal) | `agentic-systems-architect` (this) | NEW sub-threshold signal; architectural placement already carried by [`mod-309 exercise-05 data-handling-residency-design`](lessons/mod-309-governance-compliance-domain) + [`project-302`](projects/project-302-regulated-domain-agent-architecture). Watch item. |

†Theme-01 drop is a sample-composition effect, not a market retreat. The 10 new-cycle postings skew enterprise-platform/consulting, where orchestration is one architectural concern among many rather than THE defining concern. Still dominant and still owned by mod-301/mod-302. ↑ = crossed above threshold this cycle; ↓ = dropped below threshold this cycle.

## Posting evidence for load-bearing themes

The tables below list postings anchoring each ≥ 30% theme in the 41-posting sample (30 in the 2026-08-13 → 2026-11-11 window + 11 retained from prior-cycle window). New postings this cycle are marked **(new 2026-11)**.

### Theme 1 — Multi-agent orchestration architecture (61%, prior 85%)

| Employer | Title | URL | Date observed | Posted |
|---|---|---|---|---|
| Cognizant | Agentic AI Architect | https://careers.cognizant.com/us-en/jobs/00069574701/agentic-ai-architect/ | 2026-09-08 | 2026-06-29 |
| Air India | Agentic AI Architect | https://careers.airindia.com/job/Gurugram-Agentic-AI-Architect/55349644/ | 2026-09-08 | 2026-08-21 |
| Slalom | Agentic AI Architect - Intelligence Engineering (East) | https://www.linkedin.com/jobs/view/agentic-ai-architect-intelligence-engineering-east-at-slalom-4434388672 | 2026-09-08 | est:2026-09 |
| Capital One | Distinguished AI Engineer (Agentic AI Platform) | https://www.capitalonecareers.com/job/san-jose/distinguished-ai-engineer-agentic-ai-platform/1732/89599740832 | 2026-09-08 | est:2026-06 |
| Capital One | Sr. Distinguished AI Engineer (Agentic AI Platform) | https://www.capitalonecareers.com/job/mclean/sr-distinguished-ai-engineer-agentic-ai-platform/1732/91069871376 | 2026-09-08 | est:2026-06 |
| Deloitte Consulting | Google AI Architect | https://apply.deloitte.com/en_US/careers/JobDetail/Google-AI-Architect/362202 | 2026-09-08 | est:2026-07 |
| Concentrix | Principal Architect: AI & GCP Agentic Stack | https://himalayas.app/companies/concentrix/jobs/principal-architect-ai-gcp-agentic-stack-330828100 | 2026-09-08 | 2026-09-03 |
| Lenovo | AI Solutions Architect, Agentic AI | https://jobs.lenovo.com/en_US/careers/JobDetail/AI-Solutions-Architect-Agentic-AI/78115 | 2026-09-08 | 2026-06-03 |
| Zoom | Principal AI Architect - Agentic Verticals | https://careers.zoom.us/jobs/principal-ai-architect-agentic-verticals-seattle-washington-united-states-san-jose-california | 2026-09-08 | est:2026-08 |
| Experian | Staff AI Architect | https://jobs.smartrecruiters.com/experian/744000144163919-staff-ai-architect-remote | 2026-09-08 | est:2026-08 |
| OKX | Principal AI Engineer, AI Agent Development | https://job-boards.greenhouse.io/okx/jobs/7650500003 | 2026-09-08 | est:2026-07 |
| Airtable | AI Agent Architect, Customer Experience | https://job-boards.greenhouse.io/airtable/jobs/8409168002 | 2026-09-08 | est:2026-08 |
| ServiceNow | Principal Applied AI Architect | https://jobs.smartrecruiters.com/ServiceNow/744000147375129-principal-applied-ai-architect | 2026-09-08 | est:2026-09 |
| ServiceNow | Principal AI Platform Engineer (FDE Lead Architect) | https://jobs.smartrecruiters.com/ServiceNow/744000146559474-principal-ai-platform-engineer | 2026-09-08 | est:2026-09 |
| NVIDIA | Senior Solutions Architect, Agentic AI | https://jobs.nvidia.com/careers/job/893396513561 | 2026-09-08 | est:2026-08 |
| PwC | Agentic AI & Digital Solution Architect | https://pwc.wd3.myworkdayjobs.com/en-US/Global_Experienced_Careers/job/Agentic-AI---Digital-Solution-Architecture-_744314WD | 2026-09-08 | est:2026-08 |
| Gusto | Agentic Operations Architect | https://builtin.com/job/senior-manager-agentic-strategy-operations/10066231 | 2026-09-08 | est:2026-09 |
| Accommodations Plus Intl | Principal Architect - Enterprise Architecture & AI | https://ats.rippling.com/accommodations-plus-international/jobs/7fb6c63a-3e2a-48e8-b45b-2e95cb035563 | 2026-09-08 | est:2026-08 |
| Cognizant | Principal AI Architect - Agentic AI, AWS Bedrock | https://careers.cognizant.com/latam-es/empleos/00069303232/principal-ai-architect-agentic-ai-aws-bedrock-broad-spectrum-ai-remote/ | 2026-09-08 | 2026-06-11 |
| Salesforce | Principal Data and AI Architect | https://careers.salesforce.com/en/jobs/jr331487/principal-data-and-ai-architect/ | 2026-09-08 | est:2026-07 |
| Scotiabank | Chief AI Architect | https://jobs.scotiabank.com/job/Dallas-Chief-AI-Architect-TX-75201/601879417/ | 2026-09-08 | est:2026-08 |
| UiPath | Principal AI Architect - Healthcare | https://jobs.ashbyhq.com/uipath/77e4db91-6d9e-49f9-b6a3-ab158b7aa4f2 | 2026-09-08 | est:2026-07 |
| Verizon | Principal Conversational & Agentic AI Architect | https://mycareer.verizon.com/jobs/r-1095664/principal-conversational-agentic-ai-architect/ | 2026-10-08 | est:2026-09 |
| Cognizant | Gen AI Architect (Agentic AI & LLM) — Remote | https://careers.cognizant.com/us-en/jobs/00070546971/gen-ai-architect-agentic-ai-llm-remote/ | 2026-10-08 | est:2026-09 |
| Coupa Software | Principal Agentic Architect | https://remotive.com/remote/jobs/artificial-intelligence/principal-agentic-architect-5005660 | 2026-10-08 | est:2026-09 |
| Vertex, Inc. | Principal Architect, Agentic AI | https://www.builtinchicago.org/job/principal-cloud-architect-remote-us/6302120 | 2026-10-08 | 2026-09-25 |
| Ingram Micro | Agentic AI Architect | https://careers.ingrammicro.com/en/jobs/r-113852/agentic-ai-architect/ | 2026-10-08 | est:2026-09 |
| Dentsu | Agentic AI Architect | https://dentsuaegis.wd3.myworkdayjobs.com/en-US/DAN_GLOBAL/job/Agentic-AI-Architect_R1128451 | 2026-10-08 | est:2026-09 |
| OpenAI | Manager, Applied AI Architect | https://openai.com/careers/manager-applied-ai-architect/ | 2026-10-08 | 2026-10-01 |
| Verizon | Principal Engineer — AI Platform Architect **(new 2026-11)** | https://mycareer.verizon.com/jobs/r-1100306/principal-engineer-ai-platform-architect/ | 2026-11-11 | est:2026-10 |
| phData | Applied AI Solution Architect **(new 2026-11)** | https://builtin.com/job/applied-ai-solution-architect/12132541 | 2026-11-11 | 2026-11-07 |
| LPL Financial | Principal Solution Architect — AI **(new 2026-11)** | https://career.lpl.com/job/R-048509/Principal-Solution-Architect-AI | 2026-11-11 | 2026-11-09 |

Representative quotes:
- *"Architect multi-agent orchestration pipelines."* — Cognizant (Principal AI Architect)
- *"Design end-to-end agentic AI architectures including planning loops, memory management, tool integration, and agent coordination patterns."* — Slalom
- *"Architect multi-agent systems (MAS) and frameworks to support goal-directed, reasoning, planning, and reinforcement-learning-based agents."* — OKX
- *"Design comprehensive system architectures for vertical Agentic AI applications."* — Zoom
- *"Design and optimize how AI agents reason, retrieve, decide, and act — architecting the knowledge systems, decision logic, and guardrails."* — Airtable
- *"Design, build, and optimize enterprise-grade conversational AI and multi-agent solutions; architect end-to-end agent workflows integrating backend systems, LLMs, and NLU models."* — Verizon (Conversational+Agentic, 2026-10)
- *"Define the end-to-end architecture for Coupa's agentic AI platform across spend management workflows; architect multi-agent orchestration patterns and tool-use interfaces (MCP, function calling)."* — Coupa (2026-10)
- *"Direct the 5-layer architecture stack — Encompassing Model Foundation, Agent Factory, Agent Runtime, Experience, and Control Plane layers."* — Verizon (AI Platform, **new 2026-11**)
- *"Architect intent routing, context assembly, and delegation between agents and domain services."* — LPL Financial (**new 2026-11**)
- *"Experience with multi-agent patterns, memory, planning, and protocols (e.g. MCP)."* — phData (**new 2026-11**)

→ Covered by [`mod-301`](lessons/mod-301-agentic-systems-foundations) (workflow-vs-agent decomposition; orchestration-pattern catalog) and [`mod-302`](lessons/mod-302-multi-agent-orchestration) (orchestrator-worker topology, handoffs vs. manager-as-tools, MCP/A2A protocols, escalation design), integrated end-to-end in [`project-301`](projects/project-301-production-agentic-reference-architecture).

### Theme 2 — Reference architectures & reusable solution blueprints (71%, prior 73%)

Anchored by all of the prior-cycle references (Cognizant, Air India, Guidehouse, Slalom, Capital One, Deloitte, Lenovo, Zoom, Concentrix, ServiceNow, Experian, Scotiabank, PwC, NVIDIA, Salesforce, Cognizant Principal Bedrock, Cognizant Principal Enterprise, KPMG, Accommodations Plus) PLUS all 10 new 2026-11 postings (Caterpillar, Verizon AI Platform, OpenAI Gov, Brady, phData, Capgemini, LPL, BMO, Banyan, GSK) — this is the strongest-anchored theme this cycle.

Representative quotes:
- *"Develop reference architectures for AI solutions across regulated industries."* — Zoom
- *"Define the multi-engagement technical direction, reference architectures, reusable deployment patterns."* — ServiceNow (FDE Lead)
- *"Produce reusable solution IP for Lenovo's agentic AI offering portfolio: reference architectures, solution blueprints."* — Lenovo
- *"Build hands-on proofs-of-concept and reference architectures that serve as blueprints for production-grade generative AI pipelines."* — NVIDIA
- *"You will contribute to the north star platform architecture, continuously publishing and refining living diagrams and canonical APIs."* — Capital One
- *"Translates architecture into implementation plans, reference architectures, and standards across platform teams."* — Caterpillar (**new 2026-11**)
- *"Contribute high-impact reference architectures to the enterprise library to drive architectural maturity."* — Verizon AI Platform (**new 2026-11**)
- *"Design reusable agentic accelerators and reference architectures aligned with the Intelligence Platform."* — phData (**new 2026-11**)
- *"Author the pattern library entries for LLM orchestration, retrieval boundaries and tool-calling scopes that engineering teams build from."* — GSK (**new 2026-11**)
- *"Own and evolve reference architectures for AI-enabled applications, including user-facing AI workspaces."* — LPL Financial (**new 2026-11**)
- *"Define and maintain the target AI architecture for the enterprise: reference architectures, architectural standards."* — BMO (**new 2026-11**)

→ Covered by [`mod-301/exercises/exercise-04-reference-architecture-teardown`](lessons/mod-301-agentic-systems-foundations) (analyze existing reference architectures), [`project-301`](projects/project-301-production-agentic-reference-architecture) (produce an end-to-end reference architecture with ADR set, diagrams, eval plan, cost model, threat model), and [`project-303`](projects/project-303-extensible-agent-platform) (produce reusable extension architecture and adoption/DX plan — the "canonical patterns others adopt" deliverable). The emerging "pattern library as RFC" pattern (GSK, Verizon, phData) reads as reinforcement of these exercises/projects, not a new requirement.

### Theme 3 — C-suite / executive stakeholder advisory & influence (54%, prior 62%)

Anchored by prior-cycle Cognizant, Slalom, Capital One (both), Deloitte, KPMG, Zoom, ServiceNow (both), Experian, Concentrix, Anthropic, UiPath, PwC, Scotiabank, Cognizant Principal Enterprise, Air India, PLUS new-cycle OpenAI Gov, phData, Capgemini, LPL, BMO, Banyan.

Representative quotes:
- *"Serve as senior technical voice in customer executive conversations."* — Zoom
- *"Act as a trusted advisor to senior and C-level client stakeholders, shaping AI strategies."* — KPMG
- *"Lead and mentor multiple engineering teams and influence cross-functional stakeholders up to the VP level."* — Capital One (Distinguished)
- *"Develop trusted relationships and technical champions across CIOs, CTOs, CISOs, Chief Data and AI Officers, program leaders, engineering teams."* — OpenAI Gov (**new 2026-11**)
- *"Executive presence and influence: the credibility to advise Directors and senior executives, the judgment to make defensible [decisions]."* — BMO (**new 2026-11**)
- *"Work directly with CIOs, CTOs, CDOs, and senior business leaders, providing strategic guidance."* — Capgemini (**new 2026-11**)
- *"Represent Banyan's AI and data architecture to our executive team, our portfolio companies."* — Banyan Software (**new 2026-11**)
- *"Act as a trusted advisor to senior client stakeholders, shaping roadmaps, influencing strategic decisions."* — phData (**new 2026-11**)
- *"Mentor solution and software architects, influence roadmaps, and communicate tradeoffs to senior stakeholders."* — LPL Financial (**new 2026-11**)

→ **Not currently covered explicitly at L48.** See "Uncovered signal cluster — architect leadership & influence" below. REINFORCED this cycle by 6 new postings — the 2026-12 human-decision cycle should prioritize this.

### Theme 4 — AI governance frameworks embedded in architecture (56%, prior 58%)

Anchored by prior-cycle Cognizant, Air India, Slalom, Deloitte, Zoom, KPMG, UiPath, Accommodations Plus, Guidehouse, OKX, Scotiabank, Gusto, Capital One, PwC, PLUS new-cycle Verizon AI Platform, Brady, phData, Capgemini, LPL, BMO, GSK, OpenAI Gov.

Representative quotes:
- *"Define governance frameworks ensuring responsible AI usage, security, explainability, and regulatory compliance."* — Cognizant / Air India
- *"Establish governance patterns for LLM cost, latency, and safety trade-offs."* — Zoom
- *"Advise clients on AI Risk Management, Governance, and Security."* — KPMG
- *"In partnership with AppSec and risk functions, you embed security, PCI/PII compliance, and responsible AI controls into architectural defaults — structural, not bolted on."* — Accommodations Plus
- *"Translate regulatory requirements into architecture controls embedded in solution designs at inception."* — Scotiabank
- *"Engineer Responsible AI (RAI) guardrail architectures and ensure compliance with emerging international regulations."* — Verizon AI Platform (**new 2026-11**)
- *"Deep grounding in Responsible AI, AI/data governance, privacy, and evaluation/guardrail design."* — BMO (**new 2026-11**)
- *"Apply the binding AI security standards and threat models to every design, escalating where a design cannot meet them."* — GSK (**new 2026-11**)
- *"Establish robust AI governance, data privacy, safety guardrails, and secure MLOps practices to safeguard enterprise data."* — Brady (**new 2026-11**)
- *"Define classification and risk-tiering models that determine the evidence, evaluations, approvals required."* — LPL Financial (**new 2026-11**)

→ Covered by [`mod-309`](lessons/mod-309-governance-compliance-domain) (horizontal framework controls mapping, multi-regime regulated-domain architecture, extension-tool governance lifecycle, governance-accountability spec, data-handling/residency design). Deeper AIMS/policy-as-code/audit-architecture depth belongs to the sibling [`senior-ai-governance-architect-learning`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning) track; that is a different rung, not a duplicate.

### Theme 5 — Mentor architects / architectural-capability building (46%, prior 50%)

Anchored by prior-cycle Cognizant, Cognizant Principal Enterprise, Anthropic, Air India, Capital One (both), Scotiabank, Experian, OKX, Accommodations Plus, KPMG, Slalom, PLUS new-cycle Brady, phData, Capgemini, LPL, BMO, Banyan.

Representative quotes:
- *"Mentor architects, technology leads, and engineering teams while promoting architecture best practices and engineering excellence."* — Cognizant (Principal Enterprise Architect)
- *"Set architectural direction and build architectural capacity by developing architects from Senior to Principal levels."* — Scotiabank
- *"Provide architectural mentorship and technical leadership to architects and principal engineers across the function."* — BMO (**new 2026-11**)
- *"Mentor solution and software architects, influence roadmaps, and communicate tradeoffs to senior stakeholders."* — LPL Financial (**new 2026-11**)
- *"Mentor and coach team members, fostering a culture of learning, feedback, and continuous improvement."* — phData (**new 2026-11**)
- *"Build the team including vertical aligned Senior Business AI Analysts...Mentor them. Set the bar."* — Banyan Software (**new 2026-11**)
- *"Act as a technical liaison between business units and engineering teams, and mentor team members on GCP and Azure best practices."* — Brady (**new 2026-11**)

→ **Not currently covered explicitly at L48.** Distinct from L40 [`senior-agentic-ai-engineer-learning/mod-405-technical-leadership`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning) (which mentors engineers). Bundled in the "architect leadership & influence" uncovered signal cluster below. REINFORCED this cycle by 6 new postings.

### Theme 6 — Guardrails architecture (41%, prior 50%)

Anchored by prior-cycle Capital One (both), Air India, Cognizant, Slalom, Deloitte, Airtable, Accommodations Plus, NVIDIA, ServiceNow (FDE), OKX, Gusto, Concentrix, Zoom, PLUS new-cycle Verizon AI Platform, BMO, Banyan, GSK.

Representative quotes:
- *"Trust and safety remain paramount; you will help bring together a vision of central guardrail services — prompt firewalls, content-filter hooks, red team harnesses and audit APIs — consumed by every application."* — Capital One
- *"Manage AI safety and trust; establish guardrails to keep resolution rates high while failure rates stay low; responsible for edge cases, prompt injection defense, and preventing unintended behaviors."* — Airtable
- *"Design and implement evaluation harnesses, success metrics, automated testing pipelines, and guardrail frameworks."* — NVIDIA
- *"AI gateways, policy-as-code/authorization (Cedar, OPA), workload identity and zero-trust (SPIFFE/SPIRE), guardrails, and AI observability."* — BMO (**new 2026-11**)
- *"AI threat modelling and secure AI data flow design — vector store access control, classification, and AI-specific threats."* — GSK (**new 2026-11**)
- *"Define security, privacy, and AI safety guardrails. Classify data, design access tiering."* — Banyan (**new 2026-11**)

→ Covered by [`mod-306`](lessons/mod-306-guardrails-safety-security) — guardrail placement, prompt-injection threat modeling, least-privilege tool permissions, OAuth/RBAC token management, CLI-agent sandboxing, excessive-agency controls. For frontier-safety depth (dangerous-capability evals, jailbreak engineering, control evaluation), link to the sibling [`agentic-safety-engineer-learning`](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) track (different rung, not a duplicate).

### Theme 7 — Regulated-domain architecture (41%, prior 50%)

Anchored by prior-cycle UiPath (healthcare), Guidehouse (federal), KPMG, Scotiabank (banking), Cognizant Principal (fintech), PwC, Air India (compliance), Zoom (regulated verticals), OKX (crypto), Accommodations Plus (PCI/PII), Gusto (payroll compliance), Deloitte, Airtable, PLUS new-cycle LPL Financial (wealth management), BMO (banking), GSK (pharma + EU residency), OpenAI Gov (public sector).

Representative quotes:
- *"Serve as a trusted advisor to healthcare executives on AI, automation, agentic transformation."* — UiPath
- *"Design and deliver secure, scalable, and cost-effective cloud-native AI solutions for federal clients."* — Guidehouse
- *"Ensure system scalability, security, and regulatory compliance of AI-powered solutions in the crypto exchange domain."* — OKX
- *"Including human-in-the-loop controls and advisory-only boundaries so no unintended automated actions occur."* — LPL Financial (**new 2026-11, wealth-management**)
- *"Help customers navigate the security, compliance, governance, and deployment requirements that shape AI adoption in the public sector."* — OpenAI Gov (**new 2026-11, public sector**)
- *"Azure OpenAI and Vertex AI private endpoint and customer-managed-key patterns, and the network designs that keep an inference call inside the EU."* — GSK (**new 2026-11, pharma + EU residency**)
- *"Provide architectural governance for major AI initiatives: reviewing designs for coherence, scalability, security, cost, residency."* — BMO (**new 2026-11, banking**)

→ Covered by [`mod-309`](lessons/mod-309-governance-compliance-domain) (multi-regime regulated-domain architecture; balanced-menu healthcare/finance/public-sector/edtech) and [`project-302`](projects/project-302-regulated-domain-agent-architecture) (learner-selected sector plus a portability analysis showing which controls change under a different regime — this "no single sector is privileged" design is what carries the theme). New-sector-breadth this cycle (pharma, wealth-management, public sector with explicit EU-residency) reinforces the balanced-menu design; no delta. Deeper GRC depth in [`senior-ai-governance-architect-learning/mod-113-sector-and-jurisdiction-blueprints`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning).

### Theme 8 — Vendor-agnostic multi-framework fluency (37%, prior 46%)

Anchored by prior-cycle Slalom (Strands / OpenAI Agents SDK / Google ADK / LangGraph), Capital One (LangGraph / AutoGen / Semantic Kernel / CrewAI), Concentrix (LangGraph / ADK), Salesforce (agent ecosystems), OKX (AutoGPT / OpenAgents / LangGraph / LangFuse / Dify / Coze), NVIDIA (LangGraph / LangChain / MCP), Cognizant Enterprise (LangChain / LangGraph), Air India (multi-framework), Deloitte (Vertex AI / Gemini), Cognizant Principal Bedrock, PwC, Accommodations Plus, PLUS new-cycle phData (LangChain / LlamaIndex / MCP), Capgemini (Azure AI Foundry / OpenAI Services / Bedrock / Vertex AI / LangChain / LangGraph / Semantic Kernel / LlamaIndex), LPL (MCP / A2A). New-cycle broadening: Microsoft AI surfaces (BMO 'M365 Copilot, Copilot Studio, Fabric, Agent 365') now cited alongside the open-source menu.

→ **Framework mechanics** owned at L30 by [`agentic-ai-engineer-learning/mod-202-frameworks`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) (build the same agent across LangGraph/CrewAI/AutoGen; benchmark OpenAI Agents SDK / Google ADK / Claude Agent SDK / smolagents). L40 `senior-agentic-ai-engineer` also names framework fluency as a prerequisite. This L48 track's contribution is the **portability/lock-in architectural lens**: [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration) (protocol-boundary design that isolates the choice of framework) and [`project-303`](projects/project-303-extensible-agent-platform) (justify the extensible-platform choice against at least one alternative platform — Claude Code, Cursor, Copilot, LangGraph Platform, or custom — explicitly addressing portability and lock-in). Named as a prerequisite in [`PREREQUISITES.md`](PREREQUISITES.md); this track does not re-teach the mechanics.

### Theme 9 — Multi-cloud / hyperscaler architecture (44%, prior 42%)

Anchored by prior-cycle Cognizant (AWS/GCP), Deloitte (GCP + Vertex AI), Slalom (AWS + Azure + GCP), KPMG (Microsoft + AWS + GCP), Experian (ECS/EKS/service mesh/API gateway), Guidehouse (GovCloud), PwC (cloud + agentic), UiPath (hyperscaler AI services), Cognizant Principal Enterprise (AWS + GCP), Cognizant Principal Bedrock (AWS + OSS + cross-cloud), Concentrix (Gemini/Vertex), PLUS new-cycle Caterpillar (NVIDIA + cloud providers), Verizon AI Platform (multi-cloud strategy), Brady (GCP + Azure with unified IAM), phData (Bedrock + SageMaker + Azure AI/ML + Snowflake Cortex), Capgemini (Azure + AWS + GCP), BMO (AWS + Azure + MS AI surfaces), GSK (Azure OpenAI + Vertex AI private endpoints).

Representative quotes:
- *"Design and deliver AI and ML solutions across AWS, Azure, and GCP, using the right mix combination of cloud-native data services."* — Slalom
- *"Design and deliver enterprise-grade AI systems spanning Agentic AI, AWS Bedrock, and the full AI/ML spectrum."* — Cognizant (Principal Bedrock)
- *"Advise clients on TCO, deployment topology, and cross-cloud tradeoffs."* — Cognizant

→ **Covered implicitly** — the curriculum is cloud/vendor-neutral by design. Learners exercise cross-cloud tradeoffs in [`project-301`](projects/project-301-production-agentic-reference-architecture) (learner-selected reference architecture must justify its cloud/vendor choice against alternatives) and routing/cost architecture in [`mod-307/exercises/exercise-02-caching-and-routing-architecture`](lessons/mod-307-cost-latency-architecture). No explicit exercise comparing Bedrock ↔ Vertex ↔ Azure OpenAI ↔ Azure AI Foundry today. If this rises above 55% next cycle, propose extending [`project-301`](projects/project-301-production-agentic-reference-architecture) with a required "multi-cloud portability appendix" as a lightweight deliverable — no new module needed.

### Theme 10 — Evaluation infrastructure / harnesses / metrics at architecture level (41%, prior 42%)

Anchored by prior-cycle Slalom (MLOps/LLMOps), NVIDIA (eval harnesses + guardrail frameworks), Airtable (retrieval precision / hallucination rate metrics), Air India (evaluation-framework standards), Zoom (safety metrics), Gusto (quality safeguards), Capital One (red-team harnesses), Cognizant Principal, PwC, Accommodations Plus, Experian, PLUS new-cycle Caterpillar (MLOps and Model Lifecycle), OpenAI Gov (model evaluation), phData (evaluation strategies), LPL (groundedness/hallucination/safety/agent behavior metrics), BMO (evaluation/guardrail design), Banyan (evaluation frameworks).

→ Covered by [`mod-304`](lessons/mod-304-evaluation-harnesses) at the architecture level (trajectory-eval design, tool-call-correctness harness, LLM-as-judge rubric, eval-gated release pipeline). The new LPL metric vocabulary ("groundedness, hallucination, safety, and agent behavior") maps cleanly to existing mod-304 exercises. Build-level eval infrastructure at L40 [`senior-agentic-ai-engineer-learning/mod-402-eval-observability-infra`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning); specialist-eval depth at L30 [`ai-eval-engineer-learning`](https://github.com/ai-engineering-curriculum/ai-eval-engineer-learning).

### Theme 11 — Memory / context / RAG architecture (41%, prior 42%)

Anchored by prior-cycle Experian (memory + retrieval strategies), Airtable (retrieval accuracy + knowledge systems), Cognizant, Air India, Slalom, Accommodations Plus, Deloitte, Guidehouse, Cognizant Principal, PwC, Salesforce, PLUS new-cycle Brady (RAG), phData (context engineering), Capgemini (RAG + Vector DBs), BMO (RAG + agentic frameworks), Banyan (prompt + RAG), GSK (RAG and retrieval boundary patterns).

Representative quotes:
- *"Define and promote agentic AI architecture patterns, including multi-agent systems, tool orchestration, memory and retrieval strategies."* — Experian
- *"RAG and retrieval boundary patterns, embedding security and API security for AI services."* — GSK (**new 2026-11**)
- *"Architect intent routing, context assembly, and delegation between agents and domain services."* — LPL Financial (**new 2026-11**)

→ Covered by [`mod-303`](lessons/mod-303-memory-context-architecture) (context engineering, context-rot mitigation, memory-tier placement, RAG-as-architectural-concern). The new "retrieval boundary" framing (GSK) maps to mod-303 exercise-04 (rag-architecture-for-agents). RAG pipeline implementation is prerequisite: [`agentic-ai-engineer-learning/mod-203-rag-and-memory`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning); specialist depth in [`rag-engineer-learning`](https://github.com/ai-engineering-curriculum/rag-engineer-learning).

### Theme 12 — Tool integration / MCP / function calling architecture (32%, prior 38%)

Anchored by prior-cycle Air India (function-calling schemas, legacy-system tools), NVIDIA (MCP), Cognizant Principal (MCP + tool orchestration), Airtable (agent tool APIs), Gusto (tool orchestration patterns), Concentrix (agent orchestration & tool use), Slalom, Capital One (guardrail hooks/APIs), Deloitte (agentic design patterns), Cognizant, PLUS new-cycle phData (MCP), LPL (MCP + A2A), GSK (tool-calling scopes).

Representative quotes:
- *"Design secure Function Calling interfaces and Tool Definition schemas to enable agents to interact with legacy systems, SQL databases, and enterprise CRMs."* — Air India
- *"Experience with multi-agent patterns, memory, planning, and protocols (e.g. MCP)."* — phData (**new 2026-11**)
- *"Familiarity with agent protocols and frameworks: tool calling, MCP, A2A, multi-agent orchestration."* — LPL Financial (**new 2026-11**)
- *"Agent design patterns, LLM orchestration, RAG and retrieval boundaries, trust boundaries, tool-calling scopes and human-in-the-loop controls."* — GSK (**new 2026-11**)

→ Covered by [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration) and [`mod-310/exercises/exercise-02-secure-tool-use-and-context-hydration`](lessons/mod-310-agentic-developer-platforms). MCP-server authoring at L30 [`agentic-ai-engineer-learning/mod-202-frameworks/exercises/exercise-04-mcp-tool-server`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning). MCP is now universally-baseline rather than a differentiator; if MCP-tool-governance (MCP-server versioning, catalog, cross-server auth) becomes an explicit L48 concern in >50% of postings next cycle, consider a focused exercise under mod-310.

### Theme 13 — Publish / evangelize / architecture thought leadership (24%, prior 38%) ↓ DROPPED BELOW THRESHOLD

Still anchored by prior-cycle Capital One (both — conferences, blogs, office hours), Slalom (thought leadership), Anthropic (external representation, scalable enablement mechanisms), ServiceNow (both — voice-of-customer + feed into product), UiPath, Salesforce, KPMG (strategic vision publishing), Airtable, NVIDIA (partner workshops), Cognizant Principal Enterprise (roadmaps + POVs). Only Dentsu (prior-cycle) and OpenAI Gov (new-cycle, "Represent...at industry events and executive briefings") clearly add this cycle; the 10 new in-window postings lean toward INTERNAL pattern-library authorship instead, which falls under theme-02 rather than external evangelism.

Representative quote: *"Coach and evangelize — hosting architecture office hours, mentoring Staff, Principal and Senior engineers."* — Capital One.

→ **Not currently covered explicitly at L48.** Bundled in the architect-leadership-cluster `needs-research` below. Still part of the cluster even though the external-publishing framing dropped below threshold — it remains a durable aspect of senior-architect roles.

### Theme 14 — Enterprise integration / legacy systems (32%, prior 38%)

Anchored by prior-cycle Air India (legacy systems, SQL, CRMs), Deloitte (enterprise applications), Concentrix (data-estate integration), Airtable (APIs), Experian (integration architecture), Cognizant Principal (enterprise integration), PwC (workflow/systems), Guidehouse (mission systems), ServiceNow, Accommodations Plus (Java backends + AI-enabled systems), PLUS new-cycle Brady (legacy migration), GSK (AI services API security), Capgemini (multi-vendor environments).

→ Covered by [`mod-310/exercises/exercise-03-workflow-toolchain-integration`](lessons/mod-310-agentic-developer-platforms) (VCS, issue trackers, knowledge bases, CI/CD over REST/GraphQL/event-driven interfaces).

### Theme 15 — Vertical / domain-specific architecture (34%, prior 35%)

Anchored by prior-cycle UiPath (healthcare), Guidehouse (federal), Cognizant Bedrock (broad), Zoom (vertical agentic apps), OKX (crypto), Scotiabank (banking), Air India (aviation), Airtable (customer experience), Gusto (payroll), PLUS new-cycle Caterpillar (industrial physical AI), OpenAI Gov (public sector), LPL (wealth-management), BMO (banking), GSK (pharma).

→ Covered by [`project-302`](projects/project-302-regulated-domain-agent-architecture) — learner-selected sector from a balanced menu (healthcare, finance, public sector, edtech), with a portability analysis across regimes. The "no single sector is privileged" design is what carries the theme. New verticals this cycle (industrial physical AI, wealth-management, pharma with EU-residency) all map cleanly to the project-302 learner-choice design.

### Theme 16 — TCO / cost architecture / build-vs-buy at portfolio level (39%, prior 31%) ↑

Anchored by prior-cycle Cognizant (TCO/cross-cloud), Guidehouse (TCO + deployment topology + multi-cloud), PwC (target-state architecture + TCO + governance model), Cognizant Principal Bedrock (TCO + cross-cloud tradeoffs), Cognizant Enterprise (build-vs-buy at scale), Zoom (cost/latency/safety tradeoffs), Capital One (SLAs), Experian (velocity + reliability + cost + security balancing), PLUS new-cycle Caterpillar (MLOps cost), Verizon AI Platform (3-year TCO modeling), Brady (FinOps), phData, Capgemini, LPL (FinOps), BMO (cost residency), Banyan (keep the bill rational).

Representative quotes:
- *"Define TCO, deployment topology, and multi-cloud tradeoffs across GovCloud environments."* — Guidehouse
- *"Establish governance patterns for LLM cost, latency, and safety trade-offs."* — Zoom
- *"Advise senior client stakeholders on target-state architecture, TCO, and governance model."* — PwC
- *"Executing complex build-vs-buy analyses for platform components and develop comprehensive 3-year TCO models."* — Verizon AI Platform (**new 2026-11**)
- *"Lead LLMOps and AgentOps: versioning, deployment, monitoring, release management, FinOps."* — LPL Financial (**new 2026-11**)
- *"Continuously monitor cloud usage and implement FinOps best practices to optimize spend across our multi-cloud environment."* — Brady (**new 2026-11**)
- *"Own platform reliability, observability, and cost. Set SLOs, monitor usage, and keep the bill rational."* — Banyan Software (**new 2026-11**)

→ Covered by [`mod-307`](lessons/mod-307-cost-latency-architecture) (token-economics cost model, caching-and-routing architecture, cost/latency/quality budgets). Build-level cost defense at L40 [`senior-agentic-ai-engineer-learning/mod-403/02-token-and-latency-budgets`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning) and [`mod-404-reliability-cost-incident/02-cost-controls-and-budgets`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning). If this rises above 55% next cycle, extend `mod-307 exercise-01-token-economics-cost-model` to require a 3-year TCO model as deliverable — no new module.

### Theme 17 — Pre-sales / RFP / GTM enablement (27%, prior 31%) ↓ DROPPED BELOW THRESHOLD

Still anchored by prior-cycle Slalom (thought leadership + client-facing), KPMG (business development), Cognizant Principal (client engagement), Lenovo (pre-sales solution proposals), Anthropic (segment leads / partner engagements), ServiceNow (both — voice of customer + GTM readiness), PwC (engagement delivery), Concentrix (sales+delivery bridge), PLUS limited new-cycle presence at OpenAI Gov (account strategy), Capgemini (pursuit support), phData (consulting SA). The 10 new postings skew product/platform (Caterpillar, Brady, LPL, BMO, Banyan, GSK) which do not require pre-sales.

Representative quotes:
- *"Drive business development to expand KPMG's AI portfolio by identifying market opportunities."* — KPMG
- *"Support pre-sales engagements as a senior AI architecture authority, producing customer-facing solution proposals."* — Lenovo
- *"Partner with Account Directors on account strategy while owning the technical account plan, technical milestones, adoption priorities."* — OpenAI Gov (**new 2026-11**)

→ **Not curriculum-worthy universally at L48.** Dropped below threshold this cycle. Still concentrated at consulting shops and vendor-SA teams. Product/platform-team architects don't need it. Learners in consulting or vendor-SA tracks should pursue **external resources** (below) rather than an in-track module.

External resources for learners in consulting / vendor-SA sub-tracks:
- AWS Certified Solutions Architect – Associate (SAA-C03) — https://aws.amazon.com/certification/certified-solutions-architect-associate/
- Google Cloud Professional Cloud Architect — https://cloud.google.com/learn/certification/cloud-architect
- SPIN Selling (Neil Rackham) — canonical technical-discovery methodology used across SA/consulting practices — https://www.huthwaiteinternational.com/en/spin-selling
- Anthropic Applied AI blog — https://www.anthropic.com/customers (representative client-facing agentic architecture writeups)

### Theme 18 — Observability & tracing (34%, prior 27%) ↑ CROSSED ABOVE THRESHOLD

Newly above threshold this cycle. Anchored by prior-cycle Accommodations Plus (drift detection), Cognizant Principal, Capital One, Airtable (observability + retrieval-accuracy instrumentation), NVIDIA, Gusto, Zoom, PLUS new-cycle Caterpillar (DCGM / Prometheus / Grafana / Loki, SRE practices, SLOs), Verizon AI Platform (observability requirements), Brady (continuously monitor cloud usage), phData (observability strategies for LLM and agent systems), LPL (LLMOps and AgentOps: monitoring, release management), BMO (AI observability), Banyan (platform reliability, observability, and cost; set SLOs).

Representative quotes:
- *"Observability, Reliability, and Security – DCGM / Prometheus / Grafana / Loki, SRE practices and SLOs."* — Caterpillar (**new 2026-11**)
- *"Own platform reliability, observability, and cost. Set SLOs, monitor usage, and keep the bill rational."* — Banyan Software (**new 2026-11**)
- *"Deep AI/ML and GenAI solution architecture: ... AI observability."* — BMO (**new 2026-11**)

→ Covered by [`mod-305-observability-tracing`](lessons/mod-305-observability-tracing) — OpenTelemetry GenAI semantic conventions, stable trace identity across retries and long-running sessions, quality/drift signals, platform evaluation (LangSmith, Langfuse, Arize Phoenix). Fleet-level operational-observability implementation remains at L40 [`senior-agentic-ai-engineer-learning/mod-402-eval-observability-infra`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning). No delta — ownership was already correctly placed.

### Theme 20 — Design authority / architecture review board / gate reviews (32%, prior 23%) ↑ CROSSED ABOVE THRESHOLD

Newly above threshold this cycle. Anchored by prior-cycle Experian (arch reviews with binding decisions), Scotiabank (design-authority review cadence), Concentrix (deep-dive arch reviews), Accommodations Plus (ARBs, Gate 0/Gate 1 estimates), Cognizant (arch strategy), Zoom (arch reviews for high-risk deployments), PLUS new-cycle Caterpillar (architectural standards across platform teams), Verizon AI Platform (lead component reviews; formal layer boundaries; interface contracts), OpenAI Gov (use-case portfolio with decision criteria), Capgemini (architectural governance and decision-making), LPL Financial (architecture review cycles across Enterprise Architecture and risk forums), BMO (architectural governance for major AI initiatives), GSK (binding AI security standards...escalating where a design cannot meet them; "Your specifications are what Engineering builds from").

Representative quotes:
- *"Lead component reviews and provide consultative oversight for Business Unit agent architectures to ensure platform alignment."* — Verizon AI Platform (**new 2026-11**)
- *"Represent AI designs in architecture review cycles across Enterprise Architecture and risk forums."* — LPL Financial (**new 2026-11**, paraphrased)
- *"Your specifications are what Engineering builds from, and if they are ambiguous the build is wrong."* — GSK (**new 2026-11**)
- *"Singular architectural oversight across the AI Engineering function and across Cloud AI and Workspace Engineering for all AI surfaces."* — BMO (**new 2026-11**)

→ **Bundled in the architect-leadership-cluster `needs-research` below.** Crossing above threshold REINFORCES the cluster's stakes for the 2026-12 human-decision cycle but does not create a new technical gap this cycle — the architectural spine (mod-301..310) remains complete.

## Uncovered signal cluster — architect leadership & influence at L48

Four themes cluster together and are not currently covered by this L48 track. **REINFORCED this cycle** — aggregate frequency rose from ~62% to ~68%:

| Component theme | Freq (this cycle) | Prior | Above threshold? |
|---|---|---|---|
| C-suite / executive stakeholder advisory & influence (theme-03) | **54%** | 62% | Yes |
| Mentor architects / practice-level capability building (theme-05) | **46%** | 50% | Yes |
| Design authority / ARB / gate reviews (theme-20) | **32%** | 23% | **YES (newly crossed)** |
| Publish / evangelize / architecture thought leadership (theme-13) | 24% | 38% | No (newly dropped) |

Postings cite these components heavily overlapping (Capital One's Distinguished JDs name all four; Scotiabank's Chief AI Architect names three; Cognizant's Principal Enterprise Architect names three; Slalom, ServiceNow, Anthropic, Air India, UiPath name at least two; new-cycle BMO, Banyan, Capgemini, LPL, GSK each name multiple). The **union frequency** — postings citing at least one component — is ~68% of the sample (up from ~62%).

**Decision this cycle: NO DELTA.** Reasons:

1. This is a **curriculum-scope-boundary question, not a market shift**. The L48 curriculum was authored (June 2026) as a deliberate **technical-architecture spine** — see [README.md](README.md) — leaving leadership/influence content out of scope by intent, not by omission. The REINFORCEMENT this cycle (aggregate 62% → 68%; theme-20 crossing above threshold) raises the stakes but does not reframe the scope question.
2. **Sibling generic-architect tracks may already own this terrain.** Relevant candidates: [`senior-ai-governance-architect-learning/mod-112-program-design-and-org-shape`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning) (which covers program design and org shape at governance-architect altitude), [`ai-infra-senior-architect-learning`](https://github.com/ai-infra-curriculum/ai-infra-senior-architect-learning), and [`cto-curriculum`](https://github.com/ai-infra-curriculum/cto-curriculum) (which owns executive AI-strategy conversations). Under the ownership rule, if a sibling track owns generic architect leadership, this L48 track should link there rather than duplicate.
3. Under strict continuity bias, **PREFER ZERO ADDITIONS over weakly-justified ones** — and adding a leadership module without first confirming sibling coverage is exactly the kind of ill-scoped addition the packet warns against.

**Recommendation for next cycle (2026-12):** Humans decide between three options:

- **(a)** Add a lightweight L48 module `mod-311-architect-leadership-influence` (~10 hours, 3–4 exercises: exec brief drafting for CIO/CAIO, ARB defense simulation / design-authority-as-contract, architect mentoring/coaching plan, publishing an agentic-architecture POV). +9.4% additions on module count — within the 20% cap. The new-cycle evidence quotes (GSK "Your specifications are what Engineering builds from"; Verizon "formal layer boundaries, interface contracts"; LPL "architecture review cycles across Enterprise Architecture and risk forums") provide sharp material for a design-authority-as-contract exercise.
- **(b)** Route the theme to a sibling track (`senior-ai-governance-architect-learning`, `ai-infra-senior-architect-learning`, or `cto-curriculum`) and link out from this L48 track's PREREQUISITES / README.
- **(c)** Keep out of scope; document as an explicit non-goal with external-resource pointers (e.g., the *Staff Engineer's Path* — Larson; *The Software Architect Elevator* — Hohpe; the SEI SATURN and O'Reilly Software Architecture Conf archives for design-authority patterns).

## Themes just below threshold this cycle

### Central platform / paved-road / shared-service (29%, prior 23%)

Climbing. Anchored by prior-cycle Capital One (both), Experian (cloud-native platform), Gusto (reusable patterns), Slalom, Zoom, Anthropic, PLUS new-cycle Caterpillar (reference architectures and standards across platform teams), Verizon AI Platform (enterprise reference architecture library), Brady (enterprise AI platform architecture), LPL (centralized AI Hub platform), BMO (singular architectural oversight), Banyan (patterns for a multi-company portfolio).

→ Covered by [`mod-310-agentic-developer-platforms`](lessons/mod-310-agentic-developer-platforms) and [`project-303-extensible-agent-platform`](projects/project-303-extensible-agent-platform). If it crosses 30% next cycle, no delta required (already owned); verify mod-310 exercises still map cleanly.

### Human-in-the-loop / approval boundaries (15%, stable)

Anchored by Gusto (HITL protocols, escalation logic), Accommodations Plus, KPMG (risk management), Guidehouse (mission risk), PLUS new-cycle LPL Financial ("human-in-the-loop controls and advisory-only boundaries so no unintended automated actions occur" — regulated finance context) and GSK ("human-in-the-loop controls" — pharma context).

→ Covered by [`mod-306`](lessons/mod-306-guardrails-safety-security) (excessive-agency controls, human-approval-for-high-risk-actions) and [`mod-308/exercises/exercise-02-hitl-approval-architecture`](lessons/mod-308-deployment-durable-execution) (approve/edit/reject/respond flows with state persistence). The new LPL "advisory-only" framing for regulated advice is a particularly sharp variant of HITL already encompassed by the mod-308 exercise design.

### EU-data-residency / sovereign-inference architecture (25%, new signal)

Newly-identified this cycle. Anchored by prior-cycle Guidehouse (GovCloud), Scotiabank (banking residency), UiPath (healthcare), Deloitte (EU+APAC), Accommodations Plus (PCI/PII), PLUS new-cycle GSK ("network designs that keep an inference call inside the EU"), BMO ("residency" across AWS+Azure), OpenAI Gov (Munich/London EU posting with explicit public-sector compliance framing).

Representative quotes:
- *"Azure OpenAI and Vertex AI private endpoint and customer-managed-key patterns, and the network designs that keep an inference call inside the EU."* — GSK (**new 2026-11**)
- *"Provide architectural governance for major AI initiatives: reviewing designs for coherence, scalability, security, cost, residency."* — BMO (**new 2026-11**)

→ Architectural placement already carried by [`mod-309/exercises/exercise-05-data-handling-residency-design`](lessons/mod-309-governance-compliance-domain) + [`project-302`](projects/project-302-regulated-domain-agent-architecture). If it crosses 40% next cycle, extend mod-309 exercise-05 with a sovereign-inference worked example (private endpoints, customer-managed keys, in-region inference) — no new module.

## Out-of-scope / linked-out themes

For requirements that belong at another rung per the ownership rule, we link out rather than duplicating.

| Theme | Link |
|---|---|
| Agent framework mechanics (LangGraph, CrewAI, AutoGen, OpenAI Agents SDK, Google ADK, Claude Agent SDK) | [`agentic-ai-engineer-learning/mod-202-frameworks`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) |
| RAG pipeline mechanics, embeddings, rerankers, vector DBs | [`agentic-ai-engineer-learning/mod-203-rag-and-memory`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning); depth in [`rag-engineer-learning`](https://github.com/ai-engineering-curriculum/rag-engineer-learning) |
| Single-agent evaluation / trajectory + tool-call grading | [`agentic-ai-engineer-learning/mod-205-evaluation-observability`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning); depth in [`ai-eval-engineer-learning`](https://github.com/ai-engineering-curriculum/ai-eval-engineer-learning) |
| Guardrail *implementation* basics (I/O moderation, prompt-injection defenses, tool-permission enforcement) | [`agentic-ai-engineer-learning/mod-206-guardrails-implementation`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning); frontier-safety depth in [`agentic-safety-engineer-learning`](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) |
| Production-hardening of agent systems (SLOs, incident response, cost defense on live traffic) | [`senior-agentic-ai-engineer-learning/mod-404-reliability-cost-incident`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning) |
| Technical-leadership at the *engineer* rung (mentoring engineers, agent-specific code review, paved roads for internal engineering teams) | [`senior-agentic-ai-engineer-learning/mod-405-technical-leadership`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning) |
| AIMS / policy-as-code / control-library architecture / audit-architecture depth | [`senior-ai-governance-architect-learning`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning) |
| Frontier-safety depth (dangerous-capability evals, jailbreak engineering, control evaluation) | [`agentic-safety-engineer-learning`](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) |
| Pre-sales / RFP / SA-style solution selling | External: AWS SAA, GCP Professional Cloud Architect, SPIN Selling (Rackham) |
| Executive-level AI strategy (as-a-CTO) | [`cto-curriculum`](https://github.com/ai-infra-curriculum/cto-curriculum) (candidate owner — pending scope-boundary decision on the architect-leadership cluster) |
| Agent modeling / SFT / RLHF / LoRA / synthetic data | [`ml-engineering-curriculum`](https://github.com/ml-engineering-curriculum) tracks |

## Conclusion

<!-- needs-research: for the 2026-12 cycle, humans should decide the SCOPE-BOUNDARY question on architect-leadership-and-influence. REINFORCED this cycle: aggregate union frequency 62% → 68%; theme-20 (design authority / ARB) crossed above threshold (23% → 32%); theme-13 (publish/evangelize) dropped below threshold (38% → 24%) but stays in cluster. Updated component frequencies: executive advisory ~54%, practice mentoring ~46%, design authority / ARB ~32%, publish/evangelize ~24%. Options unchanged: (a) add a lightweight mod-311-architect-leadership-influence to this L48 track — new-cycle GSK/Verizon/LPL quotes provide sharp material for a design-authority-as-contract exercise — (b) route to a sibling generic-architect track (senior-ai-governance-architect-learning/mod-112, ai-infra-senior-architect-learning, or cto-curriculum), or (c) keep out of scope with external-resource pointers. The signal remains strong and strengthening; the question is where it belongs. Still not a technical-market-shift signal — the requirement existed at curriculum design time and was omitted by intent. -->

<!-- needs-research: watch multi-cloud/hyperscaler-architecture — ~44% this cycle (up from ~42%). If it crosses 55% next cycle, extend project-301 with a required multi-cloud portability appendix (still no new module). If it stays 40–55%, defer. The AWS+Azure+Microsoft-AI-surfaces pairing (BMO Agent 365 / Copilot Studio) is now showing up explicitly — track whether this is a durable pattern. -->

<!-- needs-research: central-platform / paved-road / shared-service-agentic-architecture — 29% this cycle (up from 23%, likely to cross 30% next cycle). If it crosses 30%, no delta required (already owned by mod-310 + project-303) but re-verify the exercises still map cleanly to the emerging pattern-library-as-RFC pattern (GSK, Verizon, phData). -->

<!-- needs-research: new 2026-11 sub-threshold signal — EU-data-residency / sovereign-inference architecture (~25%, GSK + BMO + OpenAI Gov). Architectural placement already carried by mod-309 exercise-05 (data-handling-residency-design). If it crosses 40% next cycle, extend mod-309 exercise-05 with a sovereign-inference worked example (private endpoints, customer-managed keys, in-region inference). No new module. -->

<!-- needs-research: TCO / build-vs-buy rose from ~31% to ~39% this cycle driven by Verizon's "3-year TCO models" template. If it crosses 55% next cycle, extend mod-307 exercise-01-token-economics-cost-model to require a 3-year TCO model as deliverable. No new module. -->

<!-- needs-research: MCP is now universally-baseline rather than a differentiator (>40% of new in-window postings cite it explicitly). Still covered by mod-302 exercise-03 and mod-310 exercise-02. If MCP-tool-governance (versioning MCP servers, MCP-server catalog, cross-MCP-server auth) becomes an explicit L48 architectural concern in >50% of postings next cycle, consider a focused exercise under mod-310 on MCP tool-governance. No delta required this cycle. -->

<!-- needs-research: new 2026-11 sub-threshold signals (watch only, below cap for curriculum action): (a) Physical AI / autonomy-at-scale architect (~9%, Caterpillar) — adjacent to the chat-architect pool; consider whether a sibling robotics-/embodied-AI-architect rung should be scoped if it crosses 15% next cycle. (b) Portfolio/holdco multi-company architecture (~8%, Banyan) — adjacent-to-architect-altitude; may become curriculum-worthy if private-equity holdco patterns multiply. -->

The `mod-301..310` architecture spine continues to cover every job-market requirement that clears the continuity-bias thresholds at L48 altitude. The 2026-11 incremental refresh (41 postings; +10 new, 11 retained from prior cycle) confirms this: no theme crossed into *unowned* territory. Two themes crossed above threshold this cycle — *observability & tracing* (27% → 34%, already owned by mod-305) and *design authority / ARB / gate reviews* (23% → 32%, bundled in the architect-leadership cluster needs-research). Two themes dropped below — *publish/evangelize* (38% → 24%, still in the cluster) and *pre-sales* (31% → 27%, still linked out). Theme 16 (TCO / build-vs-buy) jumped from 31% to 39% but remains covered by mod-307. Build-fundamentals (framework mechanics, RAG implementation, single-agent evaluation, guardrail implementation) stay owned by the L30 `agentic-ai-engineer-learning` / `rag-engineer-learning` / `ai-eval-engineer-learning` tracks and are named as prerequisites. Production-hardening build skills stay owned by the L40 `senior-agentic-ai-engineer-learning` track. Sibling architect tracks (`agentic-safety-engineer-learning`, `senior-ai-governance-architect-learning`) are linked as adjacent, not duplicated. **No delta is proposed this cycle.** The one genuine uncovered signal — architect leadership & influence — is REINFORCED this cycle (aggregate 62% → 68%; theme-20 newly above threshold) and remains flagged for human review in the 2026-12 cycle. The MCP, EU-residency, 3-year-TCO, pattern-library-as-RFC, physical-AI, and portfolio-holdco signals are watch items only.
