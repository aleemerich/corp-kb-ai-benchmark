# Monitor: Prometheus

**Produto:** Infraestrutura | **Departamento:**  | **Data:** 2026-01-01

---

## Visão Geral

O objetivo deste material é documentar as práticas recomendadas para Monitor: Prometheus.

Alinhado com as melhores práticas do mercado, Monitor: Prometheus segue padrões estabelecidos pelas equipes da AIRich Tecnologia.

## Procedimento

Para executar corretamente:

1. Verificar pré-requisitos
2. Aplicar o procedimento
3. Validar resultados
4. Atualizar documentação
5. Comunicar stakeholders

## Infraestrutura


![Topologia Rede](../../assets/img/topologia-rede.png)


![Plataforma Geral](../../assets/img/plataforma-geral.png)

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
