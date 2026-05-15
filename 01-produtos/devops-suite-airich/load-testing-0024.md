# Load testing

**Produto:** AIRich DevOps Suite | **Departamento:** Produtos | **Data:** 2026-06-24

---

## Visão Geral

O presente documento tem como objetivo apresentar Load testing para as equipes envolvidas.

Alinhado com as melhores práticas do mercado, Load testing segue padrões estabelecidos pelas equipes de engenharia e operações da AIRich Tecnologia.

## Procedimento

Para executar este processo corretamente:

1. Verificar pré-requisitos e dependências
2. Aplicar o procedimento conforme documentação técnica
3. Validar resultados com a equipe responsável
4. Atualizar a documentação com eventuais mudanças
5. Comunicar stakeholders sobre o status

## Infraestrutura


![Arquitetura Dados](../../assets/img/arquitetura-dados.png)


![Pipeline Cicd](../../assets/img/pipeline-cicd.png)


![Fluxo Autenticacao](../../assets/img/fluxo-autenticacao.png)


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
