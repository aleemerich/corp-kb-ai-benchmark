# Split de pagamentos

**Produto:** AIRich Pay | **Departamento:** Produtos | **Data:** 2026-09-26

---

## Visão Geral

O presente documento tem como objetivo apresentar Split de pagamentos para as equipes envolvidas.

Como parte do programa de melhoria contínua da AIRich, Split de pagamentos foi estruturado para atender às necessidades de escalabilidade, segurança e performance exigidas pelo mercado.

## Procedimento

As etapas recomendadas são:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Topologia Rede](../assets/img/topologia-rede.png)


![Sequencia Pagamento](../assets/img/sequencia-pagamento.png)

| Métrica | Meta | Atual | Tendência |
|------|------|-------|----------|
| Disponibilidade | 99.95% | 99.97% | ↑ |
| Latência P95 | < 200ms | 156ms | ↓ |
| Taxa de Erro | < 0.1% | 0.05% | ↓ |
| Throughput | 10K req/s | 12.5K req/s | ↑ |

---

*Documento mantido pela equipe de Produtos — AIRich Tecnologia*
