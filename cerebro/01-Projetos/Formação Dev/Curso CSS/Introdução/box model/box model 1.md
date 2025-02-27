---
Ordem: 1
Data: 2025-02-27
Status: ✅ Concluído
tags:
  - aula
  - curso
---

## Estrutura

### **Box Model no CSS: Resumo e Exemplos**

O **Box Model** é um conceito fundamental no CSS que descreve como os elementos HTML são estruturados visualmente na página. Cada elemento é tratado como uma "caixa" retangular, composta por quatro camadas principais:

1. **Content (Conteúdo):** A área onde o conteúdo do elemento é exibido (texto, imagens, etc.).
2. **Padding (Preenchimento):** Espaço interno entre o conteúdo e a borda.
3. **Border (Borda):** Linha que envolve o padding e o conteúdo.
4. **Margin (Margem):** Espaço externo ao redor da borda, separando o elemento de outros elementos.

Essas camadas podem ser ajustadas individualmente para controlar o layout e o espaçamento dos elementos.


![[Captura de tela de 2025-02-27 20-03-23.png]]

### **Box Sizing**

Por padrão, a largura e altura de um elemento incluem apenas o **conteúdo** . Para incluir o padding e a borda na largura/altura total, use a propriedade `box-sizing`.

### **Resumo Final**

- O **Box Model** define como os elementos HTML são renderizados como caixas retangulares.
- As camadas são: **content** , **padding** , **border** , e **margin** .
- Use `box-sizing: border-box` para facilitar o controle das dimensões totais.
- Compreender o Box Model é essencial para criar layouts precisos e responsivos.

