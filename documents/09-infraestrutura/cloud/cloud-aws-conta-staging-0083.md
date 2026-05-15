# Cloud: AWS conta staging

**Produto:** Infraestrutura | **Departamento:**  | **Data:** 2026-02-27

---

## Visão Geral

Esta especificação técnica define os requisitos e procedimentos para Cloud: AWS conta staging.

A evolução constante do ecossistema AIRich demanda processos bem definidos. Cloud: AWS conta staging foi documentado para orientar as equipes.

## Procedimento

Para executar corretamente:

1. Verificar pré-requisitos
2. Aplicar o procedimento
3. Validar resultados
4. Atualizar documentação
5. Comunicar stakeholders

## Infraestrutura


![Fluxo Autenticacao](../../../assets/img/fluxo-autenticacao.png)


![Infraestrutura Cloud](../../../assets/img/infraestrutura-cloud.png)


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
