<h1 align="center">Deepesh Sonar</h1>

<p align="center">
  <b>I build systems, then try to break my own claims about them.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deepeshsonar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://orcid.org/0009-0008-1762-4246"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="mailto:18deepnar@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://x.com/DeepnarS"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Deepnar&label=Profile+Views&color=7C3AED&style=for-the-badge" alt="Profile Views">
</p>

---

Computer Engineering student in Mumbai.

I like building things from first principles, pushing them until they break, and figuring out which parts actually mattered.

Some projects become research. Some become tools. Some exist because I wanted to understand an idea properly and ended up implementing far more of it than originally planned.

### 📄 Current research

<p>
  <a href="https://arxiv.org/abs/2609.16730">
    <img src="https://img.shields.io/badge/arXiv-B31B1B?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv">
  </a>
  <b>LSREP: A Longitudinal State-Replay Protocol for Evaluating Conversational Memory, with ICE v2 as an Audited Local-First Architecture</b>
</p>

LSREP is a longitudinal evaluation protocol for conversational memory. It treats memory as something that evolves over time rather than as a static retrieval problem, using ordered replay, repeated probes, evolving reference answers, lifecycle schedules, and mechanism-fidelity auditing.

The work grew out of building and evaluating ICE, but the larger question interested me more:

**How do you know whether a system actually behaves the way its architecture says it does?**

### 🛠️ Selected work

| Project | What it is |
| --- | --- |
| **[ICE](https://github.com/Deepnar/ice)** | A local-first conversational memory system built around typed memory, retrieval fusion, evolving state, and evaluation that traces which mechanisms actually affected the final result. |
| **[Presentation Forge](https://github.com/Deepnar/presentation-forge)** | A self-hosted presentation and report generator with PPTX/DOCX export, deterministic themes, local-model support, BYOK providers, and a Docker-first setup. |
| **[timetable-generator](https://github.com/Deepnar/timetable-generator)** | A constraint-driven scheduling system using OR-Tools CP-SAT alongside a greedy solver, designed around explicit hard constraints rather than post-generation cleanup. |

I keep plenty of smaller repos too: coursework, experiments, model tooling, systems work, from-scratch implementations, and things I built mostly because I wanted to understand them.

### 🔬 How I work

**I try to separate “didn't work” from “wasn't actually tested.”**  
A mechanism that failed, never ran, was never exercised, or never reached the final output does not tell you the same thing.

**I prefer precise results to impressive-sounding ones.**  
If something matches a baseline, loses to one, or only works under certain conditions, I want the write-up to say exactly that.

**I usually care about the whole system.**  
The model or algorithm is often only one piece. The data path, API, database, evaluation harness, deployment, cost, failure modes, and edge cases usually matter just as much.

**I document heavily.**  
Architecture notes, experiments, threat models, evaluation traces, and design decisions are often where I notice what I misunderstood.

### 🌱 Open source

I contribute upstream when I run into bugs, rough edges, or missing pieces that seem worth fixing.

Some changes are small compatibility fixes. Others turn into longer debugging sessions, tests, CI archaeology, and learning how mature codebases actually make decisions.

**[View my pull requests →](https://github.com/pulls?q=is%3Apr+author%3ADeepnar)**

### ⚙️ Stuff I use

Python · Java · Rust · PyTorch · FastAPI · PostgreSQL · pgvector · Redis · OR-Tools · Docker · Linux

I run Arch, self-host some of my tooling, experiment with local models, and spend an unreasonable amount of time turning configuration problems into projects.

<br>

> **Open to research and startup internships.**
>
> If you're working on something technically interesting and think I could be useful, I'd like to hear about it.
