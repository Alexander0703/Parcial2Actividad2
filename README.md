📚 Biblioteca de Normandía
HTML5
CSS3
Responsive
Sitio web moderno y responsive para la Biblioteca de Normandía con un tema oscuro rojo y negro. Permite explorar el catálogo de libros, registrarse como miembro y contactar con la biblioteca.

🎯 Características Destacadas
- Diseño Moderno — Tema oscuro rojo/negro con gradientes y efectos visuales.
- Totalmente Responsive — Mobile First; adaptable a móviles y tablets.
- Navegación Intuitiva — Menús con hover y transiciones suaves.
- Catálogo Visual — Tabla con 8 libros y estados colorizados (Disponible, Prestado, Reservado, En reparación).
- Formulario Estilizado — Registro de usuarios con validación visual y feedback.

🚀 Comenzar
Prerrequisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge).
- Servidor web local opcional (recomendado para pruebas con fetch, JSON o rutas relativas).
- (Opcional) Node.js o PHP si prefieres otros servidores locales.
Instalación
git clone https://github.com/Alexander0703/Parcial2Actividad2.git
cd Parcial2Actividad2


Ejecutar localmente
- Abrir index.html directamente en el navegador (rápido, algunas funciones pueden fallar si usan fetch).
- Servir con Python 3:
python -m http.server 8000
# luego visita http://localhost:8000


- Servir con Node (http-server):
npx http-server


- Servir con PHP:
php -S localhost:8000



📁 Estructura del Proyecto
Parcial2Actividad2/
- index.html        # Página principal
- catalogo.html     # Catálogo de libros
- registro.html     # Formulario de registro
- contacto.html     # Información de contacto
- style.css         # Estilos principales (tema oscuro rojo/negro)
- biblioteca.jpg    # Imagen de la biblioteca
- mapa.jpeg         # Mapa de ubicación
- README.md         # Este archivo         

🖥️ Páginas y Funcionalidades
index.html
Página principal con bienvenida, imagen representativa, resumen de servicios y navegación a las demás secciones.
catalogo.html
Tabla responsive con 8 libros que muestra Título, Autor, Género y Estado. Estados colorizados:
- 🟢 Disponible
- 🟡 Prestado (con posible fecha de vencimiento)
- 🔵 Reservado
- 🔴 En reparación
registro.html
Formulario de registro con validación visual y campos: Nombre de usuario, Correo electrónico, Contraseña, Aceptación de normas.
contacto.html
Información de contacto con enlace integrado a Google Maps, imagen del mapa y datos de dirección/telefono/email.

🎨 Diseño y Estética
- Colores principales: Fondo gradiente negro (#0a0a0a → #1a1a1a), acento rojo carmesí (#b91c1c / #dc2626).
- Tipografía clara, alto contraste para legibilidad.
- Efectos: sombras, gradientes, transiciones suaves y glow sutil en acentos rojos.
- Componentes reutilizables y variables CSS para fácil personalización.

🛠️ Tecnologías Utilizadas
- HTML5 — Estructura semántica.
- CSS3 — Variables CSS, Flexbox, Gradientes, Transiciones, Media Queries.
- Opcional: JavaScript para validación y carga dinámica (próximas mejoras).

🚦 Accesibilidad y Performance
- Estructura semántica y navegación por teclado.
- Contraste suficiente en textos y botones.
- Imágenes comprimidas y optimizadas.
- CSS modular para mantenimiento y rendimiento.

📈 Próximas Mejoras
- Validación completa y feedback con JavaScript.
- Búsqueda y filtrado del catálogo.
- Modo claro/oscuro toggle.
- Páginas individuales por libro y sistema de comentarios/ratings.
- Guardar catálogo en JSON y cargar dinámicamente.

👥 Contribuciones
- Haz Fork del repositorio.
- Crea una rama: git checkout -b feature/nombre-feature.
- Haz commits claros: git commit -m "feat: descripción corta".
- Push a tu fork: git push origin feature/nombre-feature.
- Abre un Pull Request describiendo los cambios.
Se agradecen mejoras en estilos, accesibilidad, validación y datos del catálogo.

📄 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE en el repositorio para más detalles.

📞 Contacto
- Repositorio: https://github.com/Alexander0703/Parcial2Actividad2.git
- GitHub: @Alexander0703

Diseñado usando HTML5 y CSS3 — tema oscuro rojo y negro.
Si quieres, puedo generar un ejemplo de style.css base con variables, layout y estilos para las tablas y el formulario.
Diseñado usando HTML5 y CSS3 — tema oscuro rojo y negro.
Si quieres, puedo generar un ejemplo de style.css base con variables, layout y estilos para las tablas y el formulario.
