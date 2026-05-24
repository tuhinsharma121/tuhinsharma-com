---
title: "A Four-Layer Multi-Agent Architecture for Automated Journalism: Event-Driven Orchestration with Hybrid Context Management"
authors:
- admin
tags:
- Graph Query 
- Social Graph 
- Domain Node 
- Concept Node 
- Social Media Data 

date: "2026-03-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-03-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Summary. An optional shortened abstract.
summary: Four-layer multi-agent architecture for automated journalism with event-driven orchestration and hybrid context management using Deep Agents.


featured: false

links:
url_pdf: "publications/a-four-layer-multi-agent-architecture-for-automated-journalism-event-driven-orchestration-with-hybrid-context-management.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**pixabay**](https://pixabay.com/illustrations/road-town-sign-place-name-sign-924566/)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<h2> Abstract </h2>

We present a four-layer architecture for automated journal-
ism that addresses unbounded context growth, agent coordination com-
plexity, and quality assurance at scale. The system comprises Layer 1
(Observability), Layer 2 (Specialized Agents), Layer 3 (Event-Driven Or-
chestration with Listener-Aware Communication), and Layer 4 (Hybrid
Context Management with RAG). The architecture is implemented using
Deep Agents, a LangGraph-based harness employing asynchronous mes-
sage queues, agent pooling, domain-specific skills loaded via progressive
disclosure, and remote MCP servers for external tool integration. The
hybrid context strategy combines semantic compression (avg 56% reduc-
tion) with RAG-based retrieval for unbounded source handling, while
subagent spawning isolates context across delegated tasks. Evaluation
on 500 stories sampled from a 10,000-article corpus across 5 categories
demonstrates a 97.4% pipeline completion rate, average processing time
of 135 seconds per story, and an average fact-check score of 0.93. Baseline
comparisons against a single-agent RAG pipeline show a 25.4% improve-
ment in fact-check scores.


