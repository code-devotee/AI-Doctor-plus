---
name: target-analysis
description: Analyze target biology, druggability, selectivity, and evidence strength for a target in the drug discovery pipeline.
---

# Target Analysis (靶点分析)

用于分析候选靶点的可药性、可验证性和药物开发价值。

## When to Use

- 评估靶点是否适合做药物发现项目
- 判断靶点是否具备可成药性和选择性
- 对多个候选靶点做优先级排序

## 底层实现

- 技术: 机制评估 + 智能分层筛选
- 输出: 靶点可药性评分、风险提醒和关键结论

## 调用方式

```bash
/target-analysis "KRAS G12C target druggability and selectivity"
```
