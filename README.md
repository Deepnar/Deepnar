<h1 align="center">Deepesh Sonar</h1>

<p align="center">
  <b>I build systems, then try to break my own claims about them.</b>
</p>

<p align="center">
  <a href="https://orcid.org/0009-0008-1762-4246"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://arxiv.org/abs/2609.16730"><img src="https://img.shields.io/badge/arXiv-LSREP-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="LSREP on arXiv"></a>
  <a href="https://github.com/Deepnar">
    <img src="https://komarev.com/ghpvc/?username=Deepnar&label=Profile+Views&color=7C3AED&style=for-the-badge" alt="Profile Views">
  </a>
</p>

---

Third-year Computer Engineering student in Mumbai working on **information retrieval,
long-term memory for language models, and evaluation**.

I'm interested in a deceptively simple question: *when information changes over months of
interaction, what should a memory system remember — and how do we determine whether it
remembered the right thing?*

### 📄 Current research

**[LSREP: A Longitudinal State-Replay Protocol for Evaluating Conversational Memory, with ICE v2 as an Audited Local-First Architecture](https://arxiv.org/abs/2609.16730)**

LSREP treats conversational memory evaluation as an evolving process rather than a static
retrieval task. It combines ordered replay, explicit lifecycle schedules, repeated checkpoint
probes, evolving reference answers, and mechanism-fidelity auditing.

The protocol is evaluated with **[ICE](https://github.com/Deepnar/ice)**, my local-first
conversational memory architecture, alongside matched vector-RAG baselines and a separate
LongMemEval evaluation.

### 🔬 How I work

**I write the criticism of my own work before someone else does.** I try to distinguish
mechanisms that genuinely failed from mechanisms that never ran, were never exercised,
or simply never reached the final context.

**I'd rather state a result precisely than round it up.** Matching a baseline instead of
beating it is still a result. The interesting part is understanding what produced it.

**I document aggressively.** Architecture notes, evaluation traces, threat models, and cost
models are often where I discover that I don't understand something as well as I thought.

### 🛠️ Projects

| Project | What it is |
| :--- | :--- |
| **[ICE](https://github.com/Deepnar/ice)** | Local-first conversational memory with typed stores, retrieval fusion, dynamic context budgets, and auditable retrieval paths. |
| **[timetable-generator](https://github.com/Deepnar/timetable-generator)** | Constraint-driven scheduling across seven timetable types using OR-Tools CP-SAT and a greedy solver behind a hard-constraint registry. |
| **[prompt-routing-classifier](https://github.com/Deepnar/prompt-routing-classifier)** | Multi-label topic and intent classification for routing prompts to specialised models, from dataset construction through CPU inference. |
| **[DS-Practice](https://github.com/Deepnar/DS-Practice)** | Algorithms, data structures, operating systems, and networking implemented through coursework. |
| **[micrograd-from-scratch](https://github.com/Deepnar/micrograd-from-scratch)** | Scalar autodiff and manual backpropagation without ML libraries. |

### 🌱 Open source

I contribute fixes upstream when I run into problems worth fixing, including work in
**[MNE-Python](https://github.com/mne-tools/mne-python/pulls?q=is%3Apr+author%3ADeepnar)**
and other ML/scientific Python projects.

### 🐧 Stack

Python · Java · PyTorch · FastAPI · PostgreSQL · pgvector · OR-Tools · Docker · Linux

<br>

> **Open to research and startup internships** in information retrieval, conversational
> memory, evaluation, and applied ML systems.
