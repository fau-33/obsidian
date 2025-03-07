---
Ordem: 6
Data: 2025-03-07
Status: ✅ Concluído
tags:
  - aula
  - curso
---

## Estrutura

**Resumo sobre `align-content` no Flexbox:**

O `align-content` é uma propriedade do Flexbox que **controla o alinhamento de múltiplas linhas de itens em um container flexível** , quando há espaço disponível no eixo cruzado (cross axis). Funciona apenas em containers com `flex-wrap: wrap` ou `flex-wrap: wrap-reverse` (ou seja, quando os itens quebram em várias linhas).

---

### **Características Principais:**

1. **Eixo de Atuação:**  
    Atua no **eixo cruzado** (perpendicular ao `flex-direction`):
    
    - Se `flex-direction: row` → eixo cruzado é **vertical** .
    - Se `flex-direction: column` → eixo cruzado é **horizontal** .
2. **Valores Comuns:**
    
    - `flex-start`: Agrupa as linhas no início do container.
    - `flex-end`: Agrupa as linhas no final do container.
    - `center`: Centraliza as linhas verticalmente (ou horizontalmente, dependendo do eixo).
    - `space-between`: Distribui espaço igualmente entre as linhas (sem espaço nas extremidades).
    - `space-around`: Distribui espaço igualmente ao redor das linhas.
    - `space-evenly`: Distribui espaço igualmente entre e ao redor das linhas.
    - `stretch` (padrão): Estica as linhas para ocupar todo o espaço disponível.
3. **Diferença de `align-items`:**
    
    - `align-items`: Alinha **itens individuais** dentro de uma única linha.
    - `align-content`: Alinha **linhas inteiras** em um container com múltiplas linhas.

```css
.container {
  display: flex;
  flex-wrap: wrap; /* Permite quebrar linhas */
  align-content: space-between; /* Espaço entre as linhas */
  height: 300px; /* Altura fixa para visualização */
}
```

### **Caso de Uso Típico:**

- Layouts com múltiplas linhas de itens (ex.: galerias, grids responsivos).
- Ajuste de espaçamento vertical entre linhas em containers flexíveis.

---

### **Importante:**

- Se o container tiver **apenas uma linha** , `align-content` **não tem efeito** .
- Para alinhar itens em uma única linha, use `align-items` ou `justify-content`.