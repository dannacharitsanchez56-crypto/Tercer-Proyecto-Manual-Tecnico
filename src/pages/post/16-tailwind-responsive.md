---
title: "16 - Diseño Responsive con Tailwind CSS"
layout: ../../Layouts/Baselayouts.astro
---

El diseño responsive es una técnica que permite que una página web se adapte automáticamente a diferentes tamaños de pantalla como:
- celulares
- tablets
- computadores

Tailwind CSS facilita esto usando clases específicas para cada tamaño de pantalla.

---

## 🧠 ¿Qué es responsive?

Responsive significa que el diseño “responde” al tamaño del dispositivo.

Ejemplo:
- En celular → texto pequeño
- En PC → texto grande

---

## 📱 Breakpoints en Tailwind

Tailwind usa puntos de quiebre (breakpoints):

- sm → teléfonos pequeños
- md → tablets
- lg → laptops
- xl → pantallas grandes

---

## 🚀 Ejemplo básico

```astro id="r1"
<h1 class="text-sm md:text-xl lg:text-3xl">
  Texto adaptable
</h1>