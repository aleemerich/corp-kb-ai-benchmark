# KB: Casos de uso

**Produto:** Suporte | **Departamento:**  | **Data:** 2026-04-11

---

## Visão Geral

Este manual operacional descreve os processos e responsabilidades de KB: Casos de uso.

No cenário atual de transformação digital, KB: Casos de uso desempenha um papel fundamental na capacidade da AIRich de entregar valor aos seus clientes.

## Procedimento

Etapas recomendadas:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Topologia Rede](../assets/img/topologia-rede.png)


![Fluxo Autenticacao](../assets/img/fluxo-autenticacao.png)


![Paineis Relatorios](../assets/img/paineis-relatorios.png)


![Plataforma Geral](../assets/img/plataforma-geral.png)

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
