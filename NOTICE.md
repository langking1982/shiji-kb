# NOTICE

This project is a community derivative of **shiji-kb** (史记知识库) by 鲍捷 / [@baojie](https://github.com/baojie).

- **Upstream project**: <https://github.com/baojie/shiji-kb> (main @ 6b836e3, forked 2026-10-23)
- **Upstream author**: 鲍捷 (baojie@gmail.com)
- **Upstream licensing** (as stated in the upstream README):
  - Annotated data (标注数据): **CC BY-NC-SA 4.0** — Attribution-NonCommercial-ShareAlike
  - Analysis scripts (分析脚本): **MIT License**
  - The Records of the Grand Historian (《史记》原文): Public Domain
- **Upstream LICENSE file status**: the upstream repository does not currently commit a LICENSE file at its root; this derivative restores the full CC BY-NC-SA 4.0 text as declared in the upstream README, and the original MIT notice is preserved below.

## Original copyright notices (retained, as required)

```
Copyright (c) 2026 鲍捷 (baojie) — annotated data, docs, wiki, skills, and knowledge-graph assets of shiji-kb
Licensed under CC BY-NC-SA 4.0 (data) / MIT (analysis scripts)

Copyright (c) 司马迁 (c. 145–86 BC) — 《史记》原文，公有领域 (public domain)
原始文本来源：维基文库《史记》 (Wikisource)
```

## Modifications in this derivative (升级点)

Maintained by [@langking1982](https://github.com/langking1982) with AI assistance (WorkBuddy / GLM):

1. **Restored the LICENSE file** — the upstream repo declares CC BY-NC-SA 4.0 + MIT dual licensing in its README but ships no LICENSE file; this derivative commits the canonical CC BY-NC-SA 4.0 text and an MIT notice for scripts.
2. **Added proper attribution infrastructure** — `NOTICE.md` (this file), `CITATION.cff`, and a derivative banner at the top of `README.md`, keeping the full provenance chain visible.
3. **Added `UPGRADES.md`** — a living changelog of derivative-specific improvements, separate from upstream `CHANGELOG.md`.
4. **Added English README (`README_EN.md`)** — lowers the barrier for international users.
5. **Added `CITATION.cff`** — one-click citation metadata for the GitHub "Cite this repository" button.
6. **Added CI (`.github/workflows/ci.yml`)** — GitHub Actions workflow that pip-installs `requirements.txt` and sanity-imports the rendering scripts, so future contributions don't break the pipeline silently.
7. **Dependency & compliance hygiene** — `requirements.txt` is installed and verified by CI; license tags in repo metadata.

This derivative keeps the **same licensing as upstream**: CC BY-NC-SA 4.0 for annotated data, MIT for analysis scripts. Therefore, **commercial use of the annotated data requires permission from the upstream author** (and this derivative's maintainer does not grant such permission on the author's behalf). The `《史记》` original text remains public domain.

If you are the upstream author and want any of this adjusted (banner wording, links, license file layout), please open an issue — it will be handled promptly.
