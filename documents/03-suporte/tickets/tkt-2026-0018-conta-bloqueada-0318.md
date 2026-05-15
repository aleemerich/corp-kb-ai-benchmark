# TKT-2026-0018: Conta bloqueada

**Produto:** Suporte | **Departamento:**  | **Data:** 2026-03-10

---

## Visão Geral

Este documento fornece uma visão detalhada sobre TKT-2026-0018: Conta bloqueada no ecossistema AIRich.

Como parte do programa de melhoria contínua da AIRich, TKT-2026-0018: Conta bloqueada foi estruturado para atender às necessidades de escalabilidade e segurança.

## Procedimento

Etapas recomendadas:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Tela Login](../..//assets/img/tela-login.png)


![Topologia Rede](../..//assets/img/topologia-rede.png)


![Paineis Relatorios](../..//assets/img/paineis-relatorios.png)


![Plataforma Geral](../..//assets/img/plataforma-geral.png)

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
