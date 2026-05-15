# Modo noturno

**Produto:** AIRich Edu | **Departamento:** Produtos | **Data:** 2026-06-13

---

## Visão Geral

Este guia técnico aborda os aspectos fundamentais de Modo noturno na AIRich.

A equipe de produto da AIRich trabalha continuamente na evolução de Modo noturno, incorporando feedback de clientes e avanços tecnológicos para manter a competitividade da plataforma.

## Procedimento

As etapas recomendadas são:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Arquitetura Dados](../../assets/img/arquitetura-dados.png)


![Plataforma Geral](../../assets/img/plataforma-geral.png)

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
