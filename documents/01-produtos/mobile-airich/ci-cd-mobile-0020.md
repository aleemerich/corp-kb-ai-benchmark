# CI/CD mobile

**Produto:** AIRich Mobile | **Departamento:** Produtos | **Data:** 2026-02-20

---

## Visão Geral

Esta especificação técnica define os requisitos e procedimentos para CI/CD mobile.

No cenário atual de transformação digital, CI/CD mobile desempenha um papel fundamental na capacidade da AIRich de entregar valor aos seus clientes. Este documento estabelece as diretrizes para garantir consistência e eficiência.

## Procedimento

As etapas recomendadas são:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Topologia Rede](/assets/img/topologia-rede.png)


![Arquitetura Dados](/assets/img/arquitetura-dados.png)


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
