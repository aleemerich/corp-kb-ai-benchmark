# Modelo de dados

**Produto:** Engenharia | **Departamento:**  | **Data:** 2026-08-26

---

## Visão Geral

Este manual operacional descreve os processos e responsabilidades de Modelo de dados.

O investimento contínuo em Modelo de dados reflete o compromisso da AIRich com a entrega de soluções de alta qualidade.

## Procedimento

Etapas recomendadas:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Topologia Rede](/assets/img/topologia-rede.png)


![Arquitetura Dados](/assets/img/arquitetura-dados.png)


![Fluxo Autenticacao](/assets/img/fluxo-autenticacao.png)


![Plataforma Geral](/assets/img/plataforma-geral.png)

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
