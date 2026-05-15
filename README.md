# corp-kb-ai-benchmark

![AIRich Tecnologia](assets/img/logo/airich-logo.png)

> **AIRich Tecnologia** — Base de conhecimento corporativa sintética para benchmark de IA

For English version, [click here](README.en.md).

## Sobre o Projeto

O **corp-kb-ai-benchmark** é uma base de conhecimento sintética que simula o dia a dia de uma empresa de tecnologia brasileira com operações internacionais. Conta com mais de **10.000 documentos em PT-BR** e aproximadamente **6.750 documentos em EN**, totalizando cerca de **16.750 arquivos markdown**.

A AIRich Tecnologia é uma empresa fictícia com 10 produtos, 10 departamentos e uma base documental que inclui:

- Especificações de produto e roadmaps
- Runbooks de engenharia e suporte
- Tickets de suporte com scripts de diagnóstico
- Propostas comerciais e contratos
- Políticas de RH e compliance
- Relatórios financeiros
- Documentos jurídicos e LGPD
- Campanhas de marketing
- Documentação de infraestrutura
- Scripts operacionais em Bash e Python

## Estrutura

```
corp-kb-ai-benchmark/
├── 01-produtos/           # 1.500 docs PT-BR + 1.012 EN
├── 02-engenharia/         # 2.000 docs PT-BR + 1.350 EN
├── 03-suporte/            # 2.000 docs PT-BR + 1.350 EN
├── 04-vendas/             # 1.200 docs PT-BR + 810 EN
├── 05-rh/                 # 800 docs PT-BR + 540 EN
├── 06-financeiro/         # 800 docs PT-BR + 540 EN
├── 07-juridico/           # 500 docs PT-BR + 338 EN
├── 08-marketing/          # 500 docs PT-BR + 338 EN
├── 09-infraestrutura/     # 500 docs PT-BR + 338 EN
├── 10-scripts/            # 200 docs PT-BR + 134 EN
├── assets/
│   └── img/               # Imagens baixadas localmente
└── README.md
```

## Distribuição de Tamanhos (PT-BR)

| Categoria | Porcentagem | Faixa de palavras |
|-----------|------------|-------------------|
| Curta | 20% | 100-200 |
| Média | 50% | 300-500 |
| Longa | 25% | 600+ |
| Muito longa | 5% | 1500+ |

## Idiomas

- **PT-BR:** 10.000 documentos (base completa)
- **EN:** 6.750 documentos (67,5% traduzidos)
- A organização PT/EN varia por departamento para simular inconsistência real

## Produtos AIRich

1. AIRich Platform — SaaS principal
2. AIRich API Gateway
3. AIRich Mobile
4. AIRich Analytics
5. AIRich AI Assistant
6. AIRich CRM
7. AIRich DevOps Suite
8. AIRich Security Shield
9. AIRich Pay
10. AIRich Edu

## Uso para Benchmark

Esta base pode ser utilizada para testar:

- **Modelos de IA** — compreensão de contexto longo em PT-BR
- **Pipelines RAG** — recuperação em base multilíngue desorganizada
- **Search engines** — busca semântica em PT-BR vs EN
- **Knowledge management** — organização e classificação automática
- **Agentes de IA** — navegação, sumarização e cross-reference

## Licença

Apache 2.0 — Consulte [LICENSE](LICENSE) para detalhes.
