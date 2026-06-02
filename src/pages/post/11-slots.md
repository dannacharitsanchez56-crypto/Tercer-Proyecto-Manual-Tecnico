---
title: "11 - Slots en Astro"
layout: ../../Layouts/Baselayouts.astro
---

Los slots en Astro son una herramienta que permite insertar contenido dinámico dentro de un componente.

En otras palabras, un slot es un espacio vacío dentro de un componente que se llena con contenido desde fuera.

Esto hace que los componentes sean mucho más flexibles y reutilizables.

---

## 🧠 ¿Qué es un slot?

Un slot es un marcador dentro de un componente donde se puede insertar contenido personalizado.

Ejemplo simple:
- El componente es una caja
- El slot es lo que metes dentro de esa caja

---

## 🚀 Ejemplo básico de slot

### Componente

```astro id="s1"
<div class="border p-4 rounded">
  <slot />
</div>