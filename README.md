# AI Safety Self-Study

A public log of my self-directed learning in technical AI safety. The goal is to build the technical foundations needed for AI safety research and to keep a verifiable record of the work: code, solutions, and write-ups.

Started: October 2026 · Pace: about 6 hours per week

## Plan

1. **Foundations: Karpathy's micrograd.** Build a small autograd engine from scratch to understand backpropagation. I plan to extend it with my own additions rather than only following the tutorial.
2. **[ARENA](https://learn.arena.education/) (self-study).** Work through the curriculum on my own, in order:
   - Chapter 0: Fundamentals
   - Chapter 1: Transformer Interpretability
   - Later chapters (RL, LLM Evals) depending on time
3. **[BlueDot Impact](https://bluedot.org/) Technical AI Safety course.** Take the ~6-day intensive format during the holidays to get a structured map of the field.

## Progress

- [ ] micrograd (in progress)
- [ ] ARENA Chapter 0: Fundamentals (starting next)
- [ ] ARENA Chapter 1: Transformer Interpretability
- [ ] BlueDot Technical AI Safety (intensive, planned for the holidays)

**Where I am now:** Early on. I'm partway through micrograd and getting my ARENA workflow set up. My target is to finish Chapters 0 and 1 by around the end of December, at my current pace.

## How I work

- I read the ARENA material in the browser and run the exercise notebooks in VS Code, connected to a Google Colab GPU runtime via the Colab extension.
- Each chapter's notebooks live in their own folder in this repo, and I commit them as I go.
- I use the solutions only after a real attempt, then re-derive the answer myself.

## Repo layout

```
chapter-0/    ARENA Chapter 0 notebooks
chapter-1/    ARENA Chapter 1 notebooks
micrograd/    micrograd and my extensions
notes/        write-ups and what I learned
```

Folders are added as I reach them.

## Notes

This repo contains my own work on publicly available course material. The ARENA curriculum itself belongs to its authors; see the official repository for the original exercises.