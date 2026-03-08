Portafolio Web Interactivo - Perfil Personal

¿Qué es y cuál es su propósito?
Este proyecto es un Portafolio Web modular e interactivo, desarrollado desde cero como una carta de presentación digital.
Su propósito principal es mostrar de manera estructurada y visualmente atractiva la identidad, intereses, trayectoria académica y proyectos personales del autor.
El sistema fue construido utilizando tecnologías web estándar (HTML5, CSS3 y JavaScript), demostrando habilidades prácticas sólidas en programación Frontend. Es un paso firme en el desarrollo profesional práctico hacia la meta de ejercer como Software Engineer en la industria tecnológica.

Nota sobre la arquitectura visual: Notarás que la página está construida con una estructura de paneles o áreas independientes (Menú Izquierdo, Contenido Central y Menú Derecho). Esta fue una decisión de diseño deliberada para mantener la navegación estática a los lados mientras el contenido central cambia dinámicamente. De esta forma, se optimiza la experiencia del usuario, manteniendo las herramientas principales siempre a la mano.

¿Cómo explorar el proyecto? (Guía Rápida)
Para navegar por toda la plataforma, simplemente abre el archivo principal en tu navegador web.
La interfaz está dividida en tres zonas clave para facilitar su uso:
Zona Izquierda: Tu menú de navegación principal para explorar las diferentes facetas (Sobre Mí, Estudios, Hobbies, Mascotas, etc.).
Zona Central: El escenario principal donde se carga la información detallada de cada sección seleccionada.
Zona Derecha: Un panel de acceso rápido para conectar directamente a través de redes sociales.

¿Cómo funciona? (Funciones Principales y Técnicas)

1. Reproductor Multimedia Personalizado (Canciones Favoritas)
Una de las características más complejas y destacadas del portafolio es la galería musical interactiva.
Control total: Se integró un reproductor de audio mediante JavaScript que oculta los controles aburridos del navegador y utiliza botones personalizados (▶ / ❚❚).
Barra de progreso inteligente: Cada canción cuenta con su propia barra visual (<progress>) que se actualiza en tiempo real. Además, los usuarios pueden hacer clic en cualquier parte de la barra para adelantar o atrasar la canción a su gusto.
Gestión de estados: El sistema es lo suficientemente inteligente para detectar si el usuario selecciona una nueva pista, pausando y reiniciando automáticamente la canción anterior para evitar que el audio se empalme.

2. Navegación Dinámica y Comunicación entre Ventanas
El sitio utiliza un sistema avanzado de mensajería interna (postMessage en JavaScript) para que los distintos menús se comuniquen con el contenedor principal. Por ejemplo, al hacer clic en el ícono de "Inicio" (la casa) en el encabezado, el script envía una orden exacta para regresar a la sección "Sobre Mí" de forma fluida y manejando posibles errores con bloques try/catch.

3. Panel de Conectividad Social (Menú Derecho)
Se diseñó una barra lateral utilizando CSS Flexbox para garantizar una alineación central perfecta de los elementos sin importar el tamaño de la ventana. Incluye botones interactivos hacia Facebook, Instagram, TikTok y WhatsApp.

Microinteracciones: Para mejorar la experiencia de usuario (UX), los íconos cuentan con efectos de transición (hover) programados en CSS. Al pasar el cursor sobre ellos, los íconos escalan y giran suavemente 360 grados, dándole un toque moderno y dinámico a la interfaz.

4. Diseño Limpio y Estructura Flexbox
La interfaz gráfica utiliza una paleta de colores cuidadosamente seleccionada (tonos verdes y olivo) que mantiene una estética coherente, haciendo un sutil guiño a los colores institucionales del TECNM. Además, se reemplazaron los posicionamientos absolutos por estructuras modernas (display: flex, justify-content: center) para asegurar que todos los elementos se adapten y se mantengan perfectamente centrados en la pantalla.
