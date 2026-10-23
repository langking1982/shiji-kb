# 本衍生仓库升级记录 (UPGRADES)

> 本文件只记录本衍生仓库相对上游 [baojie/shiji-kb](https://github.com/baojie/shiji-kb) 的增量改动。
> 上游自身的功能演进请看上游的 [CHANGELOG.md](CHANGELOG.md)。

## v1 (2026-10-23) — 合规与工程化基线

**鸣谢**：本仓库基于 [鲍捷 (@baojie)](https://github.com/baojie) 的 [shiji-kb](https://github.com/baojie/shiji-kb) 衍生开发，谨此致谢。

### 合规修复
- ✅ 补齐 `LICENSE`：上游 README 声明「标注数据 CC BY-NC-SA 4.0 / 分析脚本 MIT」，但仓库根目录缺少 LICENSE 文件。本仓库提交了 CC BY-NC-SA 4.0 标准全文与 MIT 声明，消除歧义。
- ✅ 新增 `NOTICE.md`：完整的出处链、原版权声明（保留）、许可构成、修改清单。
- ✅ 新增 `CITATION.cff`：机器可读引用元数据（GitHub「Cite this repository」按钮可用）。
- ✅ README 顶部新增衍生声明横幅：明示本项目为 baojie/shiji-kb 的衍生升级版。

### 工程化升级
- ✅ 新增 CI（GitHub Actions）：安装 `requirements.txt` 并对核心渲染脚本做 import 级冒烟测试。
- ✅ 新增 `README_EN.md`：英文版说明，面向国际用户。
- ✅ 新增本文件 `UPGRADES.md`：衍生改动与上游 CHANGELOG 分离，方便后续 rebase 上游。

### 后续规划（欢迎 PR）
- [ ] 数据 JSON 的 schema 校验进 CI
- [ ] Markdown 死链检查
- [ ] PWA / 离线阅读支持调研
- [ ] 与上游对齐的白话翻译 v2 管线回流
