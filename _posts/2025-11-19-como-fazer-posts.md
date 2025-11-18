---
category: "admin"
date: 2025-11-18
excerpt: Breve explicação de como fazer um post no site
image: ./assets/posts/2025-11-19/imagem.jpg
layout: post
title: Como Fazer Posts
---

Este guia explica rapidamente como criar novos posts no site, onde
salvar arquivos e como estruturar imagens e conteúdo.

------------------------------------------------------------------------

## 📁 Estrutura de Pastas

A estrutura atual relevante para posts é:

    _posts/
    └── AAAA-MM-DD/
        └── como-fazer-posts.md
    assets/
    └── posts/
        └── AAAA-MM-DD/
            └── imagem.jpg

### ✔ Onde ficam os posts?

Todos os posts devem estar dentro da pasta:

    _posts/<ano>-<mês>-<dia>/

Exemplo:

    _posts/2025-11-18/meu-novo-post.md

### ✔ Onde colocar as imagens?

Use a pasta:

    assets/posts/<ano>-<mês>-<dia>/

Assim cada post fica organizado por data.

------------------------------------------------------------------------

## 📝 Modelo de Arquivo Markdown

Cada post deve começar com um bloco *front matter* igual a este:

``` yaml
---
layout: post
title: "Título do Post"
date: 2025-11-18
categories: [noticias, outros]
image: "./assets/posts/2025-11-18/imagem.jpg"
excerpt: "Resumo curto do post"
---
```

Depois disso, basta escrever normalmente em Markdown.
