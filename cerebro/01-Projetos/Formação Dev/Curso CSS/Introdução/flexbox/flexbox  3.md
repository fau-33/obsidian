---
Ordem: 3
Data: 2025-03-07
Status: ✅ Concluído
tags:
  - aula
  - curso
---

## Estrutura

### **Novidades em Relação aos Exemplos Anteriores**

1. **Direção da Coluna** :
    
    - `flex-direction: column`: Altera o **eixo principal** para vertical (ao invés da horizontal padrão).
    - Isso faz os itens se organizarem de cima para baixo.
    
2. **Centralização Aninhada** :
    
    - Cada item `.interno` agora é um **flex container** (`display: flex` via classe `.centralizar`).
    - `justify-content: center` e `align-items: center`: Centralizam o conteúdo (números) dentro de cada círculo.
    
3. **Cores Personalizadas** :
    
    - Classes `.cor-1` (fúcsia) e `.cor-2` (coral) adicionam variação visual aos itens.


```css
.flexbox {
  display: flex;
  flex-direction: column; /* Eixo principal vertical */
  justify-content: center; /* Alinha itens verticalmente */
  align-items: center;     /* Alinha itens horizontalmente */
}

.centralizar {
  display: flex; /* Cada item vira um container flex */
  justify-content: center;
  align-items: center;
}
```


### **Eixos e Alinhamento**

- **Eixo Principal (Vertical)** :
    
    - Controlado por `justify-content: center` → Centraliza itens verticalmente.
    
- **Eixo Transversal (Horizontal)** :
    - Controlado por `align-items: center` → Centraliza itens horizontalmente.

---

### **Resultado do Exemplo**

- Os **3 círculos** estão:
    - Organizados em **coluna vertical** .
    - Centralizados **horizontal e verticalmente** no container vermelho.
    - Com números centralizados internamente (graças à classe `.centralizar`).

---

### **Dica de Uso**

- Use `flex-direction: column` para layouts verticais (ex: menus laterais, listas).
- Aninhe containers flex para **centralizar conteúdo interno** (como textos ou ícones).