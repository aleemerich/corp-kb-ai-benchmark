# Network segmentation

**Produto:** AIRich Security Shield | **Departamento:** Produtos | **Data:** 2026-02-18

---

## Visão Geral

A seguir, apresentamos as diretrizes e procedimentos relacionados a Network segmentation.

No cenário atual de transformação digital, Network segmentation desempenha um papel fundamental na capacidade da AIRich de entregar valor aos seus clientes. Este documento estabelece as diretrizes para garantir consistência e eficiência.

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

| Ambiente | URL | Status | Responsável |
|---------|-----|--------|-----------|
| Produção | app.airich.com | Ativo | SRE |
| Staging | staging.airich.com | Ativo | DevOps |
| Dev | dev.airich.com | Ativo | Engenharia |
| QA | qa.airich.com | Ativo | QA Lead |

---

*Documento mantido pela equipe de Produtos — AIRich Tecnologia*
