# Saga Económica — sitio

Repositorio del sitio, generado con Hugo. Borradores, fuentes y datos pesados viven
fuera de aquí (`01-escritos`, `02-fuentes`, `03-datos`); a este repo entra solo lo
que se publica. `public/` y `resources/` se regeneran y no se versionan.

Levantar en local: `hugo server -D` → `localhost:1313`.

## Plantillas propias

Hugo busca aquí antes que en cualquier tema. Desde el 22-oct-2026 el sitio no usa
tema: todo lo que se ve sale de esta carpeta y de `assets/css/saga.css`.

## Mapa

| Archivo | Qué pinta |
|---|---|
| `baseof.html` | esqueleto común: head, encabezado, pie |
| `home.html` | portada: lema, descripción del sitio, lo más reciente |
| `section.html` | listado de una sección (analisis, boletin, datos, video) |
| `page.html` | una pieza (artículo o página suelta como `acerca`) |
| `taxonomy.html` · `term.html` | índice de etiquetas · piezas de una etiqueta |
| `404.html` | página no encontrada |
| `_partials/head.html` | título, descripción, canonical, Open Graph, favicon, CSS |
| `_partials/encabezado.html` · `pie.html` | barra superior con menú · pie con redes |
| `_partials/tarjeta.html` | una entrada en cualquier listado |
| `_partials/rail.html` | columna lateral: ficha técnica, validación, datos abiertos |
| `_partials/firma.html` | firma de autor (solo si la pieza declara `autor`) |
| `_markup/render-image.html` | toda imagen del Markdown sale como figura con pie |
| `_shortcodes/franja.html` | franja lila dentro del texto |

## Contrato del front matter de una pieza

Obligatorios: `title`, `date`, `slug` (la URL; sin fecha), `summary` (aparece en
listados, en Open Graph y bajo el titular). Opcionales, y cada uno enciende algo:

```toml
resaltado = 'fragmento del titular'   # franja lila sobre ese fragmento
tema = 'Finanzas públicas'            # rótulo junto a la sección
tags = ['fiscal', 'gnc']              # etiquetas; se vuelven páginas en /tags/
datos = 'archivo.csv'                 # recurso del bundle → bloque "Datos abiertos"
imagen = 'portada.png'                # recurso del bundle → imagen de Open Graph
autor = 'clave'                       # → firma, buscada en data/autores.yaml
aliases = ['/ruta/vieja/']            # direcciones anteriores que siguen abriendo

[ficha]                               # → bloque "Ficha técnica"
fuente = '…'
deflactor = '…'
metodologia = '…'
cobertura = '…'

[validacion]                          # → bloque "Validación" (oscuro, dorado)
contra = '…'
cifra = '≤ 0,2 pp'
alcance = '…'
```

Sin `ficha`, `validacion`, `datos` ni `autor`, la pieza sale a una sola columna
(así se ve `acerca`). El enlace «Ver nota metodológica» del bloque de validación
apunta al encabezado `## Cómo se construyeron estas cifras`: si el artículo lo
llama distinto, cambiar el `href` en `rail.html`.

## En el texto

- `{{< franja >}}frase{{< /franja >}}` → franja lila.
- `![Pie de figura](grafico.svg)` → figura encuadrada; el alt es el pie.
- Los SVG de gráficos NO llevan `@media (prefers-color-scheme)`: cargados por
  `<img>` seguirían al sistema operativo del visitante, no a la página.

## Colores (de la guía 2024, con dos correcciones de contraste)

Texto pequeño en Lila `#7C3AED` sobre Noche Profunda falla WCAG AA (3,4:1): usar
Violeta `#9D5CF5` o Lavanda. Dorado `#E8C547` solo sobre Noche Profunda (11,6:1);
sobre lavanda es ilegible (1,4:1). Los tokens viven en `:root` de `saga.css`.
