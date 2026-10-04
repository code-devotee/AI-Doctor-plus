---
name: synthesis-route-planning
description: Plan reasonable synthetic routes, identify key steps, and assess route feasibility and complexity for candidate compounds.
---

# Synthesis Route Planning (合成路线规划)

用于规划候选分子的合成路线、关键中间体和路线可行性评估。

## When to Use

- 需要为候选分子设计合成路线
- 评估路线是否过于复杂、低效率或不可行
- 寻找更适合规模化制备的合成策略

## 底层实现

- 技术: 路线生成 + 复杂度评估 + 工艺可行性判断
- 输出: 关键中间体、路线总步数和可行性结论

## 调用方式

```bash
/synthesis-route-planning "Design a synthesis route for a pyrrole-linked kinase inhibitor"
```
