# Distributed tracing

**Produto:** AIRich DevOps Suite | **Departamento:** Produtos | **Data:** 2026-06-21

---

## Visão Geral

Este guia técnico aborda os aspectos fundamentais de Distributed tracing na AIRich.

Alinhado com as melhores práticas do mercado, Distributed tracing segue padrões estabelecidos pelas equipes de engenharia e operações da AIRich Tecnologia.

## Procedimento

As etapas recomendadas são:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Pipeline Cicd](/assets/img/pipeline-cicd.png)


![Plataforma Geral](/assets/img/plataforma-geral.png)

| Componente | Tecnologia | Versão | Propósito |
|------------|------------|--------|----------|
| Backend | Python | 3.12 | Lógica de negócio |
| Banco de Dados | PostgreSQL | 16 | Persistência |
| Cache | Redis | 7.x | Performance |
| Mensageria | RabbitMQ | 3.13 | Comunicação async |
| Container | Docker | 25.x | Isolamento |
| Orquestração | Kubernetes | 1.29 | Escalabilidade |

---

*Documento mantido pela equipe de Produtos — AIRich Tecnologia*
