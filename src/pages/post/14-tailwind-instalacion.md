---
title: "14 - Instalación de Tailwind CSS en Astro"
layout: ../../Layouts/Baselayouts.astro
---

Tailwind CSS es un framework de CSS que permite diseñar interfaces usando clases predefinidas directamente en el HTML.
En lugar de escribir CSS tradicional, usas clases como:
- text-center
- p-4
- bg-blue-500
Esto hace que el desarrollo sea más rápido y ordenado.
---
## 🧠 ¿Qué es Tailwind CSS?

Tailwind es un framework de CSS basado en utilidades.

Esto significa que cada clase hace una sola cosa específica.

Ejemplo:
- p-4 → padding
- text-red-500 → color rojo
- flex → flexbox

---

## 🚀 Paso 1: Instalar Tailwind en Astro

Dentro de tu proyecto Astro ejecuta:

```bash id="t1"
npm install @astrojs/tailwind tailwindcss