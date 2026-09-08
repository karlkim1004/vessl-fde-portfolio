# Kyounuk (Karl) Kim

## Forward Deployed Engineer portfolio

Seoul, South Korea · Founder and enterprise AI delivery leader

This portfolio describes work I can substantiate from source repositories, merged pull requests, deployment records, and internal product records. Confidential customer names, credentials, personal data, and private source code are intentionally omitted.

## Fit for VESSL AI FDE

| VESSL requirement | Evidence in this portfolio | Boundary |
|---|---|---|
| Customer-facing technical practice | 15+ years across software development, solution architecture, BA/SA, PM/PL, consulting, and enterprise delivery | Customer names are disclosed only where already public or safe to generalize |
| Solution design and technical explanation | LG D2C service planning; HiaaS/Eden AI, RPA, and enterprise platform engagements; NexAI product architecture | No unverified contract values or win claims |
| AI workload understanding | NexAI on-device Korean NER and multi-channel parsing architecture; 5ETS AI consensus and operations automation | Government proposal was submitted and not selected; no funded delivery is claimed |
| PoC, onboarding, migration, and incident problem solving | Enterprise rollout governance and operational runbooks; Multica validator/worker-pool and handoff workflows | Direct GPU-cluster migration leadership is not claimed; this is the primary VESSL gap |
| Python/log/error diagnosis | Public Multica platform source and merged implementation PRs; prior software development experience | Latest public GPU/Python production evidence is limited; no claim of deep PyTorch/vLLM expertise |
| Clear communication across teams | Customer discovery, scope framing, stakeholder alignment, technical delivery, and evidence-based handoffs | Start date, if requested: approximately one month after offer signing |

## Project 1 — Multica multi-agent orchestration

### Problem

AI coding agents can produce useful changes but become difficult to coordinate when ownership, verification, waiting reasons, and completion state are ambiguous. The system needed a practical operating model for assigning work, routing follow-up tasks, validating outcomes, and preserving an audit trail.

### Role

Founder and product/technical strategist for the operating model; contributed to product direction, workflow contracts, verification gates, and delivery coordination.

### Technical structure

Multica is a web platform with issue/task state, agent and squad routing, comments and mentions, repository context, worker dispatch, validator gates, and a virtual-office view. The workflow separates task assignment from verification and uses explicit waiting ownership and unblock conditions.

### Implemented examples

- Validator registration and structured validator controls.
- Worker-pool dispatch of eligible todo work to idle workers.
- Waiting-on-aware office ownership and idle-clock behavior.
- Escalation controls that enqueue real runs rather than merely changing UI state.

### Verifiable public evidence

- Public repository: https://github.com/karlkim1004/multica
- Merged validator CLI PR: https://github.com/karlkim1004/multica/pull/75
- Merged worker-pool PR: https://github.com/karlkim1004/multica/pull/55
- Merged escalation interaction PR: https://github.com/karlkim1004/multica/pull/64

These links show the public code and merged change history. They do not imply that every internal operating record is public.

## Project 2 — AIDO on-device AI product architecture

### Problem

Design an assistant that can parse Korean multi-channel messages and call transcripts on-device, identify structured entities and behavior patterns, and produce safety-oriented alerts while preserving privacy boundaries.

### Role

Founder and AI product architect. Defined the product architecture, Korean NER and multi-channel parsing direction, alerting workflow, caregiver-facing concepts, and release/QA constraints.

### Technical structure

The architecture combines local or device-constrained parsing, Korean entity extraction, message/call normalization, behavior-pattern signals, staged safety notification, and a caregiver dashboard workflow. The design emphasizes privacy, explicit user scope, evidence-backed QA, and operational rollback safety.

### Implemented or recorded evidence

- AIDO Android application and family-safety server are maintained in a private repository.
- Release artifacts and QA records exist in internal project records.
- The 2026 government R&D application related to open-source Korean NER and safety monitoring was submitted but not selected; no award or funded delivery is claimed.
- Three Korean patent applications were filed in March 2026; they are applications, not granted patents.

Because the implementation repository and release records are private, this section intentionally provides no private URL, credential, customer name, or unverified metric.

## Project 3 — 5ETS AI consensus and operations automation

### Problem

Financial research agents need a repeatable way to combine multiple investment perspectives, handle incomplete evidence, and record operational decisions without presenting unsupported certainty as fact.

### Role

Founder and system owner. Defined the multi-expert workflow, consensus/evidence framing, runtime operations, and monitoring expectations.

### Technical structure

The system coordinates multiple AI expert perspectives, gathers market and company evidence, records a structured consensus, and separates research output from runtime/operations controls. Operational automation includes scheduled execution, health/usage observation, and failure handling.

### Evidence boundary

The source repository and operational records are private. This portfolio does not expose source code, credentials, brokerage data, financial account information, or performance claims. The project is presented as an AI workflow and operations case, not as an investment-return claim.

## Working principles

- State only what the underlying record supports.
- Separate proposal, application, implementation, and production deployment.
- Treat customer confidentiality and personal data as hard boundaries.
- Make waiting ownership, verification evidence, and unblock conditions explicit.
- Prefer a small reproducible demo or runbook over unsupported scale claims.
