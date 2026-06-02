---
title: "13 - Estilos CSS en Astro"
layout: ../../Layouts/Baselayouts.astro
---

En Astro puedes trabajar con CSS de varias formas: estilos globales, estilos por componente y frameworks como Tailwind CSS.

Esto permite crear interfaces modernas, organizadas y fáciles de mantener.

---

## 🧠 ¿Qué es CSS en Astro?

CSS (Cascading Style Sheets) es el lenguaje que se usa para dar diseño a las páginas web:
- colores
- tamaños
- posiciones
- animaciones

Astro permite usar CSS de forma flexible.

---

## 🎨 1. CSS dentro de un componente

Puedes escribir CSS directamente en un componente `.astro`.

```astro id="c1"
<style>
  h1 {
    color: blue;
    font-size: 2rem;
  }
</style>

<h1>Hola</h1>