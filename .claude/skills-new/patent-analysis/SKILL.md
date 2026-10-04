---
name: patent-analysis
description: Analyze related patents, prior art, and freedom-to-operate risk for a molecule or target area.
---

# Patent Analysis (专利分析)

用于评估候选分子或修饰思路是否存在明确的专利风险和知识产权障碍。

## When to Use

- 评估候选化合物是否已有专利覆盖
- 判断分子设计思路存在的 FTO 风险
- 为分子设计方向提供知识产权前置判断

## 底层实现

- 技术: 专利检索 + 结构相似性评估
- 重点: 现有权利要求、同族专利和侵权警示

## 调用方式

```bash
/patent-analysis "2-aryl pyridine kinase inhibitor patent landscape"
```
