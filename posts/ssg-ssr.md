---
title: "SSG vs SSR"
date: "2020-01-02"
---

É recomendado utilizar **Static Generation** (com ou sem data) sempre que possível pois sua página pode ser construída uma vez e então servida pela CDN, o que a torna muito mais rápida ao invés de fazer um novo request em cada acesso.

Você pode utilizar SSG para muitas páginas:

- E-commerces
- Blogs
- Listas de produtos
- Documentação

Pergunte-se: "Posso pré-renderizar esta páginas **antes** do request de um usuário?" Se a resposta é sim então você utilizar SSG.

Por outro lado, SSG **não** é uma boa ideia se você não pode carregar o conteúdo da página antes do acesso do usuário. Isso pode acontecer quando o conteúdo da página muda frequentemente ou depende de requests.

Nesse caso você deve utilizar **Server-Side Rendering**.
