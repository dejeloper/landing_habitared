<div align="center">

# 🏠 HABITARED — Landing Page

<p>
  <img src="https://img.shields.io/badge/Astro-6.x-0f62fe?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.x-0ea5e9?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-818cf8?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/pnpm-9.x-34d399?style=for-the-badge&logo=pnpm&logoColor=white" alt="pnpm" />
</p>

> Landing page de **HABITARED** — plataforma moderna para la gestión de comunidades residenciales.  
> Construida con Astro, Tailwind CSS v4 y un design system dark con glassmorphism.

</div>

---

## 📋 Tabla de contenido

- [Estructura del proyecto](#-estructura-del-proyecto)
- [Secciones de la landing](#-secciones-de-la-landing)
- [Paleta de colores](#-paleta-de-colores)
- [Comandos](#-comandos)
- [Requisitos](#-requisitos)

---

## 📁 Estructura del proyecto

```text
landing_habitared/
├── public/                  # Activos estáticos (imágenes, fuentes, favicon)
├── src/
│   ├── components/          # Secciones reutilizables de la página
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Stats.astro
│   │   ├── Features.astro
│   │   ├── HowItWorks.astro
│   │   ├── Testimonials.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro     # Shell principal (head, meta, fuentes)
│   ├── pages/
│   │   └── index.astro      # Punto de entrada — compone todos los componentes
│   └── styles/
│       └── global.css       # Variables CSS del design system + reset
├── COLOR_PALETTE.md         # Documentación completa de la paleta de colores
├── astro.config.mjs
└── package.json
```

---

## 🧩 Secciones de la landing

| Componente     | Descripción                                                       |
| :------------- | :---------------------------------------------------------------- |
| `Header`       | Barra de navegación con links y CTA principal                     |
| `Hero`         | Sección principal con headline, descripción y llamada a la acción |
| `Stats`        | Métricas clave de la plataforma                                   |
| `Features`     | Características y funcionalidades del producto                    |
| `HowItWorks`   | Explicación paso a paso del flujo de uso                          |
| `Testimonials` | Reseñas y casos de éxito de usuarios                              |
| `Contact`      | Formulario de contacto o captura de leads                         |
| `Footer`       | Links, redes sociales e información legal                         |

---

## 🎨 Paleta de colores

El design system usa un tema **dark** con glassmorphism. Las variables principales son:

| Token            |                            Color                             | Hex       | Uso                          |
| :--------------- | :----------------------------------------------------------: | :-------- | :--------------------------- |
| `--brand-blue`   | ![#0f62fe](https://via.placeholder.com/14/0f62fe/0f62fe.png) | `#0f62fe` | CTAs, nav activo, gradientes |
| `--brand-cyan`   | ![#0ea5e9](https://via.placeholder.com/14/0ea5e9/0ea5e9.png) | `#0ea5e9` | Gradientes, focus, links     |
| `--brand-purple` | ![#818cf8](https://via.placeholder.com/14/818cf8/818cf8.png) | `#818cf8` | Badges, texto decorativo     |
| `--brand-green`  | ![#34d399](https://via.placeholder.com/14/34d399/34d399.png) | `#34d399` | Estado activo, éxito         |
| `--bg-base`      | ![#06091a](https://via.placeholder.com/14/06091a/06091a.png) | `#06091a` | Fondo raíz de la app         |
| `--text-primary` | ![#f1f5f9](https://via.placeholder.com/14/f1f5f9/f1f5f9.png) | `#f1f5f9` | Títulos y texto importante   |

> Ver [`COLOR_PALETTE.md`](./COLOR_PALETTE.md) para la documentación completa del design system.

---

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando          | Acción                                               |
| :--------------- | :--------------------------------------------------- |
| `pnpm install`   | Instala las dependencias                             |
| `pnpm dev`       | Inicia el servidor de desarrollo en `localhost:4321` |
| `pnpm build`     | Genera el sitio de producción en `./dist/`           |
| `pnpm preview`   | Previsualiza el build localmente antes de desplegar  |
| `pnpm astro ...` | Ejecuta comandos de la CLI de Astro                  |

---

## ⚙️ Requisitos

- **Node.js** `>= 22.12.0`
- **pnpm** `>= 9.x`

---

## 🤖 Generado con IA

> Documentación creada con **GitHub Copilot** usando el modelo **Claude Sonnet 4.6**.
