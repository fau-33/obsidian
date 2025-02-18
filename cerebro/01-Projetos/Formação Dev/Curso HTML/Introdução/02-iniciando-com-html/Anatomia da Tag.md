---
Ordem: 
Data: 2025-02-17
Status: ✅ Concluído
tags:
  - aula
  - curso
  - anatomia-html
  - web
---

## Estrutura

 *Estrutura da aula que foi ministrada no curso...*
 

## Minhas Observações

*adicionar minhas observações e complementos*

Claro! Vou explicar como as **tags HTML** funcionam e fornecer exemplos práticos. As tags são os elementos fundamentais do HTML, usados para estruturar e formatar o conteúdo de uma página web.

---

### **O que são Tags HTML?**
- **Tags HTML** são instruções que definem a estrutura e o significado do conteúdo em uma página web.
- Elas geralmente vêm em pares: uma **tag de abertura** (`<tag>`) e uma **tag de fechamento** (`</tag>`).
- Algumas tags são **auto-fecháveis**, como `<img>` ou `<br>`.

---

### **Exemplos de Tags HTML**

#### 1. **Títulos (`<h1>` até `<h6>`)**
- Usadas para criar títulos e subtítulos.
- `<h1>` é o mais importante, e `<h6>` o menos importante.

```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<h3>Outro Subtítulo</h3>
```

---

#### 2. **Parágrafos (`<p>`)**
- Usada para criar blocos de texto.

```html
<p>Este é um parágrafo simples.</p>
<p>Aqui está outro parágrafo com mais informações.</p>
```

---

#### 3. **Links (`<a>`)**
- Usada para criar links para outras páginas ou sites.
- O atributo `href` define o destino do link.

```html
<a href="https://www.google.com">Visite o Google</a>
<a href="sobre.html">Sobre Nós</a>
```

---

#### 4. **Imagens (`<img>`)**
- Insere imagens na página.
- Atributos importantes:
  - `src`: Caminho da imagem (local ou URL).
  - `alt`: Texto alternativo caso a imagem não carregue.

```html
<img src="logo.png" alt="Logo da Empresa">
<img src="https://exemplo.com/imagem.jpg" alt="Imagem Externa">
```

---

#### 5. **Listas**
- **Lista Não Ordenada (`<ul>`):** Com marcadores (bolinhas).

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

- **Lista Ordenada (`<ol>`):** Numerada.

```html
<ol>
    <li>Primeiro item</li>
    <li>Segundo item</li>
    <li>Terceiro item</li>
</ol>
```

---

#### 6. **Divisões (`<div>` e `<span>`)**
- `<div>`: Bloco de conteúdo usado para agrupar elementos.
- `<span>`: Inline, usado para estilizar pequenas partes do texto.

```html
<div>
    <p>Este é um bloco de conteúdo.</p>
</div>

<p>Este texto tem <span style="color: red;">uma parte destacada</span>.</p>
```

---

#### 7. **Tabelas (`<table>`)**
- Usada para organizar dados em linhas e colunas.

```html
<table border="1">
    <tr>
        <th>Nome</th>
        <th>Idade</th>
    </tr>
    <tr>
        <td>Maria</td>
        <td>25</td>
    </tr>
    <tr>
        <td>João</td>
        <td>30</td>
    </tr>
</table>
```

---

#### 8. **Formulários (`<form>`)**
- Usada para coletar dados dos usuários.

```html
<form action="/enviar" method="post">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome"><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    
    <input type="submit" value="Enviar">
</form>
```

---

#### 9. **Quebra de Linha (`<br>`)**
- Insere uma quebra de linha sem criar um novo parágrafo.

```html
<p>Esta é a primeira linha.<br>Esta é a segunda linha.</p>
```

---

#### 10. **Negrito (`<b>`), Itálico (`<i>`), Sublinhado (`<u>`), e Mais**
- Formatação básica de texto.

```html
<p><b>Negrito</b>, <i>Itálico</i>, <u>Sublinhado</u>.</p>
<p><strong>Texto importante</strong> e <em>ênfase</em>.</p>
```

---

#### 11. **Citações (`<blockquote>` e `<q>`)**
- `<blockquote>`: Citação longa.
- `<q>`: Citação curta.

```html
<blockquote>
    Este é um exemplo de citação longa retirada de um livro famoso.
</blockquote>

<p>O autor disse: <q>Isto é uma citação curta.</q></p>
```

---

#### 12. **Vídeos (`<video>`)**
- Insere vídeos na página.

```html
<video width="320" height="240" controls>
    <source src="video.mp4" type="video/mp4">
    Seu navegador não suporta o elemento de vídeo.
</video>
```

---

#### 13. **Áudio (`<audio>`)**
- Insere arquivos de áudio.

```html
<audio controls>
    <source src="musica.mp3" type="audio/mpeg">
    Seu navegador não suporta o elemento de áudio.
</audio>
```

---

#### 14. **Seções Semânticas (`<header>`, `<footer>`, `<main>`, etc.)**
- Tags semânticas ajudam a organizar o conteúdo de forma lógica.

```html
<header>
    <h1>Cabeçalho da Página</h1>
</header>

<main>
    <section>
        <h2>Conteúdo Principal</h2>
        <p>Aqui vai o conteúdo principal da página.</p>
    </section>
</main>

<footer>
    <p>Rodapé da Página</p>
</footer>
```

---

### **Resumo das Características das Tags**
1. **Tags de Abertura e Fechamento:** `<tag>Conteúdo</tag>`
   - Exemplo: `<p>Texto</p>`
2. **Tags Auto-Fecháveis:** `<tag />`
   - Exemplo: `<img src="imagem.jpg" />`
3. **Atributos:** Adicionam informações extras às tags.
   - Exemplo: `<a href="link.html">Texto</a>`

---

Esses são alguns dos principais tipos de tags HTML e seus exemplos! 😊

## Referências

*Referências (links) internos e externos*





