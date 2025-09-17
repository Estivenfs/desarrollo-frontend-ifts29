# Equipo Innovador - Sitio Web del Equipo 9

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de un sitio web responsivo y moderno para presentar a nuestro equipo de trabajo "Equipo Innovador". El sitio web incluye una página principal con información del equipo, páginas individuales para cada uno de los 5 integrantes con sus perfiles personales completos, y una sección de bitácora que documenta todo el proceso de desarrollo.

El objetivo principal es crear una plataforma digital que permita conocer a cada miembro del equipo, sus habilidades, intereses, experiencia, películas favoritas y gustos musicales, mientras se demuestra el dominio de tecnologías web modernas y buenas prácticas de desarrollo.

## Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos personalizados con variables, flexbox y grid
- **JavaScript ES6+**: Interactividad y funcionalidades dinámicas
- **Bootstrap 5.3.0**: Framework CSS para diseño responsivo y componentes
- **Bootstrap Icons**: Iconografía moderna y consistente

### Tipografías y Recursos
- **Google Fonts**: Poppins y Roboto para mejorar la estética y legibilidad
- **SVG**: Gráficos vectoriales para avatares y logo del equipo
- **CSS Variables**: Para mantener consistencia en colores y estilos
- **LocalStorage**: Persistencia de preferencias del usuario (tema)

### Herramientas de Desarrollo
- **Media Queries**: Diseño responsivo con breakpoints específicos
- **Flexbox y CSS Grid**: Layouts modernos y flexibles
- **Intersection Observer API**: Animaciones basadas en scroll
- **CSS Transitions y Animations**: Efectos visuales suaves

## Estructura del Proyecto

```
Presentacion/
├── index.html              # Página principal del equipo
├── lucas.html              # Perfil individual de Lucas
├── victoria.html           # Perfil individual de Victoria
├── sebastian.html          # Perfil individual de Sebastián
├── jose.html               # Perfil individual de José
├── estiven.html            # Perfil individual de Estiven
├── bitacora.html          # Documentación del proceso de desarrollo
├── README.md              # Documentación del proyecto
├── css/
│   ├── styles.css         # Estilos personalizados del sitio
│   ├── estiven.css        # Estilos específicos de Estiven
│   ├── jose.css           # Estilos específicos de José
│   ├── lucas.css          # Estilos específicos de Lucas
│   └── victoria.css       # Estilos específicos de Victoria
├── js/
│   ├── main.js            # JavaScript principal con todas las funcionalidades
│   ├── estiven.js         # JavaScript específico de Estiven
│   ├── lucas.js           # JavaScript específico de Lucas
│   └── wolverine.js       # JavaScript para funcionalidades de Wolverine
├── video/                  # Videos de fondo y multimedia
│   ├── hero-bg.mp4             # Video de fondo para la sección hero
│   └── logan fondo.mp4         # Video de fondo para la página de Logan
└── img/
    ├── bitacora-favicon.png       # Favicon de bitácora
    ├── bitacora.jpg               # Imagen para bitácora
    ├── ed_foto.png                # Foto de Ed
    ├── est-avatar.png             # Avatar de Estiven
    ├── est-ghost-song.jpg         # Canción Ghost de Estiven
    ├── est-hall_of_fame-song.jpg  # Canción Hall of Fame de Estiven
    ├── est-heartstopper-movie.jpg # Serie Heartstopper de Estiven
    ├── est-magi-movie.jpg         # Película Magi de Estiven
    ├── est-sense8-movie.jpg       # Serie Sense8 de Estiven
    ├── est-shelter-movie.png      # Película Shelter de Estiven
    ├── est-thameypo-movie.webp    # Serie Thame y Po de Estiven
    ├── est-the_nights-song.jpg    # Canción The Nights de Estiven
    ├── est-you_are_the_reason-song.jpg # Canción You Are The Reason de Estiven
    ├── favicon.png                # Favicon principal
    ├── fondo-index.png            # Fondo de la página principal
    ├── jose-favicon.png           # Favicon de José
    ├── jose.png                   # Imagen de José
    ├── juego1.png                 # Imagen de juego 1
    ├── juego2.png                 # Imagen de juego 2
    ├── juego3.png                 # Imagen de juego 3
    ├── juego4.png                 # Imagen de juego 4
    ├── logan.png                  # Imagen de Logan
    ├── logan2.jpeg                # Imagen de Logan 2
    ├── logan3.jpeg                # Imagen de Logan 3
    ├── logan4.jpeg                # Imagen de Logan 4
    ├── logo.png                   # Logo del equipo (PNG)
    ├── logo.svg                   # Logo del equipo (SVG)
    ├── lucas_background.png       # Fondo de Lucas
    ├── lucas_icn.ico              # Icono de Lucas
    ├── lucas_perfil.png           # Perfil de Lucas
    ├── pelis_foto.png             # Imagen de películas
    ├── sebas-numb.jpg             # Canción Numb de Sebastián
    ├── sebastian-Como_Hackear_seu_Chefe3.jpg # Película Como Hackear seu Chefe de Sebastián
    ├── sebastian-ajeoosi2.jpg     # Película Ajeoosi de Sebastián
    ├── sebastian-creep.jpg        # Canción Creep de Sebastián
    ├── sebastian-dontcry.jpg      # Canción Don't Cry de Sebastián
    ├── sebastian-perfil.webp      # Perfil de Sebastián
    ├── sebastian-redes.jpg        # Película Redes de Sebastián
    ├── sebastian-scorpion1.jpg    # Película Scorpion de Sebastián
    ├── sebastian-terminator2.jpg  # Película Terminator de Sebastián
    ├── sebastian-thebigshort1.jpg # Película The Big Short de Sebastián
    ├── vic-melodrama.jpg          # Álbum Melodrama de Victoria
    ├── vic-orgullo.webp           # Álbum Orgullo de Victoria
    ├── vic-oyster.jpg             # Álbum Oyster de Victoria
    ├── vic-renglones.jpg          # Álbum Renglones de Victoria
    ├── vic-speaknow.jpg           # Álbum Speak Now de Victoria
    ├── vic-virgin.jpeg            # Álbum Virgin de Victoria
    ├── victoria-deboot.png        # Imagen Deboot de Victoria
    ├── victoria-favicon.png       # Favicon de Victoria
    ├── victoria-fondo.webp        # Fondo de Victoria
    ├── victoria-hometown.jpg      # Hometown de Victoria
    ├── victoria-hyped.png         # Imagen Hyped de Victoria
    ├── victoria-ind.png           # Imagen Ind de Victoria
    ├── victoria-interact.png      # Imagen Interact de Victoria
    └── victoria-korean.jpg        # Imagen Korean de Victoria
```

## Estructura de Archivos

La organización del proyecto sigue las mejores prácticas de desarrollo web:

### Archivos HTML
- **Ubicación**: Directorio raíz del proyecto
- **Propósito**: Todas las páginas HTML están en la raíz para facilitar la navegación y el acceso directo
- **Archivos**: `index.html` (página principal), páginas individuales de cada integrante, y `bitacora.html`

### Carpeta CSS (`css/`)
- **Contenido**: Archivo `styles.css` con todos los estilos personalizados
- **Organización**: Estilos organizados por secciones (variables, componentes, responsive, tema oscuro)
- **Integración**: Bootstrap importado via CDN, Google Fonts integradas

### Carpeta JavaScript (`js/`)
- **Contenido**: Archivo `main.js` con todas las funcionalidades interactivas
- **Estructura**: Funciones globales, específicas por página, y utilidades compartidas
- **Compatibilidad**: JavaScript ES6+ con fallbacks para navegadores antiguos

### Carpeta de Imágenes (`img/`)
- **Formato**: Archivos SVG para gráficos vectoriales escalables
- **Contenido**: Avatares personalizados para cada integrante y logo del equipo
- **Ventajas**: Archivos ligeros, escalables y editables

### Documentación
- **README.md**: Documentación completa del proyecto en el directorio raíz
- **Contenido**: Descripción, tecnologías, instalación, y guías de uso

## Funcionalidades Implementadas

### Página Principal (index.html)
- **Mensaje de Bienvenida Dinámico**: Botón que muestra un saludo personalizado con la hora actual
- **Animación de Tarjetas**: Las tarjetas de los miembros se animan al cargar la página
- **Contadores Animados**: Estadísticas del equipo que se animan al hacer scroll
- **Cambio de Tema**: Toggle entre modo claro y oscuro con persistencia
- **Efecto Parallax**: Efecto visual en la sección hero
- **Navegación Suave**: Scroll suave entre secciones

### Páginas Individuales

#### Lucas (lucas.html)
- **Perfil Completo**: Desarrollador apasionado por la tecnología, el desarrollo de software, los juegos y el fútbol. Aprende desarrollo de software de manera formal y autodidacta desde hace 3 años.
- **Ubicación**: Villa Devoto, CABA (31 años)
- **Habilidades**: HTML, CSS, POO, JavaScript, SQL, C#, Git, Kotlin, Modelado y diseño de Software, Forjador de Telarañas Digitales, Maestro de Código
- **Secciones**: Información personal, habilidades técnicas, experiencia, películas favoritas y música
- **Funcionalidades Dinámicas JavaScript**:
  - **Cambio de Lema Dinámico**: Función `cambiarLema()` que rota entre diferentes lemas de casas de Game of Thrones
  - **Toggle de Información**: Función `toggleInfo()` que muestra/oculta información adicional del perfil
  - **Saludar**: Función `saludar()` que muestra un mensaje especial al usuario
  - **Scroll Suave**: Función `scrollSuave()` para navegación fluida entre secciones


#### Victoria (victoria.html)
- **Perfil Completo**: Diseñadora multimedia especializada en UX/UI. Se especializa en diseñar aplicaciones desde cero y darles vida a través de interfaces intuitivas y visualmente atractivas.
- **Ubicación**: Buenos Aires, Argentina (23 años)
- **Habilidades**: Figma, Adobe Suit, Prototipado, HTML, CSS, JavaScript, Kotlin
- **Secciones**: Información personal, habilidades técnicas, proyectos destacados (Deboot, Hyped, InteractxTech), películas favoritas y música
- **Características**: Incluye showcase de proyectos con prototipos interactivos
- **Funcionalidades Dinámicas JavaScript**:
  - **Animaciones de Hadas**: Función `crearCorazon()` que genera hadas flotantes animados
  - **Carrusel Bootstrap**: Carrusel automático de proyectos con controles de navegación
  - **Efecto de Escritura**: Animación de texto tipo máquina de escribir para el nombre en el h2
  - **Botón Volver Arriba**: Función de scroll suave hacia la parte superior de la página

#### Sebastián (sebastian.html)
- **Perfil Completo**: Desarrollador Full Stack con gran pasión por la innovación y las nuevas tecnologías. Se especializa en la integración de sistemas.
- **Ubicación**: Valencia, España (26 años)
- **Habilidades**: Vue.js, React, PHP, Laravel, MySQL, Docker, Git, AWS
- **Secciones**: Información personal, habilidades técnicas, certificaciones (AWS Certified Developer, Vue.js Expert, Scrum Master), películas favoritas y música
- **Funcionalidades Dinámicas JavaScript**:
  - **Rotación de Imagen**: Función `cambiarImagen()` que rota la imagen de perfil con transiciones
  - **Efectos Hover**: Animaciones de elevación en tarjetas de películas y música

#### José (jose.html)
- **Perfil Completo**: Página temática de Wolverine/Logan. Estudiante que busca su camino en el mundo de la programación.
- **Ubicación**: ??? (Más de 100 años - personaje ficticio)
- **Habilidades**: Factor de curación acelerado, Garras de adamantium, Combate cuerpo a cuerpo, Sentidos agudizados, Resistencia sobrehumana, Envejecimiento casi inexistente
- **Secciones**: Información del personaje Wolverine, habilidades mutantes, experiencia como X-Men y soldado, información sobre José como estudiante
- **Funcionalidades Dinámicas JavaScript**:
  - **Cambio de Imagen**: Función `cambiarImagen()` que rota entre diferentes imágenes de Wolverine
  - **Scroll Suave**: Función `scrollSuave()` para navegación fluida entre secciones
  - **Datos Aleatorios**: Función `datoRandom()` que muestra curiosidades sobre Wolverine en alertas
  - **Carrusel Bootstrap**: Carrusel automático de juegos con intervalo personalizado de 1.3 segundos

#### Estiven (estiven.html)
- **Perfil Completo**: Desarrollador de software estudiando en el IFTS N° 29. Trabaja desarrollando aplicaciones web para empresa mediana, especializado en e-commerce de muebles de pino.
- **Ubicación**: Buenos Aires, Argentina (31 años)
- **Habilidades**: NodeJS, MySQL, Express, NestJS, NextJS, Python, C#, .NET
- **Secciones**: Información personal, habilidades técnicas, experiencia profesional, favoritos (IA, series y películas), carrusel de películas y música
- **Entretenimiento**: Películas de ciencia ficción y música experimental con carrusel interactivo
- **Funcionalidades Dinámicas JavaScript**:
  - **Rotación de Imagen**: Función `rotarImagen()` que rota la imagen de perfil 90 grados con cada clic
  - **Carrusel 3D de Música**: Carrusel tridimensional interactivo para mostrar música favorita con navegación manual
  - **Carrusel de Películas**: Sistema de carrusel automático para series y películas favoritas con indicadores
  - **Efectos Hover Avanzados**: Animaciones de elevación en tarjetas de favoritos con translateY

### Bitácora (bitacora.html)
- **Resumen Ejecutivo**: Generación dinámica de resumen del proyecto
- **Animaciones de Entrada**: Efectos de aparición basados en scroll
- **Navegación Contextual**: Enlaces directos a secciones específicas

### Funcionalidades Globales
- **Diseño Responsivo**: Adaptación a dispositivos móviles, tablets y desktop
- **Navegación Intuitiva**: Menú de navegación con dropdown y enlaces contextuales
- **Alertas Personalizadas**: Sistema de notificaciones para interacciones
- **Scroll Suave**: Navegación fluida entre secciones
- **Animaciones CSS**: Transiciones y efectos visuales en toda la aplicación

## Diseño Responsivo

El sitio web está optimizado para diferentes tamaños de pantalla con los siguientes breakpoints:

- **400px**: Dispositivos móviles pequeños
  - Layout de una columna
  - Navegación colapsable
  - Texto y botones optimizados para touch
  - Imágenes redimensionadas

- **900px**: Tablets y pantallas medianas
  - Layout de dos columnas en secciones principales
  - Navegación horizontal
  - Tarjetas reorganizadas para mejor aprovechamiento del espacio

- **1200px**: Pantallas de escritorio grandes
  - Layout completo de tres columnas donde aplique
  - Navegación completa visible
  - Máximo aprovechamiento del espacio disponible
  - Efectos hover más prominentes

## Características Técnicas

### Accesibilidad
- Estructura HTML semántica
- Atributos ARIA apropiados
- Contraste de colores optimizado
- Navegación por teclado
- Textos alternativos en imágenes

### Performance
- Imágenes SVG para gráficos escalables
- CSS optimizado con variables
- JavaScript modular y eficiente
- Carga asíncrona de recursos
- Animaciones optimizadas para GPU

### Compatibilidad
- Soporte para navegadores modernos
- Fallbacks para funcionalidades avanzadas
- Progressive enhancement
- Validación HTML5 y CSS3

## Instalación y Uso

1. **Clonar o descargar** el proyecto en tu máquina local
2. **Abrir** el archivo `index.html` en tu navegador web preferido
3. **Navegar** por las diferentes secciones usando el menú de navegación
4. **Explorar** las funcionalidades interactivas en cada página
5. **Probar** el diseño responsivo redimensionando la ventana del navegador

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar Bootstrap y Google Fonts desde CDN)
- JavaScript habilitado para funcionalidades interactivas

## Estructura de Archivos CSS

El archivo `styles.css` está organizado en las siguientes secciones:

1. **Variables CSS**: Colores, fuentes y espaciados
2. **Estilos Base**: Reset y estilos generales
3. **Componentes**: Navbar, cards, botones, footer
4. **Páginas Específicas**: Estilos únicos para cada página
5. **Responsive Design**: Media queries para diferentes dispositivos
6. **Animaciones**: Keyframes y transiciones


## JavaScript - Funciones Dinámicas Implementadas

### Página Principal (`index.html`)

#### Sección Hero/Portada
- **Mensaje de Bienvenida Dinámico**: Función `mostrarBienvenida()` que muestra un saludo personalizado con la hora actual al hacer clic en el botón "¡Conoce al equipo!"
- **Efecto Parallax**: Animación de fondo que se mueve a diferente velocidad durante el scroll
- **Animación de Entrada**: Efectos fade-in en elementos al cargar la página

#### Sección de Equipo
- **Animación de Tarjetas**: Función `animarTarjetas()` que hace aparecer las tarjetas de los integrantes con efecto de deslizamiento
- **Efectos Hover**: Transformaciones y sombras al pasar el mouse sobre las tarjetas

#### Sección de Estadísticas
- **Contadores Animados**: Función `animarContadores()` que incrementa los números desde 0 hasta el valor final cuando la sección es visible
- **Intersection Observer**: Detecta cuando los elementos entran en el viewport para activar animaciones

#### Funcionalidades Globales

- **Scroll Suave**: Función `scrollSuave()` para navegación fluida entre secciones
- **Sistema de Alertas**: Función `mostrarAlerta()` para notificaciones personalizadas

## Licencia

Este proyecto es de uso educativo y está disponible bajo licencia MIT.

---

**Equipo Innovador - Grupo 9** - Desarrollando el futuro, una línea de código a la vez. 🚀