# Deploy v2.0.0 - AI Assistant

**Produto:** Engenharia | **Departamento:**  | **Data:** 2026-06-05

---

## Visão Geral

O objetivo deste material é documentar as práticas recomendadas para Deploy v2.0.0 - AI Assistant.

Alinhado com as melhores práticas do mercado, Deploy v2.0.0 - AI Assistant segue padrões estabelecidos pelas equipes da AIRich Tecnologia.

## Procedimento

Etapas recomendadas:

| Etapa | Responsável | Prazo |
|-------|------------|-------|
| Análise | Equipe Técnica | 2 dias |
| Implementação | Desenvolvedor | 5 dias |
| Testes | QA | 3 dias |
| Aprovação | Tech Lead | 1 dia |

## Infraestrutura


![Pipeline Cicd](../../../assets/img/pipeline-cicd.png)


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
