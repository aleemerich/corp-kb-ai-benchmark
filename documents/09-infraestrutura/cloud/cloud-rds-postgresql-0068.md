# Cloud: RDS PostgreSQL

**Produto:** Infraestrutura | **Departamento:**  | **Data:** 2026-05-12

---

## Visão Geral

O presente documento tem como objetivo apresentar Cloud: RDS PostgreSQL para as equipes envolvidas.

A evolução constante do ecossistema AIRich demanda processos bem definidos. Cloud: RDS PostgreSQL foi documentado para orientar as equipes.

## Procedimento

Etapas recomendadas:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Fluxo Autenticacao](../../../assets/img/fluxo-autenticacao.png)


![Plataforma Geral](../../../assets/img/plataforma-geral.png)

| Componente | Tecnologia | Versão | Propósito |
|------------|------------|--------|----------|
| Backend | Python | 3.12 | Lógica de negócio |
| Banco | PostgreSQL | 16 | Persistência |
| Cache | Redis | 7.x | Performance |
| Fila | RabbitMQ | 3.13 | Mensageria |
| Docker | Docker | 25.x | Container |
| K8s | Kubernetes | 1.29 | Orquestração |

---

*Documento mantido pela equipe de  — AIRich Tecnologia*
