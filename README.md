# Projeto: Galeria de Arte

## 📄 Descrição do Projeto

Este projeto é uma página web simples e elegante que exibe uma galeria de obras de arte. O foco foi criar um layout limpo e responsivo, onde as informações de cada obra (título e autor) são sobrepostas na imagem, aparecendo de forma clara e estilizada. A página foi construída utilizando apenas HTML5 e CSS3, com foco em boas práticas de estruturação e estilização.

## 🚀 Tecnologias Utilizadas

-   **HTML5:** Para a estruturação semântica do conteúdo.
-   **CSS3:** Para estilização, layout e responsividade.

## 🧠 O que aprendi neste projeto

Este projeto foi uma excelente oportunidade para praticar e solidificar conceitos fundamentais de desenvolvimento front-end. Os principais aprendizados foram:

1.  **Estrutura HTML Semântica e Nomenclatura BEM**
    Utilizei tags semânticas como `<main>`, `<section>` e `<article>` para organizar o conteúdo de forma lógica e acessível. Adotei a metodologia **BEM (Block, Element, Modifier)** para nomear as classes CSS (ex: `artwork-gallery__container-image`). Isso tornou o código mais organizado, legível e fácil de manter, evitando conflitos de estilo.

2.  **Layout Moderno com Flexbox**
    O layout principal da galeria foi construído com `display: flex`. Aprendi a usar `justify-content: center` e `align-items: center` para centralizar os itens perfeitamente na página. A propriedade `gap` foi usada para criar um espaçamento consistente entre os itens, e `flex-wrap: wrap` garantiu que a galeria se adaptasse a diferentes tamanhos de tela, quebrando a linha quando necessário.

3.  **Posicionamento Avançado (Texto sobre Imagem)**
    O maior desafio e aprendizado foi sobrepor o texto na imagem. Consegui isso utilizando:
    -   `position: relative;` no contêiner da imagem (`.artwork-gallery__container-image`).
    -   `position: absolute;` no bloco de informações (`.artwork-gallery__info`).
    Essa técnica me permitiu posicionar o texto de forma precisa com as propriedades `bottom` e `left`, fazendo com que o texto ficasse "preso" ao seu contêiner pai.

4.  **Efeitos Interativos com `:hover`**
    Criei uma microinteração simples usando a pseudo-classe `:hover` para mudar a opacidade da imagem e o cursor do mouse, dando um feedback visual ao usuário de que o elemento é clicável ou interativo.

5.  **Tipografia Responsiva com a técnica `font-size: 62.5%`**
    No `<html>`, defini `font-size: 62.5%`. Isso "reseta" a medida `1rem` para ser equivalente a `10px` (em vez do padrão de `16px`), o que tornou muito mais fácil e intuitivo definir tamanhos de fontes e outros elementos de forma escalável e acessível.

6.  **Importância do CSS Reset**
    Utilizei um arquivo `reset.css` para remover os estilos padrão do navegador (margens, preenchimentos, etc.). Isso garante que a página tenha uma aparência consistente em diferentes navegadores e me deu controle total sobre a estilização.

## 📁 Estrutura de Pastas

A estrutura de arquivos do projeto está organizada da seguinte forma:

```
/
├── 📄 index.html
├── 📁 src/
│   ├── 📁 css/
│   │   ├── 📄 reset.css
│   │   └── 📄 style.css
│   └── 📁 imagens/
│       ├── 🖼️ rome.png
│       ├── 🖼️ boat.png
│       ├── 🖼️ sand-and-sea.png
│       └── 🖼️ starry-night.png
└── 📄 README.md

Documentação do projeto

```

## 📂 Como Executar o Projeto

1.  Faça o clone ou o download deste repositório:
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```
2.  Abra o arquivo `index.html` no seu navegador de preferência.
