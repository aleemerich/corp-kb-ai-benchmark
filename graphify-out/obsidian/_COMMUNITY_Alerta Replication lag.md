---
type: community
cohesion: 1.00
members: 2
---

# Alerta: Replication lag

**Cohesion:** 1.00 - tightly connected
**Members:** 2 nodes

## Members
- [[Alerta Replication lag]] - document - 09-infraestrutura/en/monitoramento/alerta-replication-lag-0056.md
- [[Alerta Replication lag_1]] - rationale - 09-infraestrutura/en/monitoramento/alerta-replication-lag-0056.md

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Alerta_Replication_lag
SORT file.name ASC
```

## Connections to other communities
- 4 edges to [[_COMMUNITY_Infrastructure]]
- 1 edge to [[_COMMUNITY_Acoes preventivas]]
- 1 edge to [[_COMMUNITY_Ambiente de staging]]

## Top bridge nodes
- [[Alerta Replication lag]] - degree 6, connects to 2 communities
- [[Alerta Replication lag_1]] - degree 2, connects to 1 community