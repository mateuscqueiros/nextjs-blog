---
title: "Duas formas de pré-renderização"
date: "2020-01-01"
---

O Next.js tem duas formas de pré-renderização: **Static Generation** e **Server-side Rendering**. A diferença está em **quando** ele gera HTML para a página.

- **Static Generation** é a pré-renderização que gera HTML em **build**. O HTML pré-renderizado é então _reusado_ em cada request.
- **Server-side Rendering** é a pré-renderização que gera HTML em **cada request**.

Ainda mais importante, o Next.js deixa você **escolher** qual método de pré-renderização utilizar em cada página.
