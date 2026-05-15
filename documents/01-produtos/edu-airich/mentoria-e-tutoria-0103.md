# Mentoria e tutoria

**Produto:** AIRich Edu | **Departamento:** Produtos | **Data:** 2026-04-19

---

## Visão Geral

Esta especificação técnica define os requisitos e procedimentos para Mentoria e tutoria.

A evolução constante do ecossistema AIRich demanda processos bem definidos. Mentoria e tutoria foi documentado para orientar as equipes técnicas e operacionais na execução de suas atividades.

## Procedimento

As etapas recomendadas são:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Plataforma Geral](../assets/img/plataforma-geral.png)

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
