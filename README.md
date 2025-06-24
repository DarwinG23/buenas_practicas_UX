# buenas_practicas_UX

# 🏆 SportBoard – Módulo de Gestión de Competencias Deportivas

SportBoard es una aplicación web centrada en la gestión de competencias deportivas, diseñada bajo buenas prácticas de UX para asegurar una experiencia fluida, intuitiva y accesible para usuarios como organizadores, árbitros y administradores de torneos.

Este repositorio contiene el diseño y prototipo de 6 interfaces clave del módulo de competencias, así como su implementación base en HTML y CSS.

---

## 📌 Objetivo del Proyecto

Diseñar e implementar una solución web para administrar competencias deportivas de manera eficiente, visual e intuitiva, utilizando buenas prácticas de diseño de experiencia de usuario (UX).

---

## 🔁 Proceso de Trabajo

El desarrollo del proyecto siguió las siguientes fases:

### 1. **Investigación sobre UX**
Se realizó una investigación detallada sobre buenas prácticas de UX, abordando conceptos como:
- Diseño Centrado en el Usuario (DCU)
- Principios de usabilidad, accesibilidad e interacción
- Arquitectura de la información clara
- Proceso iterativo y evaluación constante
- Técnicas como prototipado, wireframing, pruebas de usabilidad, customer journey map, mapas de empatía, etc.

> 📚 La investigación fue apoyada con la herramienta **Google NotebookLM**, que permitió sintetizar fuentes académicas y artículos especializados en UX.

### 2. **Definición del módulo y vistas necesarias**
Se eligió diseñar el **módulo de gestión de competencias deportivas**, con 6 vistas principales que abordan todo el ciclo de vida de una competencia:
1. Inicio del módulo de competencias
2. Creación de competencia
3. Detalle de competencia
4. Gestión de participantes/equipos
5. Calendario de partidos
6. Resultados y clasificación

### 3. **Diseño de Interfaz (Figma AI)**
Se usó un prompt detallado para generar las interfaces utilizando Figma AI, alineado con las buenas prácticas de UX y estética profesional.

### 4. **Prototipado HTML/CSS**
Se implementó un prototipo funcional de las vistas diseñadas, usando:
- HTML5 semántico
- CSS3 con enfoque responsive
- JavaScript opcional (interacciones simples)

---

## 🤖 Prompt Utilizado en Google Stitch

Diseña una interfaz web moderna y centrada en el usuario para una aplicación llamada **SportBoard**, enfocada en la **gestión de competencias deportivas**. Aplica buenas prácticas de UX en estructura, navegación, colores, tipografía e interacciones. Utiliza una estética profesional, accesible, clara, dinámica, y moderna, con una paleta de colores relacionados al deporte (azules, verdes, blanco, grises neutros y detalles en rojo o naranja para notificaciones o acciones críticas). Crea **6 interfaces (pantallas)** detalladas del módulo de competencias, siguiendo los principios de usabilidad, accesibilidad, diseño centrado en el usuario, arquitectura clara e interacción intuitiva. Agrega imágenes o íconos que refuercen visualmente cada vista, manteniendo consistencia en estilo, botones, inputs y navegación. ### Interfaces a diseñar: --- 1. **Vista de Inicio del Módulo de Competencias** - Muestra un dashboard con tarjetas resumidas de las competencias activas, finalizadas y próximas. - Incluye botones visibles para "Crear nueva competencia" y "Filtrar por deporte, estado o fecha". - Agrega íconos e indicadores visuales de estado (activo, terminado, en preparación). - Barra lateral de navegación fija, con acceso a otros módulos (Usuarios, Equipos, Estadísticas). --- 2. **Formulario de Creación de Competencia** - Vista con campos bien distribuidos para ingresar: - Nombre de la competencia - Deporte - Categoría (Ej. Sub-18, Libre) - Fecha de inicio y fin (con datepicker) - Ubicación (mapa o campo texto) - Cantidad de equipos/participantes - Descripción - Validaciones visuales (colores e íconos de error/success) - Botones de "Guardar", "Cancelar", y "Previsualizar" --- 3. **Vista de Detalle de una Competencia** - Encabezado con el nombre, estado y fechas principales - Pestañas o secciones: Información general, Participantes, Calendario de partidos, Reglas - Muestra un mini-dashboard con métricas: cantidad de partidos, equipos inscritos, partidos jugados, resultados pendientes - Botón de "Editar competencia" y "Eliminar" con confirmación --- 4. **Gestión de Participantes / Equipos** - Tabla editable con columnas: nombre del equipo/jugador, categoría, estado, acciones (editar/eliminar) - Botón para "Agregar nuevo participante/equipo" - Filtros por categoría o estado de inscripción - Interacción intuitiva para edición inline o modal emergente --- 5. **Calendario de Partidos de la Competencia** - Calendario visual (tipo calendario mensual o lista cronológica) - Mostrar partidos programados con hora, lugar y equipos enfrentados - Acciones rápidas: "Editar", "Reprogramar", "Agregar nuevo partido" - Indicadores visuales de estado del partido (pendiente, en curso, finalizado) --- 6. **Vista de Resultados y Clasificación** - Tabla de posiciones con columnas como: Equipo, Puntos, PJ, PG, PE, PP, GF, GC, Dif. - Visualización de resultados recientes en formato de tarjetas o listado - Gráfica (opcional) de rendimiento por equipo - Botón para exportar resultados (.csv o .pdf) --- ### Estilo general: - Utiliza botones claros y consistentes con colores de acción (azul para primario, verde para éxito, rojo para errores). - Usa tipografía moderna, legible y jerarquías visuales claras (H1, H2, H3, texto secundario). - Agrega *feedback* visual para interacciones (hover, loading, success, error). - Interfaces responsivas (adaptables a móvil/tablet/escritorio). - Usa imágenes o íconos relacionados con deporte para reforzar contexto visual. - Usa componentes reutilizables y grillas consistentes en todo el diseño. ### Referencias de estilo (opcional): - Similar a plataformas como **SofaScore**, **Torneus**, o dashboards de administración deportiva - Inspiración visual en sitios como **Dribbble**, **Material Design**, o **Tailwind UI** Genera los diseños en alta fidelidad (hi-fi) directamente listos para prototipar o implementar en HTML/CSS. 
