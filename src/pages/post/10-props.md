---
title: "10 - Props en Astro"
layout: ../../Layouts/Baselayouts.astro
---

Las props (properties) son una forma de enviar datos a los componentes en Astro.

Gracias a las props, un mismo componente puede reutilizarse con información diferente, lo que hace el desarrollo más flexible y organizado.

---

## 🧠 ¿Qué son las props?

Las props son parámetros que se envían a un componente para que pueda mostrar información dinámica.

Ejemplo simple:
- Un botón con texto diferente
- Una tarjeta con diferentes títulos
- Un perfil con distintos nombres

---

## 🚀 Ejemplo básico

### Componente con props

```astro id="p1"
---
const { nombre } = Astro.props;
---

<h1>Hola {nombre}</h1>