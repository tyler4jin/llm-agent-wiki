---
title: Agent 推理方法对比
created: 2026-05-02
updated: 2026-05-02
type: comparison
tags: [agent-framework, comparison]
sources: [raw/papers/llm-agent-papers-2026.md]
confidence: high
---

# CoT vs ReAct vs ToT vs Reflexion

| 维度 | [[chain-of-thought]] | [[react]] | [[tree-of-thoughts]] | [[reflexion]] |
|------|---------------------|-----------|---------------------|----------|
| 推理结构 | 线性链 | 线性+行动 | 树状 | 反思循环 |
| 调用工具 | ❌ | ✅ | ❌ | ✅ |
| 回溯 | ❌ | ❌ | ✅ | ✅ |

演进：CoT → ReAct → ToT / Reflexion

相关：[[planning-and-reasoning]] [[agent-frameworks]]
