---
Ordem: 1
Data: 2025-03-07
Status: ✅ Concluído
tags:
  - aula
  - curso
---

## Estrutura

### **Conceito Básico**

Flexbox é um modelo de layout CSS para organizar elementos de forma **flexível** em um container, facilitando alinhamento, distribuição de espaço e responsividade.

---

### **Estrutura do Código**

1. **Container (`.externo`)**
    
    - `display: flex`: Ativa o modo Flexbox.
    - `flex-wrap: wrap`: Permite que os itens quebrem para a próxima linha se não couberem.
    - `justify-content: center`: Centraliza os itens horizontalmente.
    - `height: 400px`: Define altura fixa para o container.
    
2. **Itens (`.interno`)**
    
    - `width: 50px` e `height: 50px`: Tamanho fixo dos círculos.
    - `border-radius: 50%`: Forma circular.
    - Bordas e cores para visualização.

---

### **Principais Propriedades do Flexbox**

- **Container** :
    
    - `display: flex`: Define o container como flex.
    - `flex-direction`: Define a direção dos itens (padrão: `row`).
    - `justify-content`: Alinha itens na horizontal (ex: `center`, `space-between`).
    - `align-items`: Alinha itens na vertical (ex: `center`, `flex-start`).
    - `flex-wrap`: Controla a quebra de linha (`nowrap`, `wrap`).
    
- **Itens** :
    
    - `flex-grow`: Define quanto um item pode expandir.
    - `flex-shrink`: Define quanto um item pode encolher.
    - `flex-basis`: Tamanho inicial do item antes de distribuir espaço.

---

### **Resultado do Exemplo**

- Os círculos (`.interno`) são organizados em **linhas horizontais** , centralizados dentro do container vermelho (`.externo`).
- Se a largura total dos itens ultrapassar o container, eles quebram para a próxima linha (por causa do `flex-wrap: wrap`).

---

### **Dica de Uso**

Flexbox é ideal para layouts **unidimensionais** (linhas ou colunas) e alinhamentos complexos. Use as propriedades do container para controlar o comportamento geral e as dos itens para ajustes individuais.



### **Resumo Final**
