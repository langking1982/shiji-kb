# Shiji Knowledge Base (Derivative) — Records of the Grand Historian, Structured

> **Derivative notice**: This repository is a community derivative and upgrade of
> **[baojie/shiji-kb](https://github.com/baojie/shiji-kb)** by **Bao Jie (鲍捷)**.
> Huge thanks to the original author for open-sourcing this work. See [NOTICE.md](NOTICE.md)
> for the full attribution chain, [UPGRADES.md](UPGRADES.md) for what this derivative adds,
> and keep reading for what the project does. 🙏

An AI-constructed, interactive knowledge graph built from the *Records of the Grand
Historian* (《史记》, c. 94 BC, 570,000+ Chinese characters): syntax-highlighted
entities you can click, 3,198 structured historical events, 130 interactive
timelines ("the Shiji metro map"), and a 20,000+ page wiki — so you can query
relations and trace chronology instead of memorizing them.

⚠️ **Accuracy note**: annotations are AI-generated and openly documented with
error rates and multi-round calibration logs. Great for exploration, learning,
and research assistance — **not** an authoritative historical source.

## Key numbers (upstream, 2026-05-14)

| Metric | Value |
|---|---|
| Entities | 14,065 (126,441 annotations, 22 types) |
| Events | 3,198 (98.7% with CE dating) |
| Event relations | 7,637 (9 types) |
| Timelines | 130 interactive ("metro map") |
| Wiki pages | 20,830+ |

## What this derivative adds

- Restored the LICENSE file (upstream declares CC BY-NC-SA 4.0 data / MIT scripts but ships no LICENSE)
- `NOTICE.md` + `CITATION.cff` + README derivative banner — full provenance chain
- CI smoke tests on push/PR (Python 3.10/3.12)
- This English README

## Licensing

- Annotated data: **CC BY-NC-SA 4.0** — attribution, non-commercial, share-alike
- Analysis scripts: **MIT**
- *Shiji* original text: public domain

Commercial use of the annotated data requires permission from the upstream
author. Derivative works must keep the same license and attribution chain.

## Citing

Use the "Cite this repository" button, or see [CITATION.cff](CITATION.cff) —
please cite both this derivative and the original shiji-kb.
