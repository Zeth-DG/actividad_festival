# FestivalGo 2026 - Laboratorio Grupal HTML & CSS

Este repositorio contiene la entrega del proyecto **FestivalGo 2026**, una Landing Page para un festival de música desarrollada utilizando exclusivamente **HTML5 y CSS3** puros, cumpliendo con los lineamientos solicitados en la rúbrica del laboratorio.

## Requisitos de la Actividad 

El proyecto fue desarrollado evitando el uso de JavaScript y estructurado estrictamente según las indicaciones de la actividad:

### 1. Estructura HTML 
- **Secciones claras:** Todo el sitio está dividido y enlazado correctamente: Inicio (`#inicio`), Artistas (`#artistas`), Experiencias (`#experiencias`) y Boletos (`#boletos`).
- **Navegación funcional:** Los enlaces en la barra de navegación y los botones redirigen al usuario a su respectiva sección en la misma página (Scroll).

### 2. Uso de Selectores CSS
- **Selector de Elemento:** Utilizado para estilizar etiquetas globales (ej. `button`, `footer`, `p`).
- **Selector de Clase:** Implementado extensamente para reusabilidad (ej. `.card`, `.inicio-texto`, `.btn-ticket`).
- **Selector de ID:** Uso específico en las secciones principales (`#inicio`, `#boletos`) para permitir la navegación (Anclas) y sus estilos básicos.
- **Selector Agrupado:** Aplicado como reseteo básico de los títulos (`h1, h2, h3, h4, h5, h6`).

### 3. Implementación del Modelo de Cajas
Para el componente de las tarjetas (Artistas, Experiencias y Boletos), implementamos la clase base `.card` y `.artista`, las cuales manejan de forma rigurosa las 5 propiedades requeridas del Box Model:
- `width` (Ancho definido para evitar desbordes).
- `padding` (Espaciado interno del contenido).
- `margin` (Espaciado externo para separación).
- `border` (Línea decorativa exterior).
- `border-radius` (Esquinas redondeadas).

### 4. Pseudoclases
- `:hover` en tarjetas: Las tarjetas se elevan levemente (`transform`) y proyectan sombra para indicar que son interactivas.
- `:hover` en botones: Cambian de color y flotan.
- `:active` en botones: Se achican sutilmente (`scale`) cuando el usuario hace clic.

> **Equipo de Desarrollo:**  
> Gonzalo, Karen, Luis, Vanya, Alma.  
