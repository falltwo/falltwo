<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/banner.jpg?v=2" width="100%" alt="Soft-focus photo of pale flowers against a blue sky"/>
</div>

## Hi, I'm Falltwo

I'm an AI student in Taiwan. Most of what I build sits between a model's answer and a real action in a system: what the agent may do on its own, what a person has to approve first, and what record stays behind afterwards.

<p>
  <a href="mailto:gjui890@outlook.com"><img src="https://img.shields.io/badge/Email-gjui890%40outlook.com-B86B4B?style=flat-square&logo=maildotru&logoColor=white" alt="Email gjui890@outlook.com"/></a>
  <img src="https://img.shields.io/badge/Based_in-Taiwan-D9A066?style=flat-square" alt="Based in Taiwan"/>
</p>

### Projects

**[AI-Risk-Based-Inventory-ERP](https://github.com/falltwo/AI-Risk-Based-Inventory-ERP)**
An ERP where an LLM agent reads supply-chain risk and proposes purchase changes, but cannot write to the books by itself. There are three roles: one only watches the risk dashboard, one drafts proposals, and one approves and executes them. Proposals, approvals and executions are separate records with an audit trail, and repeated executions are idempotent. v1.0 passed 327 tests at release. It is a proof of concept on a single SQLite database, and the README spells out what it does not cover.

**[Contract-compliance-agent](https://github.com/falltwo/Contract-compliance-agent)**
A first-pass contract reviewer in Traditional Chinese, and a finalist in Taiwan's 2026 Best AI Awards. It's meant to save a legal reviewer the slow clause-by-clause read, with a person still signing off. You upload a contract, and it flags risky clauses, suggests edits and cites the Taiwanese statutes it relied on. Under the hood it's RAG plus a multi-tool agent, with an eval set for measuring routing and tool accuracy. Streamlit for demos, FastAPI + Vue for internal deployment.

**[gcis-talent-radar](https://github.com/falltwo/gcis-talent-radar)**
Built for InnoServe 2026. It answers questions about manufacturing in Taichung, such as how many factories and job openings a district has, using government open data. Code computes the numbers, the model only explains them, and any answer with a figure that doesn't match the tool output is blocked before it reaches the user. 345 tests.

<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/strip5.jpg?v=2" width="100%" alt="A flower and its shadow on a warm beige wall"/>
</div>

### What I'm looking into

- Approval controls that still hold when the model itself can't be trusted
- Evaluating agents on whole tasks, beyond single replies
- Keeping cost and behaviour visible when requests are routed across several models
- Deciding what an approver actually needs to see, and at which point

### Tools I use

<img src="https://skillicons.dev/icons?i=python,ts,c,vue,fastapi,docker,git&theme=light" alt="Python, TypeScript, C, Vue, FastAPI, Docker, Git"/>

Also LiteLLM, LangGraph, Streamlit and SQLite.

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=falltwo&show_icons=true&hide_border=true&title_color=B86B4B&icon_color=D9A066&text_color=8A7A6D&bg_color=00000000" alt="GitHub stats for falltwo"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=falltwo&layout=compact&hide_border=true&title_color=B86B4B&text_color=8A7A6D&bg_color=00000000&langs_count=6" alt="Most used languages for falltwo"/>
</div>

<details>
<summary>Contribution snake</summary>
<br/>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/falltwo/falltwo/output/snake-dark.svg"/>
  <img alt="Contribution graph animated as a snake" src="https://raw.githubusercontent.com/falltwo/falltwo/output/snake.svg"/>
</picture>
</details>

<div align="center">
  <img src="https://raw.githubusercontent.com/falltwo/falltwo/main/assets/strip7.jpg?v=2" width="100%" alt="Shadows of dried flowers on a pale wall"/>
</div>
