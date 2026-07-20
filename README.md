<!--
═══════════════════════════════════════════════════════════════
  SETUP
  1. Put this README.md in the ROOT of a public repo named exactly  falltwo
     (a repo with the same name as your account becomes your profile page).
  2. To enable the contribution snake: add .github/workflows/snake.yml (provided),
     then run it once manually from the repo's Actions tab.
  Palette — warm & restrained: terracotta #B86B4B / amber #D9A066 / warm-grey text #8A7A6D, transparent bg.
═══════════════════════════════════════════════════════════════
-->

<!-- ░░░ header banner (photo) ░░░ -->
<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/banner.jpg?v=2" width="100%" alt="header"/>
</div>

<!-- ░░░ typing animation title ░░░ -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=900&color=B86B4B&center=true&vCenter=true&width=620&lines=Reliable+and+governed+agentic+systems;Evaluation%2C+human+approval%2C+audit+trails;Agent+orchestration+and+LLM+routing" alt="typing" />
  </a>
</div>

<br/>

<!-- ░░░ intro ░░░ -->
### 👋 About me

I am an AI student. I build AI agent systems that connect model reasoning to
operational workflows through evaluation, human approval, and auditable execution.

My focus is the layer between a model's output and a real system action: what the
agent is allowed to do, who approves it, and what record is left behind.

<br/>

<!-- ░░░ selected projects ░░░ -->
### 📌 Selected projects

#### 1. Governed Supply-Chain ERP

**Problem** — When an LLM agent operates an ERP system, model reasoning alone
decides when inventory and purchasing records change. Functional authorisation
(a user may access a feature) is not the same as authorisation for an agent to
execute that action autonomously.

**System approach** — External supply-chain risk analysis feeds a three-tier
workflow: L1 observation (read-only risk KPIs, heatmap, alerts), L2 proposal
(impact analysis, what-if comparison, immutable proposals submitted for review),
and L3 approval and execution (review of approval evidence, approve or reject,
gateway-mediated execution, audit timeline). Protected ERP writes require human
approval before execution. Proposal, Approval, and Execution are stored as
separate records alongside audit entries and idempotent execution receipts.

**Verifiable evidence** — 327 automated tests passing on the public default
branch; tagged `v0.1` and `v1.0` GitHub Releases with English release notes;
a published procurement-flow diagram with its editable draw.io source; a
documented known-limitations section.

**Scope and limitations** — Proof of concept, not a deployed system. One SQLite
database represents a single organisation, so this is not row-level
multi-tenancy on a shared database. The application-layer audit trail is
tamper-evident but does not defend against someone with host or database
administrator access. SQLite transaction guarantees do not extrapolate to
external ERP APIs; cross-system execution would still require an outbox, worker,
and reconciliation strategy. Demo accounts and synthetic data are for local
evaluation only.

🔗 [falltwo/AI-Risk-Based-Inventory-ERP](https://github.com/falltwo/AI-Risk-Based-Inventory-ERP)

<br/>

#### 2. Contract Compliance Agent

**Problem** — A first-pass contract review means reading clauses one by one and
manually cross-checking them against legal sources, which is slow and hard to
trace back to a citation.

**System approach** — Retrieval-augmented generation over uploaded legal
documents, combined with a multi-tool agent workflow that routes between
document retrieval, knowledge-base question answering, and external legal-source
lookup. Answers are grounded in retrieved chunks and carry citations. The
repository includes evaluation datasets and batch validation routes so output
quality can be measured rather than only demonstrated, plus a Streamlit demo
path and a FastAPI + Vue service path.

**Verifiable evidence** — MIT licence; CI workflow defined in the repository;
evaluation API routes and evaluation datasets present in the public tree;
public repository topics covering RAG, agents, and retrieval.

**Scope and limitations** — This is a retrieval and drafting aid, not legal
advice. It does not establish legal accuracy or regulatory compliance, and its
output requires review by a qualified person before use. I have no measured
business outcomes to report for it.

🔗 [falltwo/Contract-compliance-agent](https://github.com/falltwo/Contract-compliance-agent)

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/strip5.jpg?v=2" width="100%" alt="divider"/>
</div>

<br/>

<!-- ░░░ interests (clearly separated from shipped work) ░░░ -->
### 🌱 Current interests

These are directions I am reading about and experimenting with. They are not
claims about what the projects above already implement.

- Governance controls that hold when the underlying model is not trusted
- Evaluation methods for agent systems beyond single-response benchmarks
- Long-running observability and cost control across multi-model routing
- Human-in-the-loop approval design: what to surface to a reviewer, and when

<br/>

<!-- ░░░ tech stack badges ░░░ -->
### 🛠 Tech stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=c,python,ts,docker,git&theme=light" alt="tech stack" />
  <br/>
  <sub><i>+ LiteLLM for the model layer · Streamlit · FastAPI · SQLite</i></sub>
</div>

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/strip6.jpg?v=2" width="100%" alt="divider"/>
</div>

<br/>

<!-- ░░░ stats + streak ░░░ -->
### 📊 Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=falltwo&show_icons=true&hide_border=true&title_color=B86B4B&icon_color=D9A066&text_color=8A7A6D&bg_color=00000000" alt="stats" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=falltwo&hide_border=true&background=00000000&stroke=E8DDD3&ring=B86B4B&fire=C26B4A&currStreakLabel=B86B4B&sideLabels=8A7A6D&dates=A89A8C&currStreakNum=5C4A3A&sideNums=5C4A3A&dayLabels=8A7A6D" alt="streak" />
</div>

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=falltwo&layout=compact&hide_border=true&title_color=B86B4B&text_color=8A7A6D&bg_color=00000000&langs_count=8" alt="top-langs" />
</div>

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/strip7.jpg?v=2" width="100%" alt="divider"/>
</div>

<br/>

<!-- ░░░ contribution snake (needs snake.yml workflow) ░░░ -->
### 🐍 Contributions

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/falltwo/falltwo/output/snake-dark.svg" />
    <img alt="snake" src="https://raw.githubusercontent.com/falltwo/falltwo/output/snake.svg" />
  </picture>
</div>

<br/>

<!-- ░░░ contact ░░░ -->
### 📫 Contact

- Email — gjui890@outlook.com
- Location — Taiwan

<br/>

<!-- ░░░ footer (photo) ░░░ -->
<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/footer8.jpg?v=2" width="100%" alt="footer"/>
</div>
