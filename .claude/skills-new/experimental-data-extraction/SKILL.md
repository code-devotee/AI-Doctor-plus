---
name: experimental-data-extraction
description: Extract and normalize experimental results, assay findings, and structured data from reports or raw study artifacts.
---

# Experimental Data Extraction (实验数据提取)

用于从实验报告、结果表格或原始数据中提取结构化信息。

## When to Use

- 需要从实验结果里提取 IC50、Ki、EC50、稳定性和活性数据
- 需要整理多个数据源的实验信息
- 需要将非结构化实验记录标准化为结构化结果

## 底层实现

- 技术: 文本解析 + 结构化抽取
- 重点: 活性、选择性、稳定性与片段数据

## 调用方式

```bash
/experimental-data-extraction "Extract IC50 and stability data from submitted assay report"
```
