---
Ordem: 2
Data: 2025-03-07
Status: ✅ Concluído
tags:
  - aula
  - curso
---

## Estrutura

### **Diferenças em Relação ao Exemplo Anterior**

1. **Menos Itens** :
    
    - O container possui apenas **3 elementos** `.interno` (vs. 12 no exemplo anterior).
    - Isso permite visualizar melhor o alinhamento centralizado em ambos os eixos.
    
2. **Novas Propriedades do Container** :
    
    - `align-items: center`: Alinha os itens **verticalmente** no centro do container (eixo transversal).
    - Mantém `justify-content: center` para alinhamento horizontal.

---

### **Código Analisado**



```css
.flexbox {

	display: flex;
	
	flex-wrap: wrap;
	
	justify-content: center; /* Alinha horizontal (eixo principal) */
	
	align-items: center; /* Alinha vertical (eixo transversal) */

}
```
---

### **Eixo Principal vs. Eixo Transversal**

- **Eixo Principal (Main Axis)** :
    
    - Direção padrão: **horizontal** (definida por `flex-direction`).
    - Controlado por `justify-content` (ex: `center`, `space-between`).
    
- **Eixo Transversal (Cross Axis)** :
    
    - Direção perpendicular ao eixo principal (ex: vertical se `flex-direction: row`).
    - Controlado por `align-items` (ex: `center`, `flex-start`).

---

### **Resultado do Exemplo**

- Os **3 círculos** estão:
    - Centralizados **horizontalmente** (`justify-content: center`).
    - Centralizados **verticalmente** (`align-items: center`).
    - Distribuídos em uma única linha (como `flex-wrap: wrap` não é necessário aqui, mas está presente para casos de mais itens).

---

### **Dica de Uso**

- Use `align-items` para ajustar o alinhamento vertical em containers com **altura definida** (ex: `.externo` com `height: 400px`).
- Combine `justify-content` e `align-items` para centralização perfeita em ambas as direções.


