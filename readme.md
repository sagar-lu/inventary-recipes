# Estructura del Proyecto - App de Recetas Mexicanas

## Archivos Principales

### 1. index.html - Página Principal
- **Hero Section**: Imagen vibrante de comida mexicana con título animado
- **Buscador Principal**: Barra de búsqueda con autocompletado
- **Categorías Populares**: Grid de categorías con iconos
- **Recetas Destacadas**: Carrusel de recetas populares
- **Estadísticas**: Visualización de datos sobre recetas
- **Testimonios**: Reviews de usuarios mexicanos

### 2. recetas.html - Galería de Recetas
- **Barra de Filtros**: Filtros por tiempo, ingredientes, tipo
- **Grid de Recetas**: Tarjetas interactivas con hover effects
- **Paginación**: Carga infinita o paginación tradicional
- **Ordenamiento**: Por popularidad, tiempo, dificultad
- **Vista de Lista/Grid**: Toggle entre vistas

### 3. receta-detalle.html - Página Individual de Receta
- **Imagen Hero**: Foto del platillo
- **Información Rápida**: Tiempo, porciones, dificultad
- **Ingredientes**: Lista interactiva con checkboxes
- **Instrucciones**: Pasos numerados con timers
- **Sustituciones**: Alternativas de ingredientes
- **Nutrición**: Información nutricional
- **Comentarios**: Reviews de otros usuarios

### 4. favoritos.html - Recetas Guardadas
- **Colecciones**: Grupos personalizados de recetas
- **Lista de Compras**: Ingredientes de recetas seleccionadas
- **Historial**: Recetas vistas recientemente
- **Recomendaciones**: Basadas en favoritos

## Archivos de Recursos

### 5. main.js - JavaScript Principal
- **Funcionalidad de Búsqueda**: Lógica de filtrado
- **Sistema de Favoritos**: LocalStorage para guardar recetas
- **Animaciones**: Control de efectos visuales
- **Interacciones**: Hover, click, scroll events
- **API de Recetas**: Simulación de datos de recetas

### 6. recetas-data.js - Base de Datos de Recetas
- **Recetas Completas**: 20+ recetas mexicanas auténticas
- **Ingredientes**: Con cantidades y unidades
- **Instrucciones**: Pasos detallados
- **Imágenes**: URLs de imágenes de recetas
- **Categorías**: Clasificación por tipo
- **Tiempo de Prep**: Duración de preparación

### 7. styles.css - Estilos Personalizados (si se necesita)
- **Animaciones Custom**: Efectos específicos
- **Media Queries**: Responsive design
- **Componentes**: Estilos reutilizables

## Estructura de Carpetas

```
/mnt/okcomputer/output/
├── index.html
├── recetas.html
├── receta-detalle.html
├── favoritos.html
├── main.js
├── recetas-data.js
├── resources/
│   ├── hero-mexican-food.jpg
│   ├── ingredients/
│   │   ├── chiles.jpg
│   │   ├── tortillas.jpg
│   │   ├── frijoles.jpg
│   │   └── ...
│   └── dishes/
│       ├── enchiladas.jpg
│       ├── tacos.jpg
│       ├── pozole.jpg
│       └── ...
└── README.md
```

## Contenido de Recetas

### Categorías Principales:
1. **Desayunos**: Chilaquiles, Huevos rancheros, Molletes
2. **Platos Fuertes**: Enchiladas, Tacos, Pozole, Mole
3. **Sopas**: Sopa de tortilla, Sopa de fideo, Caldo de pollo
4. **Antojitos**: Quesadillas, Gorditas, Sopes, Tostadas
5. **Postres**: Flan, Arroz con leche, Buñuelos
6. **Bebidas**: Agua fresca, Horchata, Jamaica

### Características de Cada Receta:
- Nombre auténtico y descripción
- Tiempo de preparación (15-45 min)
- Número de porciones (2-6 personas)
- Dificultad (Fácil/Media/Difícil)
- Costo estimado ($-$$$)
- Ingredientes con cantidades
- Instrucciones paso a paso
- Variaciones regionales
- Tips y secretos

## Funcionalidades Técnicas

### Interactividad:
- Búsqueda en tiempo real
- Filtros múltiples
- Sistema de favoritos
- Calculadora de porciones
- Timer de cocina
- Modo impresión

### Efectos Visuales:
- Animaciones de entrada
- Hover effects en tarjetas
- Scroll animations
- Loading states
- Transiciones suaves

### Responsive Design:
- Mobile-first approach
- Breakpoints: 320px, 768px, 1024px, 1440px
- Touch-friendly interface
- Optimizado para tablets

## Datos de la Aplicación

### Estadísticas a Mostrar:
- 25+ recetas disponibles
- 5 categorías principales
- 15+ ingredientes básicos
- Promedio de 25 minutos por receta
- Recetas de 10 estados de México
- Valoraciones de usuarios

### Contenido Multimedia:
- 25+ imágenes de recetas
- Iconos de ingredientes
- Ilustraciones decorativas
- Patrones mexicanos
- Fotos de ingredientes