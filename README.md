# corp-kb-ai-benchmark

> Synthetic enterprise knowledge base for AI benchmarking

[Versão em Português](README.pt.md)

---

## About the Project

**corp-kb-ai-benchmark** is a synthetic knowledge base that simulates the daily operations of a Brazilian technology company with international operations. It contains over **10,000 documents in PT-BR** and approximately **6,750 documents in EN**, totaling around **16,750 markdown files**.

The base was created with more documents in **PT-BR** to test in benchmarks the ability to adapt to languages other than EN, ES, and FR (the most common languages today). It also has **EN** versions for comparison and multilingual performance evaluation.

The document base includes:

- Product specifications and roadmaps
- Engineering and support runbooks
- Support tickets with diagnostic scripts
- Commercial proposals and contracts
- HR policies and compliance
- Financial reports
- Legal documents and LGPD compliance
- Marketing campaigns
- Infrastructure documentation
- Operational scripts in Bash and Python
- Diagrams, charts, and illustrations

---

## Purpose

This base is designed for benchmarking:

- **AI Models** — long-context understanding in PT-BR
- **RAG Pipelines** — retrieval in disorganized multilingual base
- **Search Engines** — semantic search in PT-BR vs EN
- **Knowledge Management** — automatic organization and classification
- **AI Agents** — navigation, summarization, and cross-referencing

---

## AIRich Tecnologia

<p align="center">
  <img src="assets/img/logo/airich-logo.png" alt="AIRich Tecnologia" width="200">
</p>

**AIRich Tecnologia** is a **fictional** technology company created specifically for this benchmark. It simulates a Brazilian SaaS company with international operations, 10 products, and 10 departments.

All data, names, metrics, and documents are synthetic and were artificially generated. Any resemblance to real companies is purely coincidental.

### Structure

```
corp-kb-ai-benchmark/
├── benchmarks/            # Benchmark results and evaluations
├── documents/             # All synthetic documents
│   ├── 01-produtos/       # 1,500 PT-BR + 1,012 EN docs
│   ├── 02-engenharia/     # 2,000 PT-BR + 1,350 EN docs
│   ├── 03-suporte/        # 2,000 PT-BR + 1,350 EN docs
│   ├── 04-vendas/         # 1,200 PT-BR + 810 EN docs
│   ├── 05-rh/             # 800 PT-BR + 540 EN docs
│   ├── 06-financeiro/     # 800 PT-BR + 540 EN docs
│   ├── 07-juridico/       # 500 PT-BR + 338 EN docs
│   ├── 08-marketing/      # 500 PT-BR + 338 EN docs
│   ├── 09-infraestrutura/ # 500 PT-BR + 338 EN docs
│   └── 10-scripts/        # 200 PT-BR + 134 EN docs
├── assets/
│   └── img/               # Images, diagrams, and logo
├── README.md              # Main (English)
└── README.pt.md           # Portuguese version
```

### Document Size Distribution (PT-BR)

| Category | Percentage | Word range |
|----------|-----------|------------|
| Short | 20% | 100-200 |
| Medium | 50% | 300-500 |
| Long | 25% | 600+ |
| Very long | 5% | 1500+ |

### Languages

- **PT-BR:** 10,000 documents (complete base)
- **EN:** 6,750 documents (67.5% translated)
- PT/EN organization varies per department to simulate real-world inconsistency

### Products

1. AIRich Platform — Main SaaS
2. AIRich API Gateway
3. AIRich Mobile
4. AIRich Analytics
5. AIRich AI Assistant
6. AIRich CRM
7. AIRich DevOps Suite
8. AIRich Security Shield
9. AIRich Pay
10. AIRich Edu

---

## License

Apache 2.0 — See [LICENSE](LICENSE) for details.
