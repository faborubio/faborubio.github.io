# faborubio.github.io

Redirección de **[faborubio.github.io](https://faborubio.github.io/)** → **[faborubio.dev](https://faborubio.dev/)**, mi portafolio personal.

## ¿Por qué existe?

Este es el repo de usuario de GitHub Pages, que sirve en la raíz de mi dominio de GitHub. En lugar de duplicar contenido, redirige al portafolio real (React + Vite, bilingüe ES/EN, PWA), cuyo código vive en [`Portafolio-maestro`](https://github.com/faborubio/Portafolio-maestro).

## ¿Cómo funciona?

Un único `index.html` con redirección en tres capas:

1. `window.location.replace()` — instantánea, sin dejar rastro en el historial
2. `<meta http-equiv="refresh">` — respaldo si JavaScript está desactivado
3. Enlace manual visible — por si todo lo demás falla

Incluye `<link rel="canonical">` para que los buscadores indexen el portafolio como dirección oficial.

---

🗂️ ¿Buscas mis proyectos? Mira el [panel de proyectos](https://faborubio.github.io/dashboard/) con el estado y fase de cada uno.
