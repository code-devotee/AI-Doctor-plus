---
name: compound-property-prediction
description: Predict key physicochemical, ADMET, and developability properties for lead compounds or candidate molecules.
---

# Compound Property Prediction (化合物性质预测)

用于预测候选分子的理化性质、ADMET 和研发适用性。

## When to Use

- 分子设计前需要评估溶解度、代谢、清除率等
- 需要快速判断候选化合物的开发可行性
- 对先导化合物进行优先级排序

## 底层实现

- 技术: 规则模型 + 经验分析 + 更高层统计预测
- 重点字段: logP、溶解度、清除率、膜通透性等

## 调用方式

```bash
/compound-property-prediction "Candidate molecule with piperidine scaffold and aryl amide"
```
