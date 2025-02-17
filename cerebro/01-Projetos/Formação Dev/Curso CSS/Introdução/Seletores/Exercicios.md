---
Ordem: 3
Data: 2025-02-17
Status: 💪 Em execução
tags:
  - aula
  - curso
---

Claro! Aqui estão **cinco exercícios práticos** para praticar o uso de **seletores CSS**. Cada exercício inclui uma descrição do que deve ser feito e como aplicar os seletores.

---

### **Exercício 1: Seletores de Tipo**
Crie um arquivo HTML com os seguintes elementos:
```html
<h1>Título Principal</h1>
<p>Este é um parágrafo.</p>
<a href="#">Clique aqui</a>
```

**Tarefa**:  
Use **seletores de tipo** para estilizar os elementos:
- Altere a cor do texto do `<h1>` para vermelho.
- Altere o tamanho da fonte do `<p>` para `18px`.
- Altere a cor do link (`<a>`) para azul e remova o sublinhado.

**Solução sugerida**:
```css
h1 {
    color: red;
}

p {
    font-size: 18px;
}

a {
    color: blue;
    text-decoration: none;
}
```

---

### **Exercício 2: Seletores de Classe**
Crie um arquivo HTML com os seguintes elementos:
```html
<div class="destaque">Texto destacado</div>
<p class="destaque">Parágrafo destacado</p>
<p>Parágrafo normal</p>
```

**Tarefa**:  
Use **seletores de classe** para estilizar apenas os elementos com a classe `destaque`:
- Altere a cor de fundo para amarelo.
- Altere a cor do texto para preto.
- Adicione um espaçamento interno (`padding`) de `10px`.

**Solução sugerida**:
```css
.destaque {
    background-color: yellow;
    color: black;
    padding: 10px;
}
```

---

### **Exercício 3: Seletores de ID**
Crie um arquivo HTML com os seguintes elementos:
```html
<div id="cabecalho">Cabeçalho da Página</div>
<p id="paragrafo-especial">Este é um parágrafo especial.</p>
```

**Tarefa**:  
Use **seletores de ID** para estilizar os elementos:
- Altere a cor do texto do elemento com ID `cabecalho` para branco e o fundo para azul escuro.
- Altere o tamanho da fonte do elemento com ID `paragrafo-especial` para `20px` e adicione uma borda sólida preta.

**Solução sugerida**:
```css
#cabecalho {
    color: white;
    background-color: darkblue;
    padding: 15px;
}

#paragrafo-especial {
    font-size: 20px;
    border: 2px solid black;
}
```

---

### **Exercício 4: Seletores de Atributo**
Crie um arquivo HTML com os seguintes elementos:
```html
<input type="text" placeholder="Digite seu nome">
<input type="password" placeholder="Digite sua senha">
<button disabled>Botão desativado</button>
```

**Tarefa**:  
Use **seletores de atributo** para estilizar os elementos:
- Altere a largura dos campos de entrada (`<input>`) para `200px`.
- Altere a cor de fundo dos botões desativados (`disabled`) para cinza claro.

**Solução sugerida**:
```css
input[type="text"], input[type="password"] {
    width: 200px;
    padding: 5px;
}

button[disabled] {
    background-color: lightgray;
    color: darkgray;
    cursor: not-allowed;
}
```

---

### **Exercício 5: Seletores Combinados (Descendentes e Filhos)**
Crie um arquivo HTML com a seguinte estrutura:
```html
<div class="container">
    <p>Parágrafo dentro do container.</p>
    <div>
        <p>Parágrafo aninhado.</p>
    </div>
</div>
<p>Parágrafo fora do container.</p>
```

**Tarefa**:  
Use **seletores descendentes** e **seletores de filhos** para estilizar os elementos:
- Altere a cor do texto de todos os `<p>` dentro do `.container` para verde.
- Altere apenas o `<p>` que é filho direto de `.container` para ter um tamanho de fonte de `22px`.

**Solução sugerida**:
```css
.container p {
    color: green;
}

.container > p {
    font-size: 22px;
}
```

---

Esses exercícios cobrem os principais tipos de seletores CSS, como **tipo**, **classe**, **ID**, **atributo**, e **combinadores**. Eles são ótimos para praticar e entender como os seletores funcionam na prática! 😊

Se precisar de mais exemplos ou explicações, é só pedir! 🚀





