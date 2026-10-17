<div align="right">

**[English](README.md)** · [简体中文](README.zh-CN.md)

</div>

# zhiyan

Design set for a speech-training system — 17 expression profiles, a four-dimension rubric, and the progress-flow model.

<sub>HTML · design documentation, numbered stages</sub>

---

## What this is

The design work behind a speech-practice product, kept as separate documents rather than one long file. Sixteen numbered folders, each one decision.

## The core idea

Most speech tools return a score. A score does not tell you what to change, so the design here centres on three things instead:

**Seventeen expression profiles** — pace, pause frequency, filler rate, emphasis distribution, structural clarity, sentence length variance and so on. Each measurable, each with a threshold band rather than a pass/fail.

**A four-dimension rubric** — structure, coherence, scenario fit, language accuracy. Scored separately so a weak dimension is visible rather than averaged away.

**Issue-to-task mapping** — every finding produces a task. "Pace runs 15% fast in the opening" becomes "re-record the first 30 seconds and hold each sentence to one breath".

## The progress-flow model

The part that took the most thought: how to represent progress when the metric and the task are different things.

```
baseline recording → evidence → diagnosis → task → re-recording → comparison
```

A comparison only counts if the task and the re-recording use the same scenario. Otherwise the numbers move for reasons unrelated to the practice.

## Layout

```
0/  … 15/            sixteen numbered design documents
README.md
```

Each folder is self-contained: one decision, its reasoning, and what it rules out.

## Related

- [zhiyan-tedify](https://github.com/YGtemple/zhiyan-tedify) — the product proposal built on this design
- [Profile](https://github.com/YGtemple) — all projects

## License

MIT
