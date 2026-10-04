---
name: toxicology-assessment
description: Assess toxicological liabilities, safety margins, and risk flags for candidate compounds before preclinical advancement.
---

# Toxicology Assessment (毒理评估)

用于识别候选分子的毒理风险、解毒学风险和安全边界。

## When to Use

- 评估候选化合物是否存在明显的肝毒性、心脏毒性或遗传毒性风险
- 需要筛查安全窗口与临床前风险
- 为项目推进提供风险提示

## 底层实现

- 技术: 风险评估 + 安全窗分析
- 输出: 毒理风险等级、关键风险项和建议

## 调用方式

```bash
/toxicology-assessment "Lead compound with potential CYP inhibition and QT liability"
```
