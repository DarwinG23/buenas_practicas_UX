# Interfaces Mobile
![image](https://github.com/user-attachments/assets/d29c5b8c-7626-411a-93f2-0169ea5f2dee) 
![image](https://github.com/user-attachments/assets/e5aa613e-8af6-49e1-b820-e41095b14de7)
![image](https://github.com/user-attachments/assets/a45049a9-1e78-4608-8ab6-eb363401a98a)
![image](https://github.com/user-attachments/assets/d284b5ea-9499-48c1-9ad5-223cdeae66a8) 
![image](https://github.com/user-attachments/assets/29d9c0d0-40f6-45a1-a15c-0816b88624f4) 
![image](https://github.com/user-attachments/assets/98ca3031-c79b-4b68-a2f9-d87638057334)

# Interfaces Web
![image](https://github.com/user-attachments/assets/c03ee37c-42e3-4765-b821-1523e2d9e036) 
![image](https://github.com/user-attachments/assets/3872fc32-c0a9-4435-9bcf-94db0ee5fbc5)
![image](https://github.com/user-attachments/assets/f9b79ee8-d99b-4f58-9f78-f5a7190f3936) 
![image](https://github.com/user-attachments/assets/3ca6cf00-3c96-4c54-8ba5-c53c2eb489db) 
![image](https://github.com/user-attachments/assets/6f15dca4-270f-4cf9-bed4-1d0dd3bf4d76) 
![image](https://github.com/user-attachments/assets/dc6a24f0-7b0c-4a0e-9977-353beaeac448)


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

## 🤖 Prompt para interfaces web utilizado en Google Stitch

Diseña una interfaz web moderna y centrada en el usuario para una aplicación llamada **SportBoard**, enfocada en la **gestión de competencias deportivas**. Aplica buenas prácticas de UX en estructura, navegación, colores, tipografía e interacciones. Utiliza una estética profesional, accesible, clara, dinámica, y moderna, con una paleta de colores relacionados al deporte (azules, verdes, blanco, grises neutros y detalles en rojo o naranja para notificaciones o acciones críticas). Crea **6 interfaces (pantallas)** detalladas del módulo de competencias, siguiendo los principios de usabilidad, accesibilidad, diseño centrado en el usuario, arquitectura clara e interacción intuitiva. Agrega imágenes o íconos que refuercen visualmente cada vista, manteniendo consistencia en estilo, botones, inputs y navegación. ### Interfaces a diseñar: --- 1. **Vista de Inicio del Módulo de Competencias** - Muestra un dashboard con tarjetas resumidas de las competencias activas, finalizadas y próximas. - Incluye botones visibles para "Crear nueva competencia" y "Filtrar por deporte, estado o fecha". - Agrega íconos e indicadores visuales de estado (activo, terminado, en preparación). - Barra lateral de navegación fija, con acceso a otros módulos (Usuarios, Equipos, Estadísticas). --- 2. **Formulario de Creación de Competencia** - Vista con campos bien distribuidos para ingresar: - Nombre de la competencia - Deporte - Categoría (Ej. Sub-18, Libre) - Fecha de inicio y fin (con datepicker) - Ubicación (mapa o campo texto) - Cantidad de equipos/participantes - Descripción - Validaciones visuales (colores e íconos de error/success) - Botones de "Guardar", "Cancelar", y "Previsualizar" --- 3. **Vista de Detalle de una Competencia** - Encabezado con el nombre, estado y fechas principales - Pestañas o secciones: Información general, Participantes, Calendario de partidos, Reglas - Muestra un mini-dashboard con métricas: cantidad de partidos, equipos inscritos, partidos jugados, resultados pendientes - Botón de "Editar competencia" y "Eliminar" con confirmación --- 4. **Gestión de Participantes / Equipos** - Tabla editable con columnas: nombre del equipo/jugador, categoría, estado, acciones (editar/eliminar) - Botón para "Agregar nuevo participante/equipo" - Filtros por categoría o estado de inscripción - Interacción intuitiva para edición inline o modal emergente --- 5. **Calendario de Partidos de la Competencia** - Calendario visual (tipo calendario mensual o lista cronológica) - Mostrar partidos programados con hora, lugar y equipos enfrentados - Acciones rápidas: "Editar", "Reprogramar", "Agregar nuevo partido" - Indicadores visuales de estado del partido (pendiente, en curso, finalizado) --- 6. **Vista de Resultados y Clasificación** - Tabla de posiciones con columnas como: Equipo, Puntos, PJ, PG, PE, PP, GF, GC, Dif. - Visualización de resultados recientes en formato de tarjetas o listado - Gráfica (opcional) de rendimiento por equipo - Botón para exportar resultados (.csv o .pdf) --- ### Estilo general: - Utiliza botones claros y consistentes con colores de acción (azul para primario, verde para éxito, rojo para errores). - Usa tipografía moderna, legible y jerarquías visuales claras (H1, H2, H3, texto secundario). - Agrega *feedback* visual para interacciones (hover, loading, success, error). - Interfaces responsivas (adaptables a móvil/tablet/escritorio). - Usa imágenes o íconos relacionados con deporte para reforzar contexto visual. - Usa componentes reutilizables y grillas consistentes en todo el diseño. ### Referencias de estilo (opcional): - Similar a plataformas como **SofaScore**, **Torneus**, o dashboards de administración deportiva - Inspiración visual en sitios como **Dribbble**, **Material Design**, o **Tailwind UI** Genera los diseños en alta fidelidad (hi-fi) directamente listos para prototipar o implementar en HTML/CSS. 

## 🤖 Prompt para interfaces mobile utilizado en Google Stitch 
Descripción General del Diseño: Diseña una interfaz móvil moderna, profesional y centrada en el usuario para la aplicación SportBoard, especializada en la gestión de competencias deportivas. El diseño debe ser totalmente responsivo, optimizado para dispositivos móviles (smartphones), con una navegación clara, intuitiva y adaptada al uso táctil. Aplica buenas prácticas de UX móvil, considerando limitaciones y ventajas del entorno móvil: accesibilidad, jerarquías visuales simplificadas, menús compactos (hamburguesa o bottom navigation), botones táctiles grandes y feedback visual adecuado. Usa una estética profesional, deportiva, accesible y dinámica, con una paleta de colores coherente: azules, verdes, blancos, grises neutros, y detalles en rojo o naranja para notificaciones o acciones críticas. 📱 Diseña 6 Pantallas Clave del Módulo de Competencias (Mobile): 1️ Vista de Inicio del Módulo de Competencias (Mobile Dashboard) Layout tipo scroll vertical con tarjetas apiladas mostrando: Competencias activas, finalizadas y próximas (con etiquetas de estado de color). Botón fijo o flotante “+ Crear competencia” (FAB - Floating Action Button). Filtro accesible desde un botón o menú desplegable: Deporte, Estado, Fecha. Barra inferior de navegación fija con íconos: Competencias, Usuarios, Equipos, Estadísticas. Íconos e indicadores visuales para estados (activo, terminado, en preparación). Cards con resumen: nombre, fecha, estado, y acceso rápido al detalle. 2️ Formulario de Creación de Competencia (Mobile Form) Formulario en scroll vertical, con campos bien espaciados y botones táctiles grandes: Nombre de la competencia Deporte (selector desplegable o modal) Categoría (ej. Sub-18, Libre) Fecha inicio y fin (con DatePicker móvil) Ubicación (campo texto o botón para abrir mapa) Cantidad de equipos/participantes (stepper numérico o input) Descripción (textarea adaptable) Feedback en tiempo real: colores, íconos de error o éxito. Botones fijos abajo: Guardar, Cancelar, y Previsualizar (con espaciado adecuado para uso táctil). 3️  Vista de Detalle de una Competencia (Mobile Detail View) Encabezado con: Nombre, estado (badge), fechas y ubicación. Menú tipo tabs deslizables (horizontal scroll) para navegar entre: Información general Participantes Calendario Reglas Mini-dashboard resumen (cards pequeñas o badges): Total partidos Equipos inscritos Partidos jugados Resultados pendientes Botones de acción visibles: Editar competencia (ícono lápiz) Eliminar (ícono papelera, con confirmación emergente) 4️ Gestión de Participantes / Equipos (Mobile Table/List) Lista tipo card o tabla vertical con: Nombre del equipo/jugador Categoría Estado (badge) Botones pequeños: Editar / Eliminar Botón flotante “+ Agregar participante/equipo”. Filtros accesibles desde botón desplegable o chips superiores: Por categoría o estado. Edición rápida mediante: Modal emergente o Navegación a pantalla de edición. 5️ Calendario de Partidos (Mobile Calendar) Vista tipo: Calendario mensual (scrollable) o Lista cronológica de partidos ordenados por fecha. Cada partido muestra: Hora, lugar, equipos enfrentados y estado (pendiente, en curso, finalizado). Acciones rápidas desde cada item: Editar Reprogramar Agregar nuevo partido (botón flotante). Usa colores e íconos para diferenciar estados de los partidos. 6️  Vista de Resultados y Clasificación (Mobile Stats) Tabla de posiciones en scroll horizontal si es necesario: Columnas: Equipo, Pts, PJ, PG, PE, PP, GF, GC, Dif. Resultados recientes en cards o lista con: Marcador Fecha y equipos Opcional: Gráfica de rendimiento por equipo (barras o líneas). Botón de “Exportar” resultados en .csv o .pdf (ícono de descarga).  Estilo y Componentes para Móvil: Botones grandes, con padding suficiente para interacción táctil. Bottom Navigation fijo con 3-5 íconos principales. Tipografía moderna, legible, jerarquías claras: H1: Títulos principales H2: Subtítulos o secciones Body: Texto informativo Feedback visual: Estados hover (sutil en móvil), loading, success, error. Interacción rápida y fluida: evita pantallas innecesarias, prioriza accesos rápidos y modales. Iconografía coherente con el contexto deportivo. Uso de sombreados, bordes redondeados, efectos suaves.  Paleta de Colores: Primarios: Azul (#007BFF), Verde (#28A745) Neutros: Blanco (#FFFFFF), Grises (#6C757D a #F8F9FA) Críticos: Rojo (#DC3545) o Naranja (#FD7E14) para alertas o acciones importantes.  Inspiración Visual: Apps como SofaScore, FlashScore, FIFA Mobile, Strava. Diseño limpio estilo Material Design, Tailwind Mobile UI, o iOS Guidelines.
