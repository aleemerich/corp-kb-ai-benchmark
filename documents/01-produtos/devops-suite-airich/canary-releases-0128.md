# Canary releases

**Produto:** AIRich DevOps Suite | **Departamento:** Produtos | **Data:** 2026-02-16

---

## Visão Geral

Este guia técnico aborda os aspectos fundamentais de Canary releases na AIRich.

O investimento contínuo em Canary releases reflete o compromisso da AIRich com a entrega de soluções de alta qualidade que atendam às demandas do mercado brasileiro e internacional.

## Procedimento

Para executar este processo corretamente:

1. Verificar pré-requisitos e dependências
2. Aplicar o procedimento conforme documentação técnica
3. Validar resultados com a equipe responsável
4. Atualizar a documentação com eventuais mudanças
5. Comunicar stakeholders sobre o status

## Infraestrutura


![Pipeline Cicd](../assets/img/pipeline-cicd.png)

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
