# Playbook: Inside sales

**Produto:** Vendas | **Departamento:**  | **Data:** 2026-02-08 | **Versão:** 1.1

---

## Visão Geral

O presente documento tem como objetivo apresentar Playbook: Inside sales para as equipes envolvidas.

Como parte da estratégia de inovação, Playbook: Inside sales foi projetado para suportar o crescimento escalável da plataforma.

## Arquitetura


![Plataforma Geral](../../../assets/img/plataforma-geral.png)

```mermaid
flowchart TD
    A[Início] --> B[Análise]
    B --> C[Planejamento]
    C --> D[Execução]
    D --> E[Testes]
    E --> F{Aprovado?}
    F -->|Sim| G[Deploy]
    F -->|Não| D
    G --> H[Fim]
```

## Procedimento

O procedimento padrão segue as seguintes etapas:

1. **Identificação** — Reconhecer o escopo e requisitos
2. **Planejamento** — Definir recursos e cronograma
3. **Execução** — Implementar conforme especificações
4. **Validação** — Verificar critérios de aceite
5. **Documentação** — Registrar ações e decisões

## Infraestrutura

| Componente | Tecnologia | Versão | Propósito |
|------------|------------|--------|----------|
| Backend | Python | 3.12 | Lógica de negócio |
| Banco | PostgreSQL | 16 | Persistência |
| Cache | Redis | 7.x | Performance |
| Fila | RabbitMQ | 3.13 | Mensageria |
| Docker | Docker | 25.x | Container |
| K8s | Kubernetes | 1.29 | Orquestração |

## Troubleshooting

### Problema: Falha na execução

**Sintoma:** Erro inesperado durante o processo.

**Causas:** Configuração incorreta, dependência indisponível, limite de recursos.

**Solução:**
1. Verificar logs
2. Confirmar conectividade
3. Reiniciar se necessário
4. Escalar para SRE

## Segurança


![Camadas Seguranca](../../../assets/img/camadas-seguranca.png)


![Fluxo Autenticacao](../../../assets/img/fluxo-autenticacao.png)

- **Transporte:** TLS 1.3 obrigatório
- **Autenticação:** JWT com rotação de chaves
- **Autorização:** RBAC granular
- **Auditoria:** Log imutável
- **Criptografia:** AES-256

---

*Documento mantido pela equipe de  — AIRich Tecnologia*
