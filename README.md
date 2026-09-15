# Practica Calificada 2 - Desarrollo de Aplicaciones Web

Proyecto de desarrollo web enfocado en la maquetacion responsive, componentes dinamicos y animaciones CSS utilizando HTML5 y Tailwind CSS.

---

## Equipo de Trabajo

- Lider de Proyecto: TOCAS ANGLAS ANGEL
- Integrante 2: RAMOS TACZA CAMILDA
- Integrante 3: OSORIO MALLQUI JOSE
- Integrante 4: VALENCIA BERNAOLA ANDRES

---

## Backlog de Historias de Usuario

| ID   | Historia de Usuario                                                                           | Archivo     | Estado     |
| ---- | --------------------------------------------------------------------------------------------- | ----------- | ---------- |
| HU01 | Como usuario quiero ver una bandeja de mensajes estilo A para revisar mis correos rapidamente | page01.html | Completado |
| HU02 | Como usuario quiero ver una bandeja de mensajes estilo B con hora y favoritos                 | page01.html | Completado |
| HU03 | Como usuario quiero explorar las 10 playas mas importantes del Peru en tarjetas               | page02.html | Completado |
| HU04 | Como usuario quiero ver el clima de las 10 ciudades mas importantes del Peru                  | page02.html | Completado |
| HU05 | Como usuario quiero navegar una tienda de plantas con productos recien llegados               | page03.html | Completado |
| HU06 | Como usuario quiero una pagina principal con accesos animados a las demas paginas             | index.html  | Completado |

---

## Detalle de Implementacion por Pagina

### index.html

- Menu principal compuesto por 3 tarjetas animadas que dirigen a page01.html, page02.html y page03.html.
- Efecto hover con rotacion en 3D (180 grados combinando ejes horizontal y vertical).
- Orientacion de texto corregida en la cara posterior para lectura clara al girar.

### page01.html

- Layout en Grid estructurado en 1 fila y 2 columnas.
- Columna izquierda: Lista de bandeja de entrada estilo Material Design (encabezado teal, avatares y texto resaltado).
- Columna derecha: Lista de bandeja de entrada con marcas de tiempo, estados y seleccionables.
- Adaptabilidad responsiva:
  - Pantallas menores a 700px: 100% de ancho.
  - Pantallas entre 701px y 1399px: 50% de ancho.
  - Pantallas mayores a 1400px: 60% de ancho.

### page02.html

- Layout en Grid compuesto por 1 fila y 2 columnas.
- Columna A: 10 tarjetas de playas del Peru (dimensiones de imagen 200px x 120px) distribuidas en Flexbox con espacio de 10px y estados hover en botones de accion (SHARE / EXPLORE).
- Columna B: 10 tarjetas de reporte de clima para ciudades del Peru (dimensiones 250px x 200px) distribuidas en Flexbox con espacio de 5px y estado hover en boton FULL REPORT.

### page03.html

- Maquetacion de tienda virtual con barra superior de anuncios, cabecera de navegacion, banner principal y catalogo "Recien llegados".
- Efecto hover con transicion de opacidad (+15%) en las imagenes de producto.
- Comportamiento responsivo adaptable via Flexbox:
  - Menor a 480px: 1 columna.
  - Menor a 900px: 2 columnas.
  - Menor a 1200px: 3 columnas.
  - Mayor a 1200px: 4 columnas.
- Pie de pagina estructurado en 5 columnas informativas.

---

## Tecnologias Utilizadas

- HTML5
- Tailwind CSS
- CSS Custom (Media Queries y transformaciones 3D)
- Git / GitHub
