# 🌮 Cocina Pro - App de Inventario & Chef IA
Cocina Pro es una aplicación web moderna tipo "App Móvil" diseñada para gestionar tu despensa y descubrir recetas auténticas basadas en los ingredientes que tienes en casa.
Funciona como un Chef Inteligente: seleccionas lo que tienes en tu refrigerador y la app te sugiere qué cocinar, indicándote el porcentaje de coincidencia y qué ingredientes te faltan.
✨ Características Principales
1. 🥕 Gestión de Inventario Visual
Interfaz intuitiva: Iconos claros para agregar y quitar ingredientes.
Categorías: Frutas, Verduras, Carnes, Alacena, Lácteos, etc.
Persistencia: Tu inventario se guarda automáticamente en el navegador (LocalStorage).
2. 👨‍🍳 Chef Inteligente (Generador de Recetas)
Algoritmo de Coincidencia: Compara tu inventario con la base de datos de recetas.
Barra de Progreso: Te muestra visualmente qué tanto de la receta puedes cocinar (ej. "Te faltan 2 ingredientes" o "¡Tienes todo!").
Priorización: Ordena automáticamente las recetas por mayor coincidencia.
3. 🛒 Lista de Compras
Agrega ingredientes faltantes directamente desde la vista de la receta.
Marca items como "comprados" para moverlos automáticamente a tu inventario.
Comparte o gestiona tu lista fácilmente.
4. ❤️ Favoritos
Guarda tus recetas preferidas para acceso rápido.
5. 📱 Diseño "Mobile-First"
Barra de navegación inferior fija para fácil acceso en móviles.
Transiciones suaves y alertas animadas.
Diseño limpio y moderno usando Tailwind CSS.
🛠️ Tecnologías Utilizadas
El proyecto utiliza una arquitectura Single File Component (todo en un solo archivo HTML) para facilitar el despliegue y la edición.
HTML5: Estructura semántica.
Tailwind CSS (CDN): Diseño moderno y responsivo sin necesidad de compilación.
Vanilla JavaScript: Lógica de la aplicación, algoritmo del chef y manejo del localStorage.
SweetAlert2: Ventanas modales y notificaciones elegantes.
Font Awesome: Iconografía.
🚀 Instalación y Uso
No necesitas instalar nada (ni Node.js, ni bases de datos).
Descarga el archivo index.html de este repositorio.
Ábrelo directamente en tu navegador (Chrome, Safari, Edge, etc.).
¡Listo! La aplicación funcionará inmediatamente.
🌐 Cómo Publicar en GitHub Pages
Sigue estos pasos para tener tu app online gratis:
Ve a la pestaña Settings (Configuración) de tu repositorio en GitHub.
En el menú izquierdo, haz clic en Pages.
En la sección "Build and deployment" > Branch, selecciona main y la carpeta / (root).
Haz clic en Save.
Espera unos minutos y tu sitio estará vivo en: https://tu-usuario.github.io/tu-repositorio/
📂 Estructura del Proyecto
index.html: Archivo maestro que contiene:
Estructura HTML.
Estilos CSS (Tailwind config).
Base de datos JSON (Recetas e Ingredientes).
Lógica JS.
📄 Licencia
Este proyecto es de código abierto. ¡Siéntete libre de usarlo y modificarlo para tu propia cocina!
