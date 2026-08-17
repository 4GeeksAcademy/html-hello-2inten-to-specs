ROL
Eres un Senior Frontend Developer

STACK
La landing debe desarrollarse utilizando exclusivamente:

HTML5 para la estructura.

Tailwind CSS mediante CDN para todos los estilos.

RESTRICCIONES
Sin React.

Sin Vue.

Sin Angular.

Sin otros frameworks.

Sin backend.

Sin base de datos.

Sin sistema de autenticación.

Los contenidos pueden ser estáticos y estar escritos directamente en HTML.

La primera versión debe centrarse en la estructura y diseño visual de la landing.

No es necesario implementar funcionalidades complejas mediante JavaScript en esta fase.

La página debe seguir un enfoque mobile-first, utilizando primero una composición optimizada para pantallas pequeñas y adaptándola posteriormente a tablet y escritorio.

CONTENIDO
1. Estructura general**
La landing debe estar formada por las siguientes secciones:

1. Header / navegación.
2. Hero.
3. Selected Work / Portfolio.
4. Services.
5. Process.
6. Call to Action.
7. Footer.

La navegación debe permitir identificar claramente estas áreas y el contenido debe fluir verticalmente como una única landing page.

2. Header / navegación**
El Header debe aparecer en la parte superior de la página y servir como elemento de navegación principal.

### Especificaciones

1. El lado izquierdo debe contener el nombre o logotipo textual de la empresa.

2. En escritorio debe mostrar enlaces a las principales secciones: `Work`, `Services`, `Process` y `Contact`.

3. El extremo derecho debe contener un botón CTA destacado con el texto `Let's Talk`.

4. En dispositivos móviles la navegación horizontal debe simplificarse para evitar ocupar demasiado espacio, mostrando únicamente el logotipo y un botón de menú.

5. El Header debe utilizar el mismo lenguaje visual que el Hero, utilizando fondo oscuro, tipografía clara y bordes sutiles.

6. El Header debe tener suficiente espacio interior para no dar una sensación de interfaz comprimida.

3. Hero**
El Hero debe ser la primera gran sección de la página y debe ocupar **toda la pantalla inicial**.

La composición debe transmitir inmediatamente que se trata de una empresa especializada en tecnología y productos digitales.

### Especificaciones

1. El Hero debe tener una altura mínima equivalente a `100vh`, de manera que ocupe toda la pantalla disponible al cargar la página.

2. Debe contener un titular principal de gran tamaño relacionado con la creación de productos digitales, por ejemplo `We build digital futures` o un mensaje equivalente.

3. Debajo del titular debe aparecer una descripción breve explicando que la empresa ayuda a sus clientes a diseñar, desarrollar y transformar productos digitales.

4. Debe existir un CTA principal `Start a project` visualmente destacado mediante el color de acento principal.

5. Debe existir un elemento visual tecnológico situado junto al contenido textual. Este elemento puede ser un gran mockup de una interfaz web, una composición de varias pantallas o una composición abstracta basada en elementos digitales.

6. En escritorio, el Hero debe poder utilizar una composición de dos zonas: contenido textual a un lado y elemento visual al otro.

7. En móvil, el contenido debe reorganizarse verticalmente, colocando primero el mensaje principal y posteriormente el elemento visual.

8. En la parte inferior del Hero debe existir un pequeño indicador `Scroll to explore` acompañado de una flecha o indicador visual descendente.

9. El fondo debe utilizar un color oscuro con halos o gradientes muy sutiles en cyan, azul y violeta para crear profundidad.

10. El título debe utilizar una tipografía de gran tamaño, alto contraste y peso elevado para convertirse en el principal punto focal de la página.

4. Selected Work / Portfolio**
Después del Hero debe aparecer una sección dedicada a mostrar una selección de proyectos realizados por la empresa.

Esta sección debe ser una de las partes visualmente más importantes de la landing.

### Especificaciones

1. La sección debe comenzar con un título `Selected Work` y una descripción breve indicando que se trata de una selección de productos digitales desarrollados por la empresa.

2. Debe existir una **grid de exactamente 16 proyectos**.

3. En escritorio la grid debe utilizar **4 columnas y 4 filas**, creando una composición 4×4.

4. En tablet la grid debe adaptarse a **2 columnas**.

5. En móvil la grid debe adaptarse a **1 columna**.

6. Cada uno de los 16 elementos debe contener un **mockup de una página web o producto digital**.

7. Los mockups deben representar diferentes tipos de productos, por ejemplo:

* Dashboard empresarial.
* SaaS.
* E-commerce.
* Plataforma de analytics.
* Aplicación financiera.
* Plataforma de gestión.
* Página corporativa.
* Aplicación de reservas.
* Herramienta de productividad.
* Plataforma de datos.

8. Los mockups no deben ser visualmente idénticos. Deben utilizar diferentes composiciones de tarjetas, gráficos, tablas, menús, imágenes y bloques de contenido.

9. Cada proyecto debe incluir información mínima como nombre del proyecto y categoría.

10. Los mockups deben conservar proporciones correctas al cambiar el tamaño de pantalla y no deben deformarse.

11. La distancia entre las diferentes tarjetas de la grid debe ser uniforme.

12. Algunos proyectos pueden tener mayor presencia visual mediante tarjetas que ocupen más espacio, siempre que la composición siga siendo responsive y coherente.

13. Los proyectos deben utilizar diferentes combinaciones de los colores de la paleta futurista sin romper la identidad general de la página.

5. Services**
La sección Services debe explicar las principales áreas de especialización de la empresa.

### Especificaciones

1. Debe contener un título `Services` y una descripción breve de la propuesta de valor.

2. Debe presentar al menos cuatro servicios principales:

* `Product Strategy`
* `UX/UI Design`
* `Web Development`
* `Technology Consulting`

3. Cada servicio debe representarse visualmente mediante una tarjeta que contenga un icono o elemento gráfico, título y descripción breve.

4. Las tarjetas deben organizarse en una columna en móvil, dos columnas en tablet y varias columnas en escritorio.

5. Cada servicio debe utilizar un pequeño detalle de color de acento para diferenciarlo visualmente.

6. Las tarjetas deben mantener un diseño coherente con los mockups del Portfolio, utilizando fondos oscuros, bordes sutiles y esquinas redondeadas.

6. Process**
La sección Process debe explicar visualmente la metodología de trabajo de la empresa.

### Especificaciones

1. Debe contener un título `How we work` y una descripción breve del proceso.

2. Deben existir exactamente cuatro etapas:

* `01 — Discover`
* `02 — Plan`
* `03 — Build`
* `04 — Launch`

3. Cada etapa debe mostrar un número destacado, título y descripción breve.

4. Las cuatro etapas deben estar conectadas visualmente mediante una línea, separación o elemento gráfico que transmita progresión.

5. En escritorio las etapas deben mostrarse horizontalmente.

6. En móvil deben reorganizarse verticalmente.

7. Cada etapa debe utilizar un pequeño detalle de color de la paleta futurista.

7. Call to Action**
La sección CTA debe funcionar como cierre comercial de la landing antes del Footer.

### Especificaciones

1. Debe contener un titular grande como `Have a project in mind?`.

2. Debe incluir una descripción indicando que la empresa está disponible para analizar nuevos proyectos, productos o necesidades tecnológicas.

3. Debe existir un botón principal `Start a conversation`.

4. El CTA debe tener un diseño visual diferente al resto de las secciones para crear un punto focal al final de la página.

5. El fondo puede utilizar un gradiente sutil entre `Electric Cyan`, `Electric Blue` y `Neon Violet`, manteniendo una intensidad baja para no comprometer la legibilidad.

8. Footer**
El Footer debe cerrar la página proporcionando navegación e información básica de contacto.

### Especificaciones

1. Debe mostrar el nombre o logotipo de la empresa.

2. Debe incluir enlaces a `Work`, `Services`, `Process` y `Contact`.

3. Debe mostrar un email de contacto.

4. Debe incluir enlaces secundarios como `LinkedIn`, `Privacy` y `Terms`.

5. En móvil todos los elementos deben reorganizarse verticalmente.

9. Paleta de colores futurista**
La identidad visual debe utilizar una estética tecnológica y futurista basada principalmente en fondos oscuros y colores de acento luminosos.

La intención es conseguir una estética de **consultora tecnológica premium**, evitando que el diseño parezca una interfaz de videojuego.

## Colores principales

| Nombre | Hexadecimal | Uso |
| ------------- | ----------- | -------------------------- |
| Void Black | `#080A0F` | Fondo principal |
| Deep Space | `#0D111A` | Fondos secundarios |
| Surface | `#151A24` | Tarjetas y superficies |
| Surface Light | `#1D2430` | Elementos elevados |
| Electric Cyan | `#00E5FF` | CTA y elementos destacados |
| Electric Blue | `#3B82F6` | Acentos tecnológicos |
| Neon Violet | `#8B5CF6` | Acentos secundarios |
| Neon Green | `#39FF88` | Estados positivos |
| Soft White | `#F4F7FB` | Títulos y texto principal |
| Muted Gray | `#94A3B8` | Texto secundario |
| Border | `#263041` | Bordes y separadores |

## Uso de colores

1. El fondo general de la página debe utilizar `Void Black`.

2. Las secciones secundarias pueden alternar entre `Void Black` y `Deep Space` para crear separación visual.

3. Los títulos principales deben utilizar `Soft White`.

4. Los textos secundarios deben utilizar `Muted Gray`.

5. El CTA principal debe utilizar `Electric Cyan`.

6. `Neon Violet` debe utilizarse principalmente como segundo color de acento.

7. `Electric Blue` puede utilizarse en gráficos, mockups y elementos tecnológicos.

8. `Neon Green` debe reservarse principalmente para indicadores de éxito o métricas positivas.

9. Los bordes deben utilizar `Border` y mantenerse visualmente discretos.

10. Los colores brillantes no deben utilizarse como grandes superficies de fondo.

10. Gradientes y efectos visuales**
La estética futurista debe reforzarse mediante gradientes y efectos luminosos utilizados de manera moderada.

### Especificaciones

1. El Hero puede utilizar un gradiente ambiental entre `Electric Cyan`, `Electric Blue` y `Neon Violet` sobre el fondo oscuro.

2. Los elementos luminosos deben aparecer como halos o manchas difusas y no como grandes áreas de color sólido.

3. Los botones principales pueden utilizar un pequeño efecto de glow alrededor del color cyan.

4. Las tarjetas pueden utilizar bordes ligeramente iluminados en determinados elementos destacados.

5. Los efectos visuales deben ser sutiles y no dificultar la lectura.

6. La mayor parte de la superficie de la página debe permanecer oscura y neutra, utilizando los colores neon únicamente como acentos.

11. Responsive / Mobile First**
La página debe diseñarse siguiendo un enfoque **mobile-first**.

## Mobile

En pantallas pequeñas:

* El contenido debe utilizar una sola columna.
* La navegación debe simplificarse.
* El Hero debe organizarse verticalmente.
* La grid de Portfolio debe utilizar una columna.
* Los servicios deben utilizar una columna.
* El Process debe utilizar una disposición vertical.
* Los botones deben tener un tamaño adecuado para interacción táctil.
* Los mockups deben ocupar el ancho disponible sin desbordarse.
* El texto del Hero debe reducirse progresivamente para mantener una composición equilibrada.

## Tablet

En tamaños intermedios:

* La grid de Portfolio debe utilizar dos columnas.
* Los servicios pueden utilizar dos columnas.
* El Hero puede utilizar una composición más horizontal.
* El Process puede comenzar a utilizar una distribución horizontal.

## Desktop

En escritorio:

* El Header debe mostrar toda la navegación.
* El Hero debe ocupar al menos `100vh`.
* El Hero puede utilizar una composición de dos columnas.
* Portfolio debe utilizar exactamente cuatro columnas.
* Los 16 proyectos deben formar una composición 4×4.
* Services debe utilizar varias columnas.
* Process debe utilizar una composición horizontal.
* Debe aprovecharse el espacio disponible sin hacer que los contenidos tengan una anchura excesiva.

12. Espaciado y composición**
Toda la página debe mantener un sistema de espaciado consistente.

### Especificaciones

1. Cada sección debe tener suficiente espacio vertical para distinguirse claramente de la siguiente.

2. Los títulos de sección deben tener una jerarquía visual consistente.

3. Las tarjetas deben mantener el mismo sistema de padding y border-radius.

4. La grid debe utilizar espacios uniformes entre elementos.

5. El contenido principal debe utilizar un ancho máximo para evitar líneas de texto excesivamente largas en pantallas grandes.

6. Los elementos visuales deben tener suficiente espacio alrededor para evitar una apariencia saturada.

13. Criterios de aceptación**
1. La landing contiene Header, Hero, Selected Work, Services, Process, Call to Action y Footer.

2. El Hero ocupa al menos el 100% de la altura de la pantalla.

3. El Hero contiene título principal, descripción, CTA y elemento visual tecnológico.

4. Después del Hero aparece directamente la sección Selected Work.

5. Selected Work contiene exactamente 16 proyectos.

6. Los 16 proyectos contienen mockups visuales de páginas web o productos digitales.

7. En escritorio los proyectos aparecen en una grid de 4×4.

8. En tablet los proyectos aparecen en dos columnas.

9. En móvil los proyectos aparecen en una columna.

10. La grid nunca genera scroll horizontal.

11. Services contiene al menos cuatro servicios.

12. Process contiene las cuatro etapas `Discover`, `Plan`, `Build` y `Launch`.

13. Existe una sección CTA antes del Footer.

14. La página utiliza la paleta futurista definida en este documento.

15. Los colores neon se utilizan como acentos y no dominan toda la interfaz.

16. La interfaz está diseñada siguiendo un enfoque mobile-first.

17. La interfaz es responsive en móvil, tablet y escritorio.

18. Todos los estilos se implementan utilizando Tailwind CSS mediante CDN.

19. La estructura está implementada exclusivamente mediante HTML.

20. No es necesario disponer de backend ni base de datos.

21. Los proyectos, textos, estadísticas y demás contenidos pueden utilizar información estática de ejemplo.

22. La página mantiene una identidad visual consistente entre Hero, mockups, tarjetas, servicios, CTA y Footer.

23. Los mockups de Portfolio presentan suficiente variedad visual para que la grid no parezca formada por 16 copias del mismo diseño.

24. La landing transmite una imagen de empresa tecnológica profesional, moderna y orientada a productos digitales.