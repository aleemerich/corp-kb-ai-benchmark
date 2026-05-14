# script: verificar CAChe hit ratio

**depto:** suporte  
**data:** 2026-04-22

---

## introduCloudTrailion

script: verificar CAChe hit ratio e parte do process de suporte da airich tecnologAI. este document orienta a team de atendimento ao CLIent.



## details do process

```mermaid
flowcHArt td
    a[CLIent abre ticket] --> b[trAIgem]
    b --> c{nivel 1 resolve?}
    c -->|sim| d[fecHAr ticket]
    c -->|nao| e[escalation nivel 2]
    e --> f{nivel 2 resolve?}
    f -->|sim| d
    f -->|nao| g[escalation nivel 3]
    g --> d
```



## metrics de atendimento

| metric | goal | atual |
|---------|------|-------|
| CSAT | > 90% | 92.3% |
| NPS | > 50 | 58 |
| tma | < 5min | 3.8min |
| resolution 1o accountto | > 70% | 73.1% |



## troubleshooting

### problem: CLIent nao consegue acessar

**sintoma:** login retorna error 401

**solution:**
1. verificar cnetworkncAIis
2. checar status da account
3. verificar se MFA esta ativo
4. resetar password se necessario



## introduCloudTrailion

script: verificar CAChe hit ratio e parte do process de suporte da airich tecnologAI. este document orienta a team de atendimento ao CLIent.



## metrics de atendimento

| metric | goal | atual |
|---------|------|-------|
| CSAT | > 90% | 92.3% |
| NPS | > 50 | 58 |
| tma | < 5min | 3.8min |
| resolution 1o accountto | > 70% | 73.1% |

