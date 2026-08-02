<h1 align="center">Deepesh Sonar</h1>

<p align="center">
  Retrieval and long-term memory for language models
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/deepeshsonar/">LinkedIn</a> ·
  <a href="mailto:18deepnar@gmail.com">Email</a> ·
  <a href="https://github.com/Deepnar/ice">ICE</a>
</p>

---

I'm a third-year Computer Engineering student in Mumbai. I started learning ML in December
2025 and spent the next seven months building **ICE**, a memory system for language models,
mostly on my own. The paper is submitted to ACM TIST.

The problem I keep coming back to: every conversation with a model starts from zero. Bigger
context windows haven't fixed that, because a window is a buffer, not a memory. What I found
building ICE is that the instinct to retrieve *more* is wrong — retrieval quality is governed
by what you leave out.

### How I work

I try to break my own claims before someone else does. ICE ships with a **fidelity audit**
that lists which of its components were genuinely defective, which the benchmark never
exercised, and which actually carried the result — because ablation studies routinely conflate
those three, and a component that never ran isn't a component that failed.

The honest version of my headline result is that ICE *matches* a strong vector-RAG baseline on
answer quality rather than beating it. It does so on 32% fewer context fragments, wins blind
head-to-head comparisons 30.6% to 21.2%, and holds up under context density where the baseline
fails 94.2% of probes. I'd rather state that precisely than round it up.

### What I've built

**[ICE](https://github.com/Deepnar/ice)** — a local-first memory layer between any
OpenAI-compatible client and a locally served model. Six retrieval legs fused with weighted
Reciprocal Rank Fusion, a bi-temporal knowledge graph where superseded facts stay queryable as
history, and a classifier that decides whether long-term retrieval should fire at all.
Evaluated with **LSREP**, a longitudinal protocol I designed for it.

**[timetable-generator](https://github.com/Deepnar/timetable-generator)** — constraint-driven
scheduling. One engine, seven timetable types, OR-Tools CP-SAT and a greedy solver behind a
hard-constraint registry that fails closed.

**[prompt-routing-classifier](https://github.com/Deepnar/prompt-routing-classifier)** —
multi-label topic and intent classification for routing prompts to specialised models. Became
ICE's classification engine.

**[DS-Practice](https://github.com/Deepnar/DS-Practice)** — algorithms, data structures, OS and
networking from coursework, implemented from the algorithm rather than adapted from a library.

### Elsewhere

Python and Java, PyTorch, FastAPI, PostgreSQL and pgvector, OR-Tools. I run Arch on a machine
I partitioned the hard way, and I write more documentation than most people think is
reasonable.

Currently looking for **research and startup internships** in retrieval, memory, or applied ML
systems. If you're working on any of that, I'd like to hear from you.
