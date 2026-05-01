# Gama de Colores — HABITARED Design System

> Análisis completo de la paleta de colores usada en el proyecto, extraída de `styles.css` y los componentes CSS.

---

## 1. Colores de Marca (Brand Colors)

Estos son los colores de identidad del producto. Definen la personalidad visual y aparecen en botones principales, gradientes, logos, íconos activos y CTAs.

| Variable CSS         | Hex       | Color                                                                 | Uso                                       | Importancia   | % Aprox. |
|----------------------|-----------|-----------------------------------------------------------------------|-------------------------------------------|---------------|-----------|
| `--brand-blue`       | `#0f62fe` | ![#0f62fe](https://via.placeholder.com/14/0f62fe/0f62fe.png) Azul    | CTAs primarios, nav activo, gradientes    | ⭐⭐⭐⭐⭐ Crítico | ~22 %     |
| `--brand-cyan`       | `#0ea5e9` | ![#0ea5e9](https://via.placeholder.com/14/0ea5e9/0ea5e9.png) Cian    | Gradientes, spinner, focus, links         | ⭐⭐⭐⭐⭐ Crítico | ~18 %     |
| `--brand-purple`     | `#818cf8` | ![#818cf8](https://via.placeholder.com/14/818cf8/818cf8.png) Violeta | Badge "residente", texto decorativo       | ⭐⭐⭐ Medio    | ~4 %      |
| `--brand-green`      | `#34d399` | ![#34d399](https://via.placeholder.com/14/34d399/34d399.png) Verde   | Badges activos, ícono de visitas, éxito   | ⭐⭐⭐⭐ Alto    | ~8 %      |
| `--brand-red`        | `#f87171` | ![#f87171](https://via.placeholder.com/14/f87171/f87171.png) Rojo    | Errores, badges inactivos, danger         | ⭐⭐⭐⭐ Alto    | ~6 %      |
| `--brand-amber`      | `#fbbf24` | ![#fbbf24](https://via.placeholder.com/14/fbbf24/fbbf24.png) Ámbar  | Badges de advertencia, badge "manager"    | ⭐⭐⭐ Medio    | ~4 %      |

---

## 2. Fondos (Background Scale)

La escala de fondos oscuros construye la profundidad visual del dashboard con capas superpuestas.

| Variable CSS         | Hex / RGBA              | Uso                                          | Importancia     | % Aprox. |
|----------------------|-------------------------|----------------------------------------------|-----------------|-----------|
| `--bg-base`          | `#06091a`               | Fondo raíz de toda la app y landing          | ⭐⭐⭐⭐⭐ Crítico  | ~10 %     |
| `--bg-layer1`        | `#0a0f2e`               | Segunda capa (features, pricing)             | ⭐⭐⭐⭐ Alto      | ~3 %      |
| `--bg-layer2`        | `#0f1535`               | Opciones de `<select>`, dropdown fondo       | ⭐⭐⭐ Medio      | ~2 %      |
| `--bg-surface`       | `#111827`               | Superficie de componentes de tabla/formulario| ⭐⭐⭐ Medio      | ~2 %      |
| `--bg-card`          | `rgba(15,23,42, 0.80)`  | Fondo de tarjetas con transparencia          | ⭐⭐⭐⭐ Alto      | ~3 %      |
| `--bg-card-hover`    | `rgba(15,23,42, 0.95)`  | Hover de tarjetas                            | ⭐⭐ Bajo         | ~1 %      |

---

## 3. Glass / Glassmorphism

Usados para la textura de cristal opaco que cubre el sidebar, tarjetas y modales.

| Variable CSS       | RGBA                        | Uso                                        | Importancia   | % Aprox. |
|--------------------|-----------------------------|--------------------------------------------|---------------|-----------|
| `--glass-bg`       | `rgba(15,23,42, 0.70)`      | Fondo de cards, auth-card, sidebar         | ⭐⭐⭐⭐⭐ Crítico | ~5 %      |
| `--glass-border`   | `rgba(99,179,237, 0.15)`    | Borde de elementos glass                   | ⭐⭐⭐⭐ Alto    | ~3 %      |

---

## 4. Textos (Text Colors)

Escala de grises para mantener jerarquía tipográfica sobre fondos oscuros.

| Variable CSS         | Hex       | Uso                                               | Importancia   | % Aprox. |
|----------------------|-----------|---------------------------------------------------|---------------|-----------|
| `--text-primary`     | `#f1f5f9` | Títulos, valores importantes, texto activo        | ⭐⭐⭐⭐⭐ Crítico | ~5 %      |
| `--text-secondary`   | `#94a3b8` | Texto de cuerpo, celdas de tabla, nav inactivo    | ⭐⭐⭐⭐⭐ Crítico | ~5 %      |
| `--text-muted`       | `#475569` | Subtítulos, placeholders, timestamps, etiquetas  | ⭐⭐⭐⭐ Alto    | ~4 %      |
| `--text-link`        | `#60a5fa` | Links, íconos de acciones, info                   | ⭐⭐⭐ Medio    | ~2 %      |
| `#e2e8f0` (landing)  | `#e2e8f0` | Texto base en la landing page                     | ⭐⭐⭐ Medio    | ~2 %      |
| `#64748b` (landing)  | `#64748b` | Texto secundario muted en landing                 | ⭐⭐⭐ Medio    | ~2 %      |
| `#fff`               | `#ffffff` | Texto sobre botones con gradiente / logos         | ⭐⭐⭐⭐ Alto    | ~2 %      |

---

## 5. Bordes (Border Colors)

Todos basados en el tono `rgba(99,179,237, ...)` (cian-azul suave) con distinta opacidad.

| Variable CSS         | RGBA                        | Uso                                      | Importancia  | % Aprox. |
|----------------------|-----------------------------|------------------------------------------|--------------|-----------|
| `--border-dim`       | `rgba(99,179,237, 0.08)`    | Divisores, bordes de tabla y nav footer  | ⭐⭐⭐⭐ Alto   | ~3 %      |
| `--border-base`      | `rgba(99,179,237, 0.15)`    | Bordes normales de inputs y cards        | ⭐⭐⭐⭐ Alto   | ~3 %      |
| `--border-bright`    | `rgba(99,179,237, 0.35)`    | Hover y focus de elementos interactivos  | ⭐⭐⭐ Medio   | ~2 %      |

---

## 6. Sombras y Brillos (Shadows & Glows)

| Variable CSS    | Valor                            | Uso                                        | Importancia  |
|-----------------|----------------------------------|--------------------------------------------|--------------|
| `--shadow-sm`   | `0 2px 8px rgba(0,0,0, 0.30)`   | Cards pequeñas                             | ⭐⭐⭐ Medio   |
| `--shadow-md`   | `0 8px 32px rgba(0,0,0, 0.40)`  | Cards en hover                             | ⭐⭐⭐ Medio   |
| `--shadow-lg`   | `0 24px 64px rgba(0,0,0, 0.50)` | Modales, auth-card                         | ⭐⭐⭐⭐ Alto   |
| `--glow-blue`   | `0 0 24px rgba(15,98,254, 0.40)`| Brillo del botón primario y logo           | ⭐⭐⭐⭐ Alto   |
| `--glow-cyan`   | `0 0 24px rgba(14,165,233, 0.30)`| Brillo del spinner y accents              | ⭐⭐⭐ Medio   |

---

## 7. Estados (Status Colors)

Mapean directamente sobre los colores de marca. Se usan en badges, alertas y chips.

| Variable CSS  | Hex       | Estado     | Contexto de uso                              |
|---------------|-----------|------------|----------------------------------------------|
| `--success`   | `#34d399` | Activo ✔   | Badge activo, icono check, tendencias         |
| `--warning`   | `#fbbf24` | Pendiente ⚠| Badge pendiente, badge manager               |
| `--danger`    | `#f87171` | Error ✖    | Alerts, badge inactivo, btn-danger, logout   |
| `--info`      | `#60a5fa` | Info ℹ    | Iconos de acción, badge-admin, links         |

---

## 8. Colores de Acento / Decorativos

Usados puntualmente en orbes de fondo, mockups de la landing y detalles visuales.

| Color            | Hex / RGBA                   | Dónde aparece                                 | Importancia  |
|------------------|------------------------------|-----------------------------------------------|--------------|
| Azul cian home   | `#00bcd4`                    | Logo-mark en landing (sidebar mockup)         | ⭐⭐ Bajo      |
| Cian brillante   | `#22d3ee`                    | Stat-value cyan del mockup                    | ⭐⭐ Bajo      |
| Violeta suave    | `#a78bfa`                    | Stat-value purple del mockup                  | ⭐⭐ Bajo      |
| Azul claro hero  | `#7dd3fc`                    | Texto del hero-badge                          | ⭐⭐ Bajo      |
| Violeta orb      | `rgba(139,92,246, 0.15)`     | Orbe decorativo hero y CTA section            | ⭐⭐ Bajo      |
| Rojo macOS       | `#ff5f56`                    | Punto rojo del mockup de navegador            | ⭐ Decorativo |
| Amarillo macOS   | `#ffbd2e`                    | Punto amarillo del mockup de navegador        | ⭐ Decorativo |
| Verde macOS      | `#27c93f`                    | Punto verde del mockup de navegador           | ⭐ Decorativo |

---

## Resumen Porcentual de Uso

```
Azul marca  (#0f62fe / --brand-blue)   ████████████████████  ~22%
Cian marca  (#0ea5e9 / --brand-cyan)   ████████████████      ~18%
Fondos base (#06091a … rgba(15,23,42)) ██████████            ~11%
Textos      (#f1f5f9, #94a3b8, #fff)   ████████              ~9%
Glass/Glass-border                     ██████                ~8%
Verde       (#34d399)                  ██████                ~8%
Rojo        (#f87171)                  █████                 ~6%
Bordes cian (rgba(99,179,237,...))     █████                 ~6%
Violeta     (#818cf8)                  ███                   ~4%
Ámbar       (#fbbf24)                  ███                   ~4%
Resto / decorativo                     ██                    ~4%
```

---

## Notas de Diseño

- **Dark-mode nativo**: toda la app usa fondos `#06091a → #0f1535` sin alternativa de tema claro.
- **Gradiente principal**: `linear-gradient(135deg, #0f62fe, #0ea5e9)` es el elemento de identidad más recurrente (logo, CTA, avatares, step-numbers).
- **Glassmorphism**: `rgba(15,23,42, 0.7)` + `backdrop-filter: blur(16px)` es el patrón de superficie dominante en cards y sidebar.
- **Coherencia de bordes**: todos los bordes usan el mismo tono cian `rgb(99,179,237)` variando sólo la opacidad (0.08 / 0.15 / 0.35) para crear jerarquía sin cambiar matiz.
- **Estado de peligro doble**: `--danger` (`#f87171`) se usa tanto para errores de formulario como para la acción de logout, lo que refuerza la lectura semántica del color.
