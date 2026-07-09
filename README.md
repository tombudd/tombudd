<!-- Tom Budd — GitHub Profile README -->

<div align="center">

# Tom Budd
### Research-Grounded Systems Builder · AI Safety & Governance Engineer

[![Website](https://img.shields.io/badge/tombudd.com-000000?style=flat&logo=safari&logoColor=white)](https://tombudd.com)
[![Research](https://img.shields.io/badge/AI%20Governance-Research-blue?style=flat)](https://tombudd.com/research)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tombudd-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/tom-budd/)
[![Get Involved](https://img.shields.io/badge/Get%20Involved-Collaborate-orange?style=flat)](https://tombudd.com/get-involved)

</div>

---

## What I Work On

I build small, reviewable software artifacts that turn difficult ideas into things people can inspect, run, test, or critique.

I build reproducible AI governance benchmarks for agentic systems, with a focus on authority boundaries, tool-use safety, human sovereignty, and whether AI assistance strengthens or weakens human judgment.

Most of my production research is private. This GitHub contains clean-room, educational, and redacted artifacts that show my methods without exposing proprietary systems, private schemas, private logs, private records, or production architecture.

> My goal with these repos is simple: make AI governance claims inspectable instead of just aspirational.

---

## Start Here

The clearest path through my public work is:

1. **[Public AI Governance Portfolio](docs/PUBLIC_PORTFOLIO_INDEX.md)** — the short map connecting the public research arc.
2. **[Case Study: AI Governance Benchmarks](docs/CASE_STUDY_AI_GOVERNANCE_BENCHMARKS.md)** — how I turned an abstract governance idea into a bounded, runnable, tested artifact.
3. **[Evaluation Stack Overview](https://github.com/tombudd/ai-governance-benchmarks/blob/main/docs/EVALUATION_STACK_OVERVIEW.md)** — the two-layer stack: agent boundary safety and human sovereignty.
4. **[AI Governance Benchmarks](https://github.com/tombudd/ai-governance-benchmarks)** — synthetic inputs, governance scorer, reproducible report, and tests.
5. **[Agent Action Audit Template](https://github.com/tombudd/agent-action-audit-template)** — schema-backed synthetic action records, blocked-action examples, and human-review metadata.

Method line:

```text
synthetic inputs -> governance scorer -> reproducible report -> tests pass
```

---

## Recent AI Safety Evaluation Work

I recently expanded [`ai-governance-benchmarks`](https://github.com/tombudd/ai-governance-benchmarks) into a two-layer public evaluation stack: agent boundary safety and human sovereignty.

Status:

- CI green
- 21 tests passing
- deterministic rule-based scorer
- synthetic boundary cases
- generated sample report
- explicit claims and limitations
- anti-overclaim language guard

Repo: https://github.com/tombudd/ai-governance-benchmarks

---

## Public Portfolio Focus

| Area | Public Surface |
|------|----------------|
| AI governance evaluation | Synthetic benchmarks, scoring methods, and documentation patterns |
| Adversarial evaluation | Clean-room tests for prompt injection, authority spoofing, and boundary erosion |
| Accountability | Synthetic records and reconstructability rubrics |
| AI safety research | Public notes, redacted methodology, and reproducible benchmark ideas |
| Quantum + AI | Exploratory toy experiments, clearly caveated and non-production |

For the full public evidence map, start with **[Public AI Governance Portfolio](docs/PUBLIC_PORTFOLIO_INDEX.md)**.

---

## Beyond AI Governance

My work spans computational cognition, games, humanistic computing, local-first tooling, and public-safe research artifacts.

The common thread is simple: I turn abstract ideas into small, reviewable software artifacts that people can inspect, run, test, or critique.

Some of my public work focuses on AI governance, but the broader pattern is systems design: building tools and demos that make complex ideas more understandable without exposing private architecture or overstating what the work shows.

### Current Areas Of Exploration

- **Computational cognition** — active inference, prediction, uncertainty, homeostasis, agency, and adaptive behavior.
- **Games and strategic environments** — play, multi-agent decision spaces, learning under constraints, and game-like evaluation settings.
- **Humanistic computing** — interactive software around literature, culture, education, interpretation, and meaning-making.
- **Local-first tools** — lightweight systems for research, review, evidence tracking, and human-in-the-loop workflows.
- **Public-safe artifacts** — clean-room demos, primers, benchmarks, and case studies that show method without exposing private systems.
- **Product and portfolio infrastructure** — websites, project indexes, prototypes, and deployed surfaces that make research easier to navigate.

I like building systems that are useful, understandable, and responsibly bounded — tools that help people think better, learn faster, repair mistakes, and make decisions with more clarity.

### Selected Non-Governance Projects

- **[Active Inference Primer](https://github.com/tombudd/active-inference-primer)** — a minimal educational primer for thinking about prediction, agency, uncertainty, and adaptive systems.
- **[OpenSpiel](https://github.com/tombudd/open_spiel)** — game and multi-agent environment work; useful for studying strategy, learning, coordination, and bounded decision-making.
- **[Quantum AI Experiments](https://github.com/tombudd/quantum-ai-experiments)** — supporting exploratory sandbox for simulator-first quantum/AI-adjacent experiments with explicit claim boundaries.

---

## Featured Proof Artifact

**[AI Governance Benchmarks](https://github.com/tombudd/ai-governance-benchmarks)** — clean-room public benchmark portfolio for AI governance evaluation.

Shows:

- synthetic benchmark design
- reproducible local runners
- rule-based scoring
- expected reports
- pytest + GitHub Actions verification
- public/private disclosure discipline

Start with:

- [Evaluation Stack Overview](https://github.com/tombudd/ai-governance-benchmarks/blob/main/docs/EVALUATION_STACK_OVERVIEW.md)
- [Project Status](https://github.com/tombudd/ai-governance-benchmarks/blob/main/PROJECT_STATUS.md)
- [Recruiter Summary](https://github.com/tombudd/ai-governance-benchmarks/blob/main/docs/RECRUITER_SUMMARY.md)
- [Hiring Proof Map](https://github.com/tombudd/ai-governance-benchmarks/blob/main/docs/HIRING_PROOF_MAP.md)
- [Case Study](docs/CASE_STUDY_AI_GOVERNANCE_BENCHMARKS.md)

**[Agent Action Audit Template](https://github.com/tombudd/agent-action-audit-template)** — clean-room templates for synthetic agent action receipts, blocked-action examples, human-review metadata, JSON schemas, and pytest validation.

Shows:

- agent action audit trail design
- safe vs. blocked action records
- human review checkpoint modeling
- schema-backed receipt validation
- synthetic-only public boundary discipline

---

## Current Public Repositories

- **AI Governance Benchmarks** — clean-room benchmark portfolio with synthetic Constitutional Adherence and Accountability Completeness evaluations, local runners, scoring, expected reports, tests, and CI.
- **Agent Action Audit Template** — clean-room operational governance template with synthetic safe and blocked action receipts, human-review metadata, schemas, tests, and CI.
- **Human-AI Governance Lab** — clean-room workflow for lightweight risk classification, human approval gates, and reproducible audit receipts.
- **Eudaimonic Alignment** — public research notes connecting alignment, human sovereignty, flourishing, and governance evaluation.
- **Active Inference Primer** — minimal educational free-energy utilities with synthetic numerical tests and explicit limitations.
- **Quantum AI Experiments** — exploratory quantum-circuit experiments related to optimization, inference, and noisy-hardware testing.

These repositories are intentionally bounded. They are public proof-of-method artifacts, not disclosures of private systems.

---

## Research Direction

My work focuses on a practical question:

**How do we make AI systems that can act usefully while remaining inspectable, bounded, corrigible, and accountable at runtime?**

I am especially interested in:

- Governance mechanisms that execute, not just policies that describe.
- Decision receipts that can be independently audited.
- Evaluation suites for adversarial pressure and boundary stability.
- Human-centered AI systems that preserve agency, dignity, and institutional accountability.
- Safe public documentation strategies for private AI safety research.

---

## Background

I am the founder of [ResoVerse](https://resoverse.tech), where my private production research informs the public-safe methods and proof artifacts shared here.

---

## Collaboration

I am open to serious collaborators in AI safety, governance evaluation, red-teaming, systems architecture, and applied research.

→ **[tombudd.com/get-involved](https://tombudd.com/get-involved)** — I respond personally.

---

<div align="center">

[tombudd.com](https://tombudd.com) · [tom@tombudd.com](mailto:tom@tombudd.com) · San Diego, CA

</div>
