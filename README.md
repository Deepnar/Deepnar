<h1 align="center">Deepesh Sonar</h1>

<p align="center">
  <b>I build systems, then try to break my own claims about them.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deepeshsonar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:18deepnar@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Mumbai,%20India-1f8a52?style=for-the-badge" alt="Mumbai">
</p>

---

Third-year Computer Engineering student in Mumbai. I work on **information retrieval,
long-term memory for language models, and evaluation** — how you measure whether a system
actually does what you claim, which turns out to be the harder half.

Most of what I build starts as a question I couldn't find a satisfying answer to. Lately those
have been: *what does a model actually need to remember, and how would you know if it
remembered the right thing?* Before that: *can a constraint solver produce a timetable nobody
has to fix by hand?*

### 🔬 How I work

**I write the criticism of my own work before someone else does.** My largest project ships
with a fidelity audit listing which of its components were genuinely defective, which the
benchmark never exercised, and which actually carried the result — because ablation studies
routinely conflate those three, and a component that never ran isn't a component that failed.

**I'd rather state a result precisely than round it up.** When my system matched a baseline
instead of beating it, that's what I reported — along with the 32% context reduction that made
the match interesting.

**I document more than most people think is reasonable.** Architecture notes, threat models,
cost models. It's how I find out whether I actually understand something.

### 🛠️ Work

| Project | What it is |
| :--- | :--- |
| **[ice](https://github.com/Deepnar/ice)** | A local-first memory layer between any OpenAI-compatible client and a locally served model. Six retrieval legs fused with weighted Reciprocal Rank Fusion, a knowledge graph where superseded facts stay queryable as history, and a classifier gating whether retrieval fires at all. Evaluated with **LSREP**, a longitudinal protocol I designed for it. Paper submitted to ACM TIST · Apache-2.0 |
| **[timetable-generator](https://github.com/Deepnar/timetable-generator)** | Constraint-driven scheduling. One engine covering seven timetable types, OR-Tools CP-SAT alongside a greedy solver, behind a hard-constraint registry that fails closed. |
| **[prompt-routing-classifier](https://github.com/Deepnar/prompt-routing-classifier)** | Multi-label topic and intent classification for routing prompts to specialised models. Built the pipeline end to end, from dataset construction to CPU inference. |
| **[DS-Practice](https://github.com/Deepnar/DS-Practice)** | Algorithms, data structures, OS and networking from coursework — written from the algorithm rather than adapted from a library. |
| **[micrograd-from-scratch](https://github.com/Deepnar/micrograd-from-scratch)** | Scalar autodiff and manual backpropagation, no ML libraries. |

Off GitHub: I've taken a civic-reporting platform through two national and state competitions
with a six-person team, where I wrote the security threat model and the infrastructure cost
model, and led the pitch.

### 🐧 Elsewhere

Python · Java · PyTorch · FastAPI · PostgreSQL and pgvector · OR-Tools · Docker.
I run Arch on a machine I partitioned the hard way.

<br>

> **Open to research and startup internships** in retrieval, memory, or applied ML systems.
> If you're working on any of that, I'd like to hear from you.
