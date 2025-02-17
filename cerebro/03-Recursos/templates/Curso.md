---
Data inicio: ""
Data fim: ""
Status: 🔴 Não iniciado
tags:
  - curso
---

## Capítulos

```dataview
table Status, row["Data inicio"] as Inicio, row["Data fim"] as Fim
From #capitulo
Where contains(file.folder, this.file.folder)
Sort Ordem
```

### Resumo do curso

*Coloque aqui o seu resumo*

