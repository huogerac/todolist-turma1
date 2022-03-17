# Todo List - turma1 ✅

Desafio 3 da primeira turma da trilha frontend da Dev Pro

## Contributing

Este documento tem como objetivo deixar o projeto
mais padronizado. Desta forma o código ficará mais legíve e fácil de manter.

## 👉 Geral

- Utilizar 2 espaços para indentação

## 👉 CSS

- Mobile first, ou seja, pode até não funcionar muito bem no desktop, mas sempre tem que funcionar lindamente no mobile.
- Utilizar Inglês o máximo possível para os nomes dos estilos (class), exemplo `font`, `card`, `menu`
- Utilizar as cores no formato #hex, exemplo, `#fff` (evitar usode `blue` ou `white`)
- Usar o princípio do [OOCSS](https://github.com/stubbornella/oocss/wiki), exemplo, `.btn` com as propriedades mais gerais e `.btn-large` com as propriedades de tamanho ou `.btn-primary` para as cores
- Utilizar o padrão [BEM (Block Element Modifier)](http://getbem.com/introduction/), exemplo:
  - `.card` representa um bloco
  - `.card__title` ou `.card__text` representa um elemento dentro do bloco
  - `.card__btn--is-active` ou `.card__btn--inactive` representa um modificador
- Remover CSS sem uso
- Separar estilo em grupos, exemplo, `menu.css`, `cores.css`
- Tentar ser ao máximo consistente, ter um padrão independente do padrão acima de tudo
- classes raiz com nomes representativos, exemplo, `banner-marketing`
- classes aninhadas utilizando a classe do pai abreviada, exemplo, `bm__title` ao invés de `banner-marketing__title`

```
<div class="banner-marketing">
  <div class="bm-container">
    <p class="bmc__title"></p>
  </div>
</div>
```

## 👉 HTML

- Utilizar [HTML Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html) onde possível, exemplo, `<main>`, `<footer>` ao invés de `<div>`
