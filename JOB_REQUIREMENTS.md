# Job Requirements — Agentic Systems Architect

**Role level:** 48 (design-altitude architect rung — top of the individual-contributor architect stack for production agentic AI systems)
**Track:** `agentic-systems-architect-learning`
**Research window:** 2026-06-10 → 2026-09-08 (last 90 days)
**Today:** 2026-09-08
**Prior refresh:** none — this is the first job-requirements pass for this role.

This file maps verbatim requirements from current L48-altitude agentic-architect job postings to the existing curriculum. Raw normalized data lives in [`.aicg/job-requirements.json`](.aicg/job-requirements.json); the strictly-additive proposal lives in [`.aicg/curriculum-plan-delta.json`](.aicg/curriculum-plan-delta.json).

## Summary

- Postings sampled: **26** (all in the 2026-06-10 → 2026-09-08 window, one 7 days outside window_start retained because it was active in-window).
- Equivalent titles counted per research packet: `Agentic Systems Architect`, `Agentic AI Architect`, `AI Agent Architect`, `Solution Architect - Agentic AI`, `Multi-Agent Systems Architect`, `Principal AI Engineer - Agents` — plus close-adjacent architect-altitude titles (`Distinguished Engineer / Distinguished AI Engineer (Agentic Platform)`, `Principal AI Architect / Principal Enterprise Architect (AI, majority-agentic)`, `Chief AI Architect`, `Head of Applied AI Architecture`, `Staff AI Architect`, `Agentic Operations Architect`).
- **Proposed delta this cycle: 0 modules, 0 exercises, 0 projects.** Every load-bearing theme (≥ 30% frequency AND ≥ 3 distinct postings) either (a) is already owned by an existing L48 module (mod-301..310) or an existing L48 project, (b) belongs at a lower L30/L40 rung and is linked as a prerequisite, or (c) belongs at a sibling architect track and is linked out.
- The **strongest uncovered signal cluster** is *architect leadership & influence at L48* — executive stakeholder advisory (**62%**), practice-level mentoring of architects (50%), architecture thought leadership / publishing (38%), and design-authority / ARB participation (23%). This cluster is a **curriculum-scope-boundary question, not a market-drift signal** — the L48 curriculum was designed by intent as a technical-architecture spine; leadership content may belong to sibling generic-architect tracks (e.g., `senior-ai-governance-architect-learning/mod-112-program-design-and-org-shape`, `ai-infra-senior-architect-learning`, `cto-curriculum`). Flagged `needs-research` for next cycle so humans can decide whether to add a lightweight L48 leadership module or defer to siblings.
- **Sub-threshold new signals also tracked:** *multi-cloud / hyperscaler architecture* (42%) is above threshold but implicitly covered — the curriculum is cloud/vendor-neutral by design; if it rises above 55% next cycle, extend `project-301` with a required multi-cloud portability appendix rather than a new module. *Pre-sales / RFP / GTM enablement* (31%) is a sub-role specialization (consulting-shop/vendor-SA path) that is not universal at L48 — link out to external SA-training resources instead.

## Methodology

- Sources: `job-boards.greenhouse.io` (Anthropic, Airtable, OKX), `jobs.smartrecruiters.com` (ServiceNow, Experian), `careers.cognizant.com`, `builtin.com`, `jobs.lenovo.com`, `careers.airindia.com`, `pwc.wd3.myworkdayjobs.com`, `guidehouse.wd1.myworkdayjobs.com`, `apply.deloitte.com`, `kpmguscareers.com`, `capitalonecareers.com`, `careers.zoom.us`, `himalayas.app`, `ats.rippling.com`, `jobs.ashbyhq.com`, `jobs.scotiabank.com`, `jobs.nvidia.com`, `careers.salesforce.com`, `linkedin.com/jobs`, and secondary aggregators (Built In, jobright, remoterocketship) for Google-snippet triangulation where SPAs blocked WebFetch.
- Per-posting capture: employer, title, URL, `date_observed`, `date_posted` (marked `estimated:YYYY-MM` when only "posted N days/weeks ago" was visible), location, 6–10 verbatim/near-verbatim requirement quotes prioritized on **L48-distinguishing altitude** — reference-architecture ownership, portfolio/practice scope, C-suite advisory, authored standards, mentoring of architects, cross-team/cross-organization influence, TCO/multi-cloud tradeoffs, governance embedded at architecture — NOT L30 build fundamentals which would double-count against lower-rung tracks.
- Frequency = distinct in-window postings citing the theme ÷ 26 in-window postings.
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
| 1 | Multi-agent orchestration architecture (patterns, coordination, tool interfaces) | **85%** | `agentic-systems-architect` (this) | [`mod-301`](lessons/mod-301-agentic-systems-foundations), [`mod-302`](lessons/mod-302-multi-agent-orchestration), [`project-301`](projects/project-301-production-agentic-reference-architecture) |
| 2 | Reference architectures & reusable solution blueprints as first-class deliverable | **73%** | `agentic-systems-architect` (this) | [`mod-301/exercises/exercise-04-reference-architecture-teardown`](lessons/mod-301-agentic-systems-foundations), [`project-301`](projects/project-301-production-agentic-reference-architecture), [`project-303`](projects/project-303-extensible-agent-platform) |
| 3 | C-suite / executive stakeholder advisory & influence | **62%** | under-review — L48 candidate or sibling generic-architect track | **Not currently covered explicitly.** Bundled in the architect-leadership-cluster `needs-research` (see below). |
| 4 | AI governance frameworks embedded in architecture (responsible AI, model risk, regulatory compliance) | **58%** | `agentic-systems-architect` (this) | [`mod-309`](lessons/mod-309-governance-compliance-domain), especially `exercise-01-horizontal-framework-controls-mapping` and `exercise-04-governance-accountability-spec` |
| 5 | Mentor architects / develop architectural capability at practice level | **50%** | under-review — L48 candidate or sibling generic-architect track | **Not currently covered explicitly.** L40 `senior-agentic-ai-engineer-learning/mod-405` owns mentoring of ENGINEERS; mentoring of ARCHITECTS is a distinct L48 skill. Bundled in the architect-leadership-cluster `needs-research`. |
| 6 | Guardrails architecture (prompt injection defense, guardrail services, red-team harnesses) | **50%** | `agentic-systems-architect` (this) — architectural placement; `agentic-safety-engineer` for frontier-safety depth | [`mod-306`](lessons/mod-306-guardrails-safety-security). Cross-link to [`agentic-safety-engineer-learning`](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) for dangerous-capability evals, jailbreak engineering, and frontier-monitor design. |
| 7 | Regulated-domain architecture (healthcare/finance/PCI/HIPAA/FedRAMP/banking/crypto/aviation) | **50%** | `agentic-systems-architect` (this) | [`mod-309`](lessons/mod-309-governance-compliance-domain), [`project-302`](projects/project-302-regulated-domain-agent-architecture) (learner-selected sector). Deeper GRC/AIMS depth in [`senior-ai-governance-architect-learning`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning). |
| 8 | Vendor-agnostic multi-framework fluency (LangGraph, ADK, OpenAI Agents SDK, Claude Agent SDK, AutoGen, CrewAI, Semantic Kernel, Strands, MCP) | **46%** | `agentic-ai-engineer` (L30) — build mechanics; `agentic-systems-architect` (L48) — portability/lock-in tradeoffs | **Prerequisite:** [`agentic-ai-engineer-learning/mod-202-frameworks`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) for framework mechanics. L48 architectural lens (MCP/A2A protocol integration, platform-portability analysis) in [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration) and [`project-303`](projects/project-303-extensible-agent-platform) (justify against alternative platform). |
| 9 | Multi-cloud / hyperscaler architecture (AWS + Azure + GCP for agentic AI) | **42%** | `agentic-systems-architect` (this) | Implicitly covered — the curriculum is cloud/vendor-neutral by design. Learners exercise cross-cloud tradeoffs in [`project-301`](projects/project-301-production-agentic-reference-architecture) and routing architecture in [`mod-307/exercises/exercise-02-caching-and-routing-architecture`](lessons/mod-307-cost-latency-architecture). See "Themes just below threshold" below for the sub-cycle plan. |
| 10 | Evaluation infrastructure / harnesses / metrics at architecture level | **42%** | `agentic-systems-architect` (this) — architecture strategy; `senior-agentic-ai-engineer` (L40) — build infrastructure; `ai-eval-engineer` (L30) — specialist evaluation | [`mod-304`](lessons/mod-304-evaluation-harnesses). Build-level eval infrastructure at L40 [`mod-402-eval-observability-infra`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning). Specialist-eval depth at L30 [`ai-eval-engineer-learning`](https://github.com/ai-engineering-curriculum/ai-eval-engineer-learning). |
| 11 | Memory / context / RAG architecture as architectural concern | **42%** | `agentic-systems-architect` (this) — architectural placement; `rag-engineer` (L30) + `agentic-ai-engineer` (L30) — implementation | [`mod-303`](lessons/mod-303-memory-context-architecture). RAG pipeline implementation is prerequisite: [`agentic-ai-engineer-learning/mod-203-rag-and-memory`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) and specialist depth in [`rag-engineer-learning`](https://github.com/ai-engineering-curriculum/rag-engineer-learning). |
| 12 | Tool integration / MCP / function calling architecture (tool schemas as architectural interface) | **38%** | `agentic-systems-architect` (this) | [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration), [`mod-310`](lessons/mod-310-agentic-developer-platforms) especially `exercise-02-secure-tool-use-and-context-hydration`. MCP-server authoring at L30 [`agentic-ai-engineer-learning/mod-202-frameworks/exercises/exercise-04-mcp-tool-server`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning). |
| 13 | Publish / evangelize / architecture thought leadership (conferences, blogs, POVs, office hours) | **38%** | under-review — L48 candidate or sibling generic-architect track | **Not currently covered explicitly.** Bundled in the architect-leadership-cluster `needs-research`. |
| 14 | Enterprise integration / legacy systems / API bridging | **38%** | `agentic-systems-architect` (this) | [`mod-310/exercises/exercise-03-workflow-toolchain-integration`](lessons/mod-310-agentic-developer-platforms) |
| 15 | Vertical / domain-specific architecture (industry expertise as architectural input) | **35%** | `agentic-systems-architect` (this) | [`project-302`](projects/project-302-regulated-domain-agent-architecture) (learner-selected sector — the balanced-menu design is what carries this theme) |
| 16 | TCO / cost architecture / build-vs-buy at portfolio level | **31%** | `agentic-systems-architect` (this) | [`mod-307`](lessons/mod-307-cost-latency-architecture). Build-level cost defense at L40 [`mod-403/02-token-and-latency-budgets`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning). |
| 17 | Pre-sales / RFP / GTM enablement (customer-facing sales engineering) | **31%** | not-curriculum-worthy universally — sub-role specialization | **Link out.** Concentrated at consulting shops (Slalom, KPMG, PwC, Lenovo pre-sales) and vendor-SA roles (NVIDIA, Anthropic Applied AI). Product-team architects (Airtable, Gusto, Experian, Airline) don't need it. External resources: AWS SAA, GCP Professional Cloud Architect certifications, and SPIN Selling (Rackham) for the advisory-discovery pattern. |
| 18 | Observability & tracing (fleet-level, drift detection, monitoring) | 27% | `agentic-systems-architect` (this) | [`mod-305`](lessons/mod-305-observability-tracing) — covered; sub-threshold this cycle, no delta. |
| 19 | Central platform / paved-road / shared-service agentic architecture | 23% | `agentic-systems-architect` (this) | [`mod-310`](lessons/mod-310-agentic-developer-platforms), [`project-303`](projects/project-303-extensible-agent-platform) |
| 20 | Design authority / architecture review board / gate reviews for agentic changes | 23% | under-review | Bundled in the architect-leadership-cluster `needs-research`. |
| 21 | Human-in-the-loop / approval boundaries in architecture | 15% | `agentic-systems-architect` (this) | [`mod-306`](lessons/mod-306-guardrails-safety-security), [`mod-308/exercises/exercise-02-hitl-approval-architecture`](lessons/mod-308-deployment-durable-execution) |

## Posting evidence for load-bearing themes

The tables below list postings anchoring each ≥ 30% theme. All 26 sampled postings fall within 2026-06-10 → 2026-09-08 (one is 7 days outside window_start; noted).

### Theme 1 — Multi-agent orchestration architecture (85%)

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

Representative quotes:
- *"Architect multi-agent orchestration pipelines."* — Cognizant (Principal AI Architect)
- *"Design end-to-end agentic AI architectures including planning loops, memory management, tool integration, and agent coordination patterns."* — Slalom
- *"Architect multi-agent systems (MAS) and frameworks to support goal-directed, reasoning, planning, and reinforcement-learning-based agents."* — OKX
- *"Design comprehensive system architectures for vertical Agentic AI applications."* — Zoom
- *"Design and optimize how AI agents reason, retrieve, decide, and act — architecting the knowledge systems, decision logic, and guardrails."* — Airtable

→ Covered by [`mod-301`](lessons/mod-301-agentic-systems-foundations) (workflow-vs-agent decomposition; orchestration-pattern catalog) and [`mod-302`](lessons/mod-302-multi-agent-orchestration) (orchestrator-worker topology, handoffs vs. manager-as-tools, MCP/A2A protocols, escalation design), integrated end-to-end in [`project-301`](projects/project-301-production-agentic-reference-architecture).

### Theme 2 — Reference architectures & reusable solution blueprints (73%)

Anchored by Cognizant, Air India, Guidehouse, Slalom, Capital One (both), Deloitte, Lenovo, Zoom, Concentrix, ServiceNow (both), Experian, Scotiabank, PwC, NVIDIA, Salesforce, Cognizant Principal Bedrock, Cognizant Principal Enterprise, KPMG, Accommodations Plus.

Representative quotes:
- *"Develop reference architectures for AI solutions across regulated industries."* — Zoom
- *"Define the multi-engagement technical direction, reference architectures, reusable deployment patterns."* — ServiceNow (FDE Lead)
- *"Produce reusable solution IP for Lenovo's agentic AI offering portfolio: reference architectures, solution blueprints."* — Lenovo
- *"Build hands-on proofs-of-concept and reference architectures that serve as blueprints for production-grade generative AI pipelines."* — NVIDIA
- *"Define canonical reference architectures, solution patterns, and integration blueprints that govern how GenAI, agentic AI, and ML capabilities are assembled."* — Scotiabank
- *"You will contribute to the north star platform architecture, continuously publishing and refining living diagrams and canonical APIs."* — Capital One

→ Covered by [`mod-301/exercises/exercise-04-reference-architecture-teardown`](lessons/mod-301-agentic-systems-foundations) (analyze existing reference architectures), [`project-301`](projects/project-301-production-agentic-reference-architecture) (produce an end-to-end reference architecture with ADR set, diagrams, eval plan, cost model, threat model), and [`project-303`](projects/project-303-extensible-agent-platform) (produce reusable extension architecture and adoption/DX plan — the "canonical patterns others adopt" deliverable).

### Theme 3 — C-suite / executive stakeholder advisory & influence (62%)

Anchored by Cognizant, Slalom, Capital One (both), Deloitte, KPMG, Zoom, ServiceNow (both), Experian, Concentrix, Anthropic, UiPath, PwC, Scotiabank, Cognizant Principal Enterprise, Air India.

Representative quotes:
- *"Serve as senior technical voice in customer executive conversations."* — Zoom
- *"Act as a trusted advisor to senior and C-level client stakeholders, shaping AI strategies."* — KPMG
- *"Serve as a trusted advisor to healthcare executives on AI, automation, agentic transformation, and enterprise technology strategy."* — UiPath
- *"Lead and mentor multiple engineering teams and influence cross-functional stakeholders up to the VP level."* — Capital One (Distinguished)
- *"Represent Anthropic externally with senior leaders at foundations, nonprofits, research institutions."* — Anthropic
- *"Operating as a technical peer to technology executives influencing platform investment decisions."* — Scotiabank
- *"Explain model and system behavior to both technical and non-technical audiences, including leading deep technical presentations."* — Slalom

→ **Not currently covered explicitly at L48.** See "Uncovered signal cluster — architect leadership & influence" below.

### Theme 4 — AI governance frameworks embedded in architecture (58%)

Anchored by Cognizant, Air India, Slalom, Deloitte, Zoom, KPMG, UiPath, Accommodations Plus, Guidehouse, OKX, Scotiabank, Gusto, Capital One, PwC.

Representative quotes:
- *"Define governance frameworks ensuring responsible AI usage, security, explainability, and regulatory compliance."* — Cognizant / Air India
- *"Establish governance patterns for LLM cost, latency, and safety trade-offs."* — Zoom
- *"Advise clients on AI Risk Management, Governance, and Security."* — KPMG
- *"In partnership with AppSec and risk functions, you embed security, PCI/PII compliance, and responsible AI controls into architectural defaults — structural, not bolted on."* — Accommodations Plus
- *"Translate regulatory requirements into architecture controls embedded in solution designs at inception."* — Scotiabank

→ Covered by [`mod-309`](lessons/mod-309-governance-compliance-domain) (horizontal framework controls mapping, multi-regime regulated-domain architecture, extension-tool governance lifecycle, governance-accountability spec, data-handling/residency design). Deeper AIMS/policy-as-code/audit-architecture depth belongs to the sibling [`senior-ai-governance-architect-learning`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning) track; that is a different rung, not a duplicate.

### Theme 5 — Mentor architects / architectural-capability building (50%)

Anchored by Cognizant, Cognizant Principal Enterprise, Anthropic, Air India, Capital One (both), Scotiabank, Experian, OKX, Accommodations Plus, KPMG, Slalom.

Representative quotes:
- *"Mentor architects, technology leads, and engineering teams while promoting architecture best practices and engineering excellence."* — Cognizant (Principal Enterprise Architect)
- *"Set architectural direction and build architectural capacity by developing architects from Senior to Principal levels."* — Scotiabank
- *"Coaching and mentoring Staff, Principal and Senior engineers, authoring technical design documents and blogs."* — Capital One (Distinguished)
- *"Provide architectural leadership to AI engineers, LLM engineers, and data engineers."* — Air India
- *"You raise the architectural thinking of senior engineers and tech leads through direct engagement, clear documentation, and collaborative design."* — Accommodations Plus

→ **Not currently covered explicitly at L48.** Distinct from L40 [`senior-agentic-ai-engineer-learning/mod-405-technical-leadership`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning) (which mentors engineers). Bundled in the "architect leadership & influence" uncovered signal cluster below.

### Theme 6 — Guardrails architecture (50%)

Anchored by Capital One (both), Air India, Cognizant, Slalom, Deloitte, Airtable, Accommodations Plus, NVIDIA, ServiceNow (FDE), OKX, Gusto, Concentrix, Zoom.

Representative quotes:
- *"Trust and safety remain paramount; you will help bring together a vision of central guardrail services — prompt firewalls, content-filter hooks, red team harnesses and audit APIs — consumed by every application."* — Capital One
- *"Manage AI safety and trust; establish guardrails to keep resolution rates high while failure rates stay low; responsible for edge cases, prompt injection defense, and preventing unintended behaviors."* — Airtable
- *"Design and implement evaluation harnesses, success metrics, automated testing pipelines, and guardrail frameworks."* — NVIDIA

→ Covered by [`mod-306`](lessons/mod-306-guardrails-safety-security) — guardrail placement, prompt-injection threat modeling, least-privilege tool permissions, OAuth/RBAC token management, CLI-agent sandboxing, excessive-agency controls. For frontier-safety depth (dangerous-capability evals, jailbreak engineering, control evaluation), link to the sibling [`agentic-safety-engineer-learning`](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) track (different rung, not a duplicate).

### Theme 7 — Regulated-domain architecture (50%)

Anchored by UiPath (healthcare), Guidehouse (federal), KPMG, Scotiabank (banking), Cognizant Principal (fintech), PwC, Air India (compliance), Zoom (regulated verticals), OKX (crypto), Accommodations Plus (PCI/PII), Gusto (payroll compliance), Deloitte, Airtable.

Representative quotes:
- *"Serve as a trusted advisor to healthcare executives on AI, automation, agentic transformation."* — UiPath
- *"Design and deliver secure, scalable, and cost-effective cloud-native AI solutions for federal clients."* — Guidehouse
- *"Ensure system scalability, security, and regulatory compliance of AI-powered solutions in the crypto exchange domain."* — OKX

→ Covered by [`mod-309`](lessons/mod-309-governance-compliance-domain) (multi-regime regulated-domain architecture; balanced-menu healthcare/finance/public-sector/edtech) and [`project-302`](projects/project-302-regulated-domain-agent-architecture) (learner-selected sector plus a portability analysis showing which controls change under a different regime — this "no single sector is privileged" design is what carries the theme). Deeper GRC depth in [`senior-ai-governance-architect-learning/mod-113-sector-and-jurisdiction-blueprints`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning).

### Theme 8 — Vendor-agnostic multi-framework fluency (46%)

Anchored by Slalom (Strands / OpenAI Agents SDK / Google ADK / LangGraph), Capital One (LangGraph / AutoGen / Semantic Kernel / CrewAI), Concentrix (LangGraph / ADK), Salesforce (agent ecosystems), OKX (AutoGPT / OpenAgents / LangGraph / LangFuse / Dify / Coze), NVIDIA (LangGraph / LangChain / MCP), Cognizant Enterprise (LangChain / LangGraph), Air India (multi-framework), Deloitte (Vertex AI / Gemini), Cognizant Principal Bedrock, PwC, Accommodations Plus.

→ **Framework mechanics** owned at L30 by [`agentic-ai-engineer-learning/mod-202-frameworks`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning) (build the same agent across LangGraph/CrewAI/AutoGen; benchmark OpenAI Agents SDK / Google ADK / Claude Agent SDK / smolagents). L40 `senior-agentic-ai-engineer` also names framework fluency as a prerequisite. This L48 track's contribution is the **portability/lock-in architectural lens**: [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration) (protocol-boundary design that isolates the choice of framework) and [`project-303`](projects/project-303-extensible-agent-platform) (justify the extensible-platform choice against at least one alternative platform — Claude Code, Cursor, Copilot, LangGraph Platform, or custom — explicitly addressing portability and lock-in). Named as a prerequisite in [`PREREQUISITES.md`](PREREQUISITES.md); this track does not re-teach the mechanics.

### Theme 9 — Multi-cloud / hyperscaler architecture (42%)

Anchored by Cognizant (AWS/GCP), Deloitte (GCP + Vertex AI), Slalom (AWS + Azure + GCP), KPMG (Microsoft + AWS + GCP), Experian (ECS/EKS/service mesh/API gateway), Guidehouse (GovCloud), PwC (cloud + agentic), UiPath (hyperscaler AI services), Cognizant Principal Enterprise (AWS + GCP), Cognizant Principal Bedrock (AWS + OSS + cross-cloud), Concentrix (Gemini/Vertex).

Representative quotes:
- *"Design and deliver AI and ML solutions across AWS, Azure, and GCP, using the right mix combination of cloud-native data services."* — Slalom
- *"Design and deliver enterprise-grade AI systems spanning Agentic AI, AWS Bedrock, and the full AI/ML spectrum."* — Cognizant (Principal Bedrock)
- *"Advise clients on TCO, deployment topology, and cross-cloud tradeoffs."* — Cognizant

→ **Covered implicitly** — the curriculum is cloud/vendor-neutral by design. Learners exercise cross-cloud tradeoffs in [`project-301`](projects/project-301-production-agentic-reference-architecture) (learner-selected reference architecture must justify its cloud/vendor choice against alternatives) and routing/cost architecture in [`mod-307/exercises/exercise-02-caching-and-routing-architecture`](lessons/mod-307-cost-latency-architecture). No explicit exercise comparing Bedrock ↔ Vertex ↔ Azure OpenAI ↔ Azure AI Foundry today. If this rises above 55% next cycle, propose extending [`project-301`](projects/project-301-production-agentic-reference-architecture) with a required "multi-cloud portability appendix" as a lightweight deliverable — no new module needed.

### Theme 10 — Evaluation infrastructure / harnesses / metrics at architecture level (42%)

Anchored by Slalom (MLOps/LLMOps), NVIDIA (eval harnesses + guardrail frameworks), Airtable (retrieval precision / hallucination rate metrics), Air India (evaluation-framework standards), Zoom (safety metrics), Gusto (quality safeguards), Capital One (red-team harnesses), Cognizant Principal, PwC, Accommodations Plus, Experian.

→ Covered by [`mod-304`](lessons/mod-304-evaluation-harnesses) at the architecture level (trajectory-eval design, tool-call-correctness harness, LLM-as-judge rubric, eval-gated release pipeline). Build-level eval infrastructure at L40 [`senior-agentic-ai-engineer-learning/mod-402-eval-observability-infra`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning); specialist-eval depth at L30 [`ai-eval-engineer-learning`](https://github.com/ai-engineering-curriculum/ai-eval-engineer-learning).

### Theme 11 — Memory / context / RAG architecture (42%)

Anchored by Experian (memory + retrieval strategies), Airtable (retrieval accuracy + knowledge systems), Cognizant, Air India, Slalom, Accommodations Plus, Deloitte, Guidehouse, Cognizant Principal, PwC, Salesforce.

Representative quote: *"Define and promote agentic AI architecture patterns, including multi-agent systems, tool orchestration, memory and retrieval strategies."* — Experian.

→ Covered by [`mod-303`](lessons/mod-303-memory-context-architecture) (context engineering, context-rot mitigation, memory-tier placement, RAG-as-architectural-concern). RAG pipeline implementation is prerequisite: [`agentic-ai-engineer-learning/mod-203-rag-and-memory`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning); specialist depth in [`rag-engineer-learning`](https://github.com/ai-engineering-curriculum/rag-engineer-learning).

### Theme 12 — Tool integration / MCP / function calling architecture (38%)

Anchored by Air India (function-calling schemas, legacy-system tools), NVIDIA (MCP), Cognizant Principal (MCP + tool orchestration), Airtable (agent tool APIs), Gusto (tool orchestration patterns), Concentrix (agent orchestration & tool use), Slalom, Capital One (guardrail hooks/APIs), Deloitte (agentic design patterns), Cognizant.

Representative quote: *"Design secure Function Calling interfaces and Tool Definition schemas to enable agents to interact with legacy systems, SQL databases, and enterprise CRMs."* — Air India.

→ Covered by [`mod-302/exercises/exercise-03-mcp-a2a-integration-architecture`](lessons/mod-302-multi-agent-orchestration) and [`mod-310/exercises/exercise-02-secure-tool-use-and-context-hydration`](lessons/mod-310-agentic-developer-platforms). MCP-server authoring at L30 [`agentic-ai-engineer-learning/mod-202-frameworks/exercises/exercise-04-mcp-tool-server`](https://github.com/ai-engineering-curriculum/agentic-ai-engineer-learning).

### Theme 13 — Publish / evangelize / architecture thought leadership (38%)

Anchored by Capital One (both — conferences, blogs, office hours), Slalom (thought leadership), Anthropic (external representation, scalable enablement mechanisms), ServiceNow (both — voice-of-customer + feed into product), UiPath, Salesforce, KPMG (strategic vision publishing), Airtable, NVIDIA (partner workshops), Cognizant Principal Enterprise (roadmaps + POVs).

Representative quote: *"Coach and evangelize — hosting architecture office hours, mentoring Staff, Principal and Senior engineers."* — Capital One.

→ **Not currently covered explicitly at L48.** Bundled in the architect-leadership-cluster `needs-research` below.

### Theme 14 — Enterprise integration / legacy systems (38%)

Anchored by Air India (legacy systems, SQL, CRMs), Deloitte (enterprise applications), Concentrix (data-estate integration), Airtable (APIs), Experian (integration architecture), Cognizant Principal (enterprise integration), PwC (workflow/systems), Guidehouse (mission systems), ServiceNow, Accommodations Plus (Java backends + AI-enabled systems).

→ Covered by [`mod-310/exercises/exercise-03-workflow-toolchain-integration`](lessons/mod-310-agentic-developer-platforms) (VCS, issue trackers, knowledge bases, CI/CD over REST/GraphQL/event-driven interfaces).

### Theme 15 — Vertical / domain-specific architecture (35%)

Anchored by UiPath (healthcare), Guidehouse (federal), Cognizant Bedrock (broad), Zoom (vertical agentic apps), OKX (crypto), Scotiabank (banking), Air India (aviation), Airtable (customer experience), Gusto (payroll).

→ Covered by [`project-302`](projects/project-302-regulated-domain-agent-architecture) — learner-selected sector from a balanced menu (healthcare, finance, public sector, edtech), with a portability analysis across regimes. The "no single sector is privileged" design is what carries the theme.

### Theme 16 — TCO / cost architecture / build-vs-buy at portfolio level (31%)

Anchored by Cognizant (TCO/cross-cloud), Guidehouse (TCO + deployment topology + multi-cloud), PwC (target-state architecture + TCO + governance model), Cognizant Principal Bedrock (TCO + cross-cloud tradeoffs), Cognizant Enterprise (build-vs-buy at scale), Zoom (cost/latency/safety tradeoffs), Capital One (SLAs), Experian (velocity + reliability + cost + security balancing).

Representative quotes:
- *"Define TCO, deployment topology, and multi-cloud tradeoffs across GovCloud environments."* — Guidehouse
- *"Establish governance patterns for LLM cost, latency, and safety trade-offs."* — Zoom
- *"Advise senior client stakeholders on target-state architecture, TCO, and governance model."* — PwC

→ Covered by [`mod-307`](lessons/mod-307-cost-latency-architecture) (token-economics cost model, caching-and-routing architecture, cost/latency/quality budgets). Build-level cost defense at L40 [`senior-agentic-ai-engineer-learning/mod-403/02-token-and-latency-budgets`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning) and [`mod-404-reliability-cost-incident/02-cost-controls-and-budgets`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning).

### Theme 17 — Pre-sales / RFP / GTM enablement (31%)

Anchored by Slalom (thought leadership + client-facing), KPMG (business development), Cognizant Principal (client engagement), Lenovo (pre-sales solution proposals), Anthropic (segment leads / partner engagements), ServiceNow (both — voice of customer + GTM readiness), PwC (engagement delivery), Concentrix (sales+delivery bridge).

Representative quotes:
- *"Drive business development to expand KPMG's AI portfolio by identifying market opportunities."* — KPMG
- *"Support pre-sales engagements as a senior AI architecture authority, producing customer-facing solution proposals."* — Lenovo
- *"Act as a key bridge between sales and delivery, working closely with customers and Google channel partners."* — Concentrix

→ **Not curriculum-worthy universally at L48.** Present in ~31% of postings but concentrated at consulting shops and vendor-SA teams. Product-team architects (Airtable, Gusto, Experian, Air India) don't need it. Learners in consulting or vendor-SA tracks should pursue **external resources** (below) rather than an in-track module.

External resources for learners in consulting / vendor-SA sub-tracks:
- AWS Certified Solutions Architect – Associate (SAA-C03) — https://aws.amazon.com/certification/certified-solutions-architect-associate/
- Google Cloud Professional Cloud Architect — https://cloud.google.com/learn/certification/cloud-architect
- SPIN Selling (Neil Rackham) — canonical technical-discovery methodology used across SA/consulting practices — https://www.huthwaiteinternational.com/en/spin-selling
- Anthropic Applied AI blog — https://www.anthropic.com/customers (representative client-facing agentic architecture writeups)

## Uncovered signal cluster — architect leadership & influence at L48

Four themes cluster together and are not currently covered by this L48 track:

| Component theme | Freq | Above threshold? |
|---|---|---|
| C-suite / executive stakeholder advisory & influence (theme-03) | **62%** | Yes |
| Mentor architects / practice-level capability building (theme-05) | **50%** | Yes |
| Publish / evangelize / architecture thought leadership (theme-13) | **38%** | Yes |
| Design authority / ARB / gate reviews (theme-20) | 23% | No (below) |

Postings cite these components heavily overlapping (Capital One's Distinguished JDs name all four; Scotiabank's Chief AI Architect names three; Cognizant's Principal Enterprise Architect names three; Slalom, ServiceNow, Anthropic, Air India, UiPath name at least two). The **union frequency** — postings citing at least one component — is ~62% of the sample.

**Decision this cycle: NO DELTA.** Reasons:

1. This is a **curriculum-scope-boundary question, not a market shift**. The L48 curriculum was authored (June 2026) as a deliberate **technical-architecture spine** — see [README.md](README.md) — leaving leadership/influence content out of scope by intent, not by omission. Nothing has materially shifted in the 90-day window that reframes that scope decision.
2. **Sibling generic-architect tracks may already own this terrain.** Relevant candidates: [`senior-ai-governance-architect-learning/mod-112-program-design-and-org-shape`](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning) (which covers program design and org shape at governance-architect altitude), [`ai-infra-senior-architect-learning`](https://github.com/ai-infra-curriculum/ai-infra-senior-architect-learning), and [`cto-curriculum`](https://github.com/ai-infra-curriculum/cto-curriculum) (which owns executive AI-strategy conversations). Under the ownership rule, if a sibling track owns generic architect leadership, this L48 track should link there rather than duplicate.
3. Under strict continuity bias, **PREFER ZERO ADDITIONS over weakly-justified ones** — and adding a leadership module without first confirming sibling coverage is exactly the kind of ill-scoped addition the packet warns against.

**Recommendation for next cycle (2026-12):** Humans decide between three options:

- **(a)** Add a lightweight L48 module `mod-311-architect-leadership-influence` (~10 hours, 3–4 exercises: exec brief drafting for CIO/CAIO, ARB defense simulation, architect mentoring/coaching plan, publishing an agentic-architecture POV). +9.4% additions on module count — within the 20% cap.
- **(b)** Route the theme to a sibling track (`senior-ai-governance-architect-learning`, `ai-infra-senior-architect-learning`, or `cto-curriculum`) and link out from this L48 track's PREREQUISITES / README.
- **(c)** Keep out of scope; document as an explicit non-goal with external-resource pointers (e.g., the *Staff Engineer's Path* — Larson; *The Software Architect Elevator* — Hohpe; the SEI SATURN and O'Reilly Software Architecture Conf archives for design-authority patterns).

## Themes just below threshold this cycle

### Observability & tracing (27%)

Anchored by Accommodations Plus (drift detection), Cognizant Principal, Capital One, Airtable (observability + retrieval-accuracy instrumentation), NVIDIA, Gusto, Zoom.

→ Covered by [`mod-305-observability-tracing`](lessons/mod-305-observability-tracing) — OpenTelemetry GenAI semantic conventions, stable trace identity across retries and long-running sessions, quality/drift signals, platform evaluation (LangSmith, Langfuse, Arize Phoenix). Fleet-level operational-observability implementation belongs at L40 [`senior-agentic-ai-engineer-learning/mod-402-eval-observability-infra`](https://github.com/ai-engineering-curriculum/senior-agentic-ai-engineer-learning).

### Central platform / paved-road / shared-service (23%)

Anchored by Capital One (both), Experian (cloud-native platform), Gusto (reusable patterns), Slalom, Zoom, Anthropic.

→ Covered by [`mod-310-agentic-developer-platforms`](lessons/mod-310-agentic-developer-platforms) and [`project-303-extensible-agent-platform`](projects/project-303-extensible-agent-platform).

### Design authority / ARB / gate reviews (23%)

Anchored by Experian (arch reviews with binding decisions), Scotiabank (design-authority review cadence), Concentrix (deep-dive arch reviews), Accommodations Plus (ARBs, Gate 0/Gate 1 estimates), Cognizant (arch strategy), Zoom (arch reviews for high-risk deployments).

→ Sub-threshold; bundled in the architect-leadership-cluster `needs-research` above.

### Human-in-the-loop / approval boundaries (15%)

Anchored by Gusto (HITL protocols, escalation logic), Accommodations Plus, KPMG (risk management), Guidehouse (mission risk).

→ Covered by [`mod-306`](lessons/mod-306-guardrails-safety-security) (excessive-agency controls, human-approval-for-high-risk-actions) and [`mod-308/exercises/exercise-02-hitl-approval-architecture`](lessons/mod-308-deployment-durable-execution) (approve/edit/reject/respond flows with state persistence).

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

<!-- needs-research: for the 2026-12 cycle, humans should decide the SCOPE-BOUNDARY question on architect-leadership-and-influence (executive advisory 62%, practice mentoring 50%, thought leadership 38%, ARB 23%). Options are (a) add a lightweight mod-311-architect-leadership-influence to this L48 track, (b) route to a sibling generic-architect track (senior-ai-governance-architect-learning/mod-112, ai-infra-senior-architect-learning, or cto-curriculum), or (c) keep out of scope with external-resource pointers. The signal is strong; the question is where it belongs. Not a technical-market-shift signal — the requirement existed at curriculum design time and was omitted by intent. -->

<!-- needs-research: watch multi-cloud/hyperscaler-architecture (Bedrock vs. Vertex vs. Azure OpenAI vs. Azure AI Foundry) — 42% this cycle. If it crosses 55%, extend project-301 with a required multi-cloud portability appendix (still no new module). If it stays 40–55%, defer. -->

<!-- needs-research: watch central-platform / paved-road / shared-service-agentic-architecture — 23% sub-threshold. If it crosses 30% next cycle, no delta required (already owned by mod-310 + project-303) but re-verify the exercises still map cleanly to the emerging patterns. -->

The `mod-301..310` architecture spine covers every job-market requirement that clears the continuity-bias thresholds at L48 altitude. Build-fundamentals (framework mechanics, RAG implementation, single-agent evaluation, guardrail implementation) stay owned by the L30 `agentic-ai-engineer-learning` / `rag-engineer-learning` / `ai-eval-engineer-learning` tracks and are named as prerequisites. Production-hardening build skills stay owned by the L40 `senior-agentic-ai-engineer-learning` track and are named as the recommended on-ramp. Sibling architect tracks (`agentic-safety-engineer-learning` for frontier-safety, `senior-ai-governance-architect-learning` for AIMS/audit depth) are linked as adjacent, not duplicated. **No delta is proposed this cycle.** The only genuine uncovered signal — architect leadership & influence — is a curriculum-scope-boundary question flagged for human review in the 2026-12 cycle.
