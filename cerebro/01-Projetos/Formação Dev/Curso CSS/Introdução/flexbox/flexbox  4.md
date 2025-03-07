---
Ordem: 4
Data: 2025-03-07
Status: ✅ Concluído
tags:
  - aula
  - curso
---

## Estrutura

### **Novidades Neste Exemplo**

1. **Propriedade `flex-grow`** :
    
    - Controla **quanto um item cresce** para preencher o espaço disponível no container.
    - Valores numéricos definem a **proporção** entre os itens:
        - `.crescer-1` → `flex-grow: 1`
        - `.crescer-2` → `flex-grow: 2` (ocupa **duas vezes mais espaço** que `.crescer-1`).
    
2. **Distribuição Proporcional** :
    
    - Itens com `flex-grow` maior "empurram" os outros para ocupar mais espaço.
    - Exemplo:
        - Item 2 (`.crescer-2`) terá **largura dupla** em relação aos itens 1 e 3 (`.crescer-1`).


```css
.crescer-1 {
  flex-grow: 1; /* Ocupa 1 parte do espaço disponível */
}
.crescer-2 {
  flex-grow: 2; /* Ocupa 2 partes do espaço disponível */
}
```

### **Resultado do Exemplo**

- O container vermelho (`.externo`) tem **3 itens** :
    
    - Item 1: Largura proporcional `1`.
    - Item 2: Largura proporcional `2` (maior que os outros).
    - Item 3: Largura proporcional `1`.
    
- O espaço total é dividido na proporção **1:2:1** (ex: se o container tiver 400px de largura, os itens terão ~100px, ~200px e ~100px).

---

### **Dica de Uso**

- Use `flex-grow` para distribuir espaço **proporcionalmente** entre itens.
- Ideal para layouts onde elementos precisam ter tamanhos **relativos** (ex: barras de navegação com seções desiguais).