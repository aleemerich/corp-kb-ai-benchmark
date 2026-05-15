# Script: Testar DNS

**Produto:** Suporte | **Departamento:**  | **Data:** 2026-04-23

---

## Visão Geral

Esta especificação técnica define os requisitos e procedimentos para Script: Testar DNS.

Como parte do programa de melhoria contínua da AIRich, Script: Testar DNS foi estruturado para atender às necessidades de escalabilidade e segurança.

## Procedimento

Para executar corretamente:

1. Verificar pré-requisitos
2. Aplicar o procedimento
3. Validar resultados
4. Atualizar documentação
5. Comunicar stakeholders

## Infraestrutura


![Topologia Rede](../../assets/img/topologia-rede.png)


![Infraestrutura Cloud](../../assets/img/infraestrutura-cloud.png)


![Paineis Relatorios](../../assets/img/paineis-relatorios.png)


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
