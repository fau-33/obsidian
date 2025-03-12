---
Data inicio: 2025-03-12
Data fim: 
Status: 💪 Em execução
tags:
  - curso
  - formacao-dev
  - web
  - javascript
---
### Capítulos
```dataview
table Status, row["Data inicio"] as Inicio, row["Data fim"] as Fim
From #capitulo
Where contains(file.folder, this.file.folder)
Sort Ordem
```