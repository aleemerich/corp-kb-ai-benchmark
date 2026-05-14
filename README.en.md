# corp-kb-ai-benchmark

> **AIRich Tecnologia** — Synthetic enterprise knowledge base for AI benchmarking

## About the Project

**corp-kb-ai-benchmark** is a synthetic knowledge base that simulates the daily operations of a Brazilian technology company with international operations. It contains over **10,000 documents in PT-BR** and approximately **6,750 documents in EN**, totaling around **16,750 markdown files**.

AIRich Tecnologia is a fictional company with 10 products, 10 departments, and a document base that includes:

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

## Structure

```
corp-kb-ai-benchmark/
├── 01-produtos/           # 1,500 PT-BR + 1,012 EN docs
├── 02-engenharia/         # 2,000 PT-BR + 1,350 EN docs
├── 03-suporte/            # 2,000 PT-BR + 1,350 EN docs
├── 04-vendas/             # 1,200 PT-BR + 810 EN docs
├── 05-rh/                 # 800 PT-BR + 540 EN docs
├── 06-financeiro/         # 800 PT-BR + 540 EN docs
├── 07-juridico/           # 500 PT-BR + 338 EN docs
├── 08-marketing/          # 500 PT-BR + 338 EN docs
├── 09-infraestrutura/     # 500 PT-BR + 338 EN docs
├── 10-scripts/            # 200 PT-BR + 134 EN docs
├── assets/
│   └── img/               # Locally downloaded images
└── README.md
```

## Document Size Distribution (PT-BR)

| Category | Percentage | Word range |
|----------|-----------|------------|
| Short | 20% | 100-200 |
| Medium | 50% | 300-500 |
| Long | 25% | 600+ |
| Very long | 5% | 1500+ |

## Languages

- **PT-BR:** 10,000 documents (complete base)
- **EN:** 6,750 documents (67.5% translated)
- PT/EN organization varies per department to simulate real-world inconsistency

## AIRich Products

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

## Benchmark Use Cases

This base can be used to test:

- **AI Models** — long-context understanding in PT-BR
- **RAG Pipelines** — retrieval in disorganized multilingual base
- **Search Engines** — semantic search in PT-BR vs EN
- **Knowledge Management** — automatic organization and classification
- **AI Agents** — navigation, summarization, and cross-referencing

## License

Apache 2.0 — See [LICENSE](LICENSE) for details.
