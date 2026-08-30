# DynaMem-Bench Dataset

This release contains the DynaMem-Bench dataset used in the paper for evaluating dynamic-memory hallucination after entity-state changes. It is not specific to MemGuard and can be used to evaluate other memory-based agents.

## Files

- `data/dynmem_bench_base.jsonl`: 640 benchmark cases.
- `data/dataset_summary.json`: dataset counts and distributions.
- `data/README.md`: data format and usage notes.

The dataset covers five scenarios, three difficulty levels, four hallucination types, and 496 non-answerable cases. Attribute values use irregular identifiers to reduce pretraining leakage.
