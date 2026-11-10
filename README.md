# My AI Systems Architecture Notes

Welcome to my personal notes on learning how to design serious AI systems.

I am sharing what I learn while going from the fundamentals to advanced enterprise AI architecture. These notes are written for me first, and for anyone else who finds them useful.

## Find the things here
[Day 1](/notes/day-001.md)
## What I am learning

This is much deeper than learning how to call an LLM API. The topics connect:

- distributed systems and software architecture
- LLM internals, agents, workflows, and model routing
- reliability, retries, fallbacks, and chaos testing
- security, tenant isolation, privacy, and threat modeling
- RAG, evaluation, observability, cloud infrastructure, and FinOps
- industry standards, compliance, governance, and responsible AI

The leverage comes from understanding how all of these pieces work together. An AI system becomes valuable in the real world when it can be trusted, operated, audited, and recovered when things go wrong.

## What you will find here

- personal explanations in plain language
- implementation experiments and small projects
- architecture diagrams and decisions
- mistakes, failures, and things I still do not understand
- notes about production systems and enterprise constraints
- links and references that helped me learn

Some notes may be beginner-friendly. Others will go very deep into distributed systems, provider failure semantics, compliance evidence, or production operations. That range is intentional.

## How I organize the notes

I use one Markdown file for each learning day:

```text
notes/day-001.md
notes/day-002.md
...
```

The notes are not meant to look like polished course chapters. They are working notes that become clearer over time. When useful, I link code and deeper documents from the note.

Start with [`docs/knowledge-map.md`](docs/knowledge-map.md), then look through [`notes/`](notes/).

## Repository map

```text
.
├── README.md                    # Personal introduction and notes index
├── docs/
│   ├── knowledge-map.md         # Topics I am exploring
│   ├── architecture/            # Diagrams and design notes
│   ├── adrs/                    # Decisions I have written down
│   ├── security-compliance/     # Security and compliance notes
│   └── operations/              # Reliability and operations notes
├── notes/                       # My day-by-day learning notes
├── templates/                   # Lightweight note helpers
└── projects/
    └── truebases-nexus/         # A project used to apply the ideas
```

These are personal learning notes, not legal, security, compliance, or production-operational advice. Standards, laws, provider behavior, and cloud pricing can change, so verify them before relying on them.
