<h1 align="center">Deepesh Sonar</h1>

<p align="center">
  <b>I build systems, then try to break my own claims about them.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deepeshsonar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://orcid.org/0009-0008-1762-4246"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://arxiv.org/abs/2609.16730"><img src="https://img.shields.io/badge/arXiv-LSREP-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="LSREP on arXiv"></a>
  <a href="mailto:18deepnar@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://x.com/DeepnarS"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
</p>

<p align="center">
  <a href="https://github.com/Deepnar">
    <img src="https://komarev.com/ghpvc/?username=Deepnar&label=Profile+Views&color=7C3AED&style=for-the-badge" alt="Profile Views">
  </a>
</p>

---

Third-year Computer Engineering student in Mumbai. I work on **information retrieval,
long-term memory for language models, and evaluation** — particularly how memory systems
should be evaluated when conversations, facts, and system state evolve over time.

My current research is **[LSREP](https://arxiv.org/abs/2609.16730)**, a longitudinal
state-replay protocol for evaluating conversational memory, developed alongside
**[ICE](https://github.com/Deepnar/ice)**, a local-first conversational memory architecture.

Most of what I build starts as a question I couldn't find a satisfying answer to. Lately:
*what does a model actually need to remember, how should that memory change over time,
and how would you know whether the system remembered the right thing?*

### 📄 Research

**[LSREP: A Longitudinal State-Replay Protocol for Evaluating Conversational Memory, with ICE v2 as an Audited Local-First Architecture](https://arxiv.org/abs/2609.16730)**

LSREP evaluates conversational memory as an evolving process rather than a static
retrieval task. It combines ordered replay, explicit lifecycle schedules, repeated
checkpoint probes, evolving reference answers, and mechanism-fidelity auditing.

ICE v2 serves as the audited local-first architecture in the study, alongside matched
vector-RAG baselines and a separate LongMemEval evaluation.

[**arXiv:2609.16730**](https://arxiv.org/abs/2609.16730) ·
[**ICE source**](https://github.com/Deepnar/ice) ·
[**Frozen software artifact**](https://doi.org/10.5281/zenodo.21759702)

### 🔬 How I work

**I write the criticism of my own work before someone else does.** My evaluation work
separates mechanisms that genuinely failed from mechanisms that never ran, were never
exercised, or simply weren't selected into the final context.

**I'd rather state a result precisely than round it up.** When a system matches a baseline
instead of beating it, that's the result. The interesting question is then what the
architecture actually contributed, what it cost, and which mechanisms were responsible.

**I document more than most people think is reasonable.** Architecture notes, evaluation
traces, threat models, and cost models. It's often how I find out whether I actually
understand something.

### 🛠️ Work

| Project | What it is |
| :--- | :--- |
| **[LSREP](https://arxiv.org/abs/2609.16730)** | A longitudinal state-replay protocol for evaluating conversational memory through ordered replay, repeated checkpoint probes, evolving reference answers, explicit lifecycle schedules, and mechanism-fidelity auditing. |
| **[ICE](https://github.com/Deepnar/ice)** | A local-first conversational memory architecture with typed memory stores, retrieval fusion, dynamic context budgets, and auditable retrieval paths. ICE v2 is the audited architecture evaluated under LSREP. [Software DOI](https://doi.org/10.5281/zenodo.21759702) · Apache-2.0 |
| **[timetable-generator](https://github.com/Deepnar/timetable-generator)** | Constraint-driven scheduling. One engine covering seven timetable types, OR-Tools CP-SAT alongside a greedy solver, behind a hard-constraint registry that fails closed. |
| **[prompt-routing-classifier](https://github.com/Deepnar/prompt-routing-classifier)** | Multi-label topic and intent classification for routing prompts to specialised models. Built the pipeline end to end, from dataset construction to CPU inference. |
| **[DS-Practice](https://github.com/Deepnar/DS-Practice)** | Algorithms, data structures, operating systems, and networking from coursework — written from the algorithm rather than adapted from a library. |
| **[micrograd-from-scratch](https://github.com/Deepnar/micrograd-from-scratch)** | Scalar autodiff and manual backpropagation, built without ML libraries. |

Off GitHub, I've taken a civic-reporting platform through national and state competitions
with a six-person team, where I worked on the security threat model and infrastructure cost
model and led the pitch.

### 🌱 Open source

I contribute fixes upstream when I run into problems worth fixing, particularly around
Python and ML/scientific-computing tooling.

Recent work includes contributions to
**[MNE-Python](https://github.com/mne-tools/mne-python/pulls?q=is%3Apr+author%3ADeepnar)**
and other open-source projects.

### 🐧 Elsewhere

Python · Java · PyTorch · FastAPI · PostgreSQL · pgvector · OR-Tools · Docker

I run Arch on a machine I partitioned the hard way.

<br>

> **Open to research and startup internships** in information retrieval, conversational
> memory, evaluation, and applied ML systems. If you're working on any of that,
> I'd like to hear from you.
