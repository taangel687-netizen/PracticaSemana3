# PracticaSemana3

Práctica Calificada 2 — Desarrollo de Aplicaciones Web
Equipo
Líder: TOCAS ANGLAS ANGEL
Integrante 2: RAMOS TACZA CAMILDA
Integrante 3: OSORIO MALLQUI JOSE
Integrante 4: VALENCIA BERNAOLA ANDRÉS

Backlog utilizado

# Historia de usuario Página Estado

1 Como usuario quiero ver una bandeja de mensajes estilo A para revisar mis correos rápidamente page01.html (lista a) Hecho
2 Como usuario quiero ver una bandeja de mensajes estilo B con hora y favoritos page01.html (lista b) Hecho
3 Como usuario quiero explorar las 10 playas más importantes del Perú en tarjetas page02.html (cards a) Hecho
4 Como usuario quiero ver el clima de las 10 ciudades más importantes del Perú page02.html (cards b) Hecho
5 Como usuario quiero navegar una tienda de plantas con productos recién llegados page03.html Hecho
6 Como usuario quiero una página principal con accesos animados a las demás páginas index.html Hecho
Funcionalidades por página
index.html
3 cards animados que enlazan a `page01.html`, `page02.html` y `page03.html`.
Animación de giro 180° combinando eje horizontal y vertical al pasar el mouse (`rotate3d(1,1,0,180deg)`).
page01.html
Grid de 2 columnas / 1 fila.
Columna A: lista de inbox estilo Material (header teal, avatares, asunto en negrita).
Columna B: lista de inbox con hora, estrella de favorito y check de seleccionado.
Responsivo: 100% de ancho `<700px`, 50% entre `701px-1399px`, 60% `>1400px`.
page02.html
Grid de 1 fila / 2 columnas.
Columna A: 10 cards de playas del Perú (200x120 imagen), flexbox con separación de 10px, hover gris en botones SHARE/EXPLORE.
Columna B: 10 cards de ciudades del Perú tipo "reporte del clima" (250x200), flexbox con separación de 5px, hover gris en botón FULL REPORT.
page03.html
Tienda de plantas: barra de promoción, nav, hero "Plantas", sección "Recién llegados" con 4 productos.
Hover en imágenes reduce opacidad (efecto +15%).
Responsivo con flexbox + media queries: pequeño `<480px` (1 columna), mediano `<900px` (2 columnas), grande `<1200px` (3 columnas), extra `>1200px` (4 columnas).
Footer con 5 columnas de información.
Tecnologías
HTML5
Tailwind CSS (CDN)
CSS personalizado para media queries específicas y animaciones 3D
