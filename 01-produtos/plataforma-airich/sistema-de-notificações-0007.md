# Sistema de notificações

**Produto:** AIRich Platform | **Departamento:** Produtos | **Data:** 2026-07-07

---

## Visão Geral

O presente documento tem como objetivo apresentar Sistema de notificações para as equipes envolvidas.

Como parte da estratégia de inovação da AIRich, Sistema de notificações foi projetado para suportar o crescimento escalável da plataforma, garantindo robustez e flexibilidade.

## Procedimento

O fluxo de trabalho padrão inclui:

1. **Kickoff** — Alinhamento de escopo com stakeholders
2. **Desenvolvimento** — Implementação seguindo padrões de código
3. **Code Review** — Revisão por pares antes do merge
4. **Testes** — Validação automatizada e manual
5. **Deploy** — Publicação em ambiente controlado
6. **Monitoramento** — Acompanhamento pós-deploy

## Infraestrutura


![Pipeline Cicd](../../assets/img/pipeline-cicd.png)


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
