# Artificial Intelligence — Knowledge Base

A structured, interconnected collection of 9 study notes covering the full scope of artificial intelligence, from foundational concepts to modern systems, applications, ethics, governance, philosophy, and the future.

## Overview

This knowledge base transforms the Wikipedia article on [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) (~30,000 words) into a structured learning system. Each note is a self-contained HTML file with embedded CSS, designed for offline reading and long-term study.

## Notes

| # | Title | Topics |
|---|-------|--------|
| 01 | [Foundations of AI](01-foundations.html) | Definition, scope, history (1956–present), AI winters, GPU revolution, transformer era |
| 02 | [The Goals of AI Research](02-goals.html) | Reasoning, knowledge representation, planning, learning, NLP, perception, social intelligence, AGI |
| 03 | [Traditional AI Techniques](03-traditional-techniques.html) | Search & optimisation, formal logic, probabilistic methods, classifiers |
| 04 | [Machine Learning & Neural Networks](04-machine-learning.html) | Supervised/unsupervised/reinforcement learning, neural networks, deep learning, GPT |
| 05 | [Modern AI Systems](05-modern-systems.html) | Generative AI, agents, LLMs, system stack, hardware, software frameworks |
| 06 | [Applications of AI](06-applications.html) | Healthcare, gaming, finance, military, software dev, web search, industry |
| 07 | [Ethics, Risks & Harms](07-ethics-risks.html) | Privacy, bias, misinformation, unemployment, environment, existential risk |
| 08 | [Governance & Society](08-governance.html) | AI alignment, open source, ethical frameworks, regulation |
| 09 | [Philosophy & Future of AI](09-philosophy-future.html) | Consciousness, computationalism, superintelligence, transhumanism, AI in fiction |

## Learning Path

```
01 Foundations
    ↓
02 Goals
    ↓
┌───────────┬────────────┐
03 Traditional  04 Machine Learning
    ↓               ↓
    └────→ 05 Modern Systems ←────┘
               ↓
          06 Applications
               ↓
          07 Ethics & Risks
           ↓         ↓
    08 Governance   09 Philosophy & Future
```

**Recommended order:** 01 → 02 → 03 or 04 → 05 → 06 → 07 → 08 → 09

Notes 03 and 04 can be read in either order — they represent alternative approaches (traditional vs. learning-based) to achieving the goals defined in Note 02.

## Source Material

- **Primary source:** Wikipedia's "Artificial Intelligence" article (~30,000 words, 71 sections)
- **Accessed:** September 2026
- **Coverage:** Every major section of the source article is mapped to at least one note

## Additional Research

Where the source article was thin or where current context was needed, supplementary information was incorporated. All supplementary material is consistent with the source's terminology and framing. Specific additions include:

- Historical timeline details (Dartmouth workshop, AI winters dates)
- Technical explanations of neural network architectures and transformer models
- Current regulatory landscape (EU AI Act, AI Safety Summit)
- Expanded philosophical context (Chalmers' hard problem, Searle's Chinese Room)

## Design

Each HTML file is:
- **Standalone** — all CSS embedded, no external dependencies
- **Responsive** — works on desktop, tablet, and mobile
- **Printable** — print-specific styles included
- **Navigable** — sticky top nav, table of contents, prev/next links, related notes
- **Visually consistent** — shared design system across all notes

## File Structure

```
knowledge-base/
├── index.html                      # Home page with overview and learning path
├── 01-foundations.html             # Foundations of AI
├── 02-goals.html                   # The Goals of AI Research
├── 03-traditional-techniques.html  # Traditional AI Techniques
├── 04-machine-learning.html        # Machine Learning & Neural Networks
├── 05-modern-systems.html          # Modern AI Systems
├── 06-applications.html            # Applications of AI
├── 07-ethics-risks.html            # Ethics, Risks & Harms
├── 08-governance.html              # Governance & Society
├── 09-philosophy-future.html       # Philosophy & Future of AI
└── README.md                       # This file
```

## How to Use

1. Open `index.html` in any web browser
2. Follow the recommended learning path, or jump to any note
3. Each note links to related notes for deeper exploration
4. All files work offline — no internet connection required

## Quality

All notes have been checked for:
- Source coverage (every major Wikipedia section represented)
- Terminology consistency (same terms used across all notes)
- Cross-link validity (all internal links point to existing files)
- HTML validity (semantic HTML5, responsive design)
- Independent readability (each note works standalone)
- Coherent system (notes form a connected knowledge graph)

---

*Generated September 2026 · Built with the knowledge-base-builder skill*
