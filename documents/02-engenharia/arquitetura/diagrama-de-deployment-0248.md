# Diagrama de deployment

**Produto:** Engenharia | **Departamento:**  | **Data:** 2026-05-24

---

## Visão Geral

O presente documento tem como objetivo apresentar Diagrama de deployment para as equipes envolvidas.

A equipe da AIRich trabalha continuamente na evolução de Diagrama de deployment, incorporando feedback e avanços tecnológicos.

## Procedimento

O procedimento padrão segue as seguintes etapas:

1. **Identificação** — Reconhecer o escopo e requisitos
2. **Planejamento** — Definir recursos e cronograma
3. **Execução** — Implementar conforme especificações
4. **Validação** — Verificar critérios de aceite
5. **Documentação** — Registrar ações e decisões

## Infraestrutura


![Tela Login](../assets/img/tela-login.png)


![Topologia Rede](../assets/img/topologia-rede.png)


![Pipeline Cicd](../assets/img/pipeline-cicd.png)


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
