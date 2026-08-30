# DynaMem-Bench 数据集

本目录包含论文使用的 DynaMem-Bench 数据集，用于评测实体状态变化后的动态记忆幻觉。数据集不绑定 MemGuard，也可用于评测其他长期记忆 Agent。

## 文件

- `data/dynmem_bench_base.jsonl`：640 条 benchmark 用例。
- `data/dataset_summary.json`：数据集数量和分布摘要。
- `data/README.md`：数据格式和使用说明。

数据集覆盖五类场景、三种难度、四类幻觉，并包含 496 条不可回答用例。属性值使用不规则标识符，以减少预训练数据泄露。
