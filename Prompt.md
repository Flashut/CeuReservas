Crea una maqueta HTML y CSS que replique con la máxima fidelidad el diseño visual y la estructura de las seis imágenes de mockup proporcionadas (Pantalla de Login, Dashboard, Disponibilidad, Confirmación de Reserva, Página de Confirmación, Tablero de Gestión).

Fidelidad Visual y Estructural:

Diseño Responsivo: La maqueta debe ser completamente responsive y adaptarse a diferentes tamaños de pantalla (escritorio, tablet, móvil). Emplea media queries para asegurar una experiencia de usuario óptima en todos los dispositivos.
Paleta de Colores y Tipografía: Identifica y replica con exactitud la paleta de colores utilizada en los mockups (fondo, texto, botones, estados de elementos). Utiliza las tipografías que visualmente más se asemejen a las mostradas, incluyendo tamaños, pesos y espaciado (letter-spacing, line-height). Si no se proporcionan fuentes específicas, opta por fuentes de Google Fonts que sean visualmente idénticas o muy similares.
Disposición y Espaciado: Reproduce con precisión la disposición de los elementos, el espaciado interno (padding) y externo (margin) entre componentes, y la alineación de texto y elementos dentro de sus contenedores.
Componentes UI: Recrea fielmente todos los componentes de la interfaz de usuario:
Encabezados y Navegación: Barras superiores, menús de navegación (CEU Reservas, Tablero, Gestión, etc.), iconos de perfil y notificaciones.
Formularios: Campos de entrada de texto (email, contraseña), placeholders, selectores de fecha/hora, botones de radio, checkboxes.
Tablas: Estructura de tablas (columnas, filas), colores de fondo de encabezados, estilos de celdas (bordes, padding), y estados visuales (ej. colores de "Confirmada", "Pendiente", "Cancelada").
Tarjetas y Paneles: Estilos de contenedores con sombras suaves y bordes redondeados.
Botones: Estados normales y hover (si se pueden inferir), colores, formas, y texto.
Gráficos/Indicadores: Reproduce el aspecto de los contadores (Ej. "Aulas Disponibles Hoy"), el calendario, y el gráfico de tendencias. No es necesario que sean funcionales con datos dinámicos, solo que visualmente sean idénticos.
Iconografía: Utiliza iconos que visualmente se correspondan con los mostrados en los mockups (ej. iconos de calendario, reloj, capacidad, proyector, Wi-Fi, etc.). Puedes usar librerías de iconos como Font Awesome si lo consideras apropiado.
Estados Visuales: Si se infiere un estado hover o active para algún elemento (como botones o elementos de navegación), implementa un cambio visual sutil.
Mapas/Imágenes de Campus: Replica el espacio para el mapa o las imágenes del campus, incluso si son solo marcadores de posición visuales.
Requisitos Funcionales (Inferidos del Mockup y Requisitos RF-XX aplicables):

Basado en las imágenes y los requisitos funcionales proporcionados, la maqueta debe incluir la estructura HTML y estilos CSS para los siguientes elementos interactivos o semánticos:

RF-001 (Login): Implementa la estructura del formulario de login (institutional.email@ceu.es y contraseña) en la pantalla de acceso. Los campos de entrada deben tener la estructura básica para aceptar input y el botón "Iniciar Sesión" debe ser un botón clicleable.
RF-007, RF-008, RF-009 (Horarios/Disponibilidad):
En la pantalla de Dashboard y Disponibilidad, la visualización de horarios (e.g., 8:00, 9:00) y el estado de las aulas ("Ocupada", "Disponible", "Pendiente") deben estar representados visualmente con los colores y checkmarks/cruces/círculos correspondientes.
La tabla de disponibilidad debe ser scrollable si hay muchas aulas/horarios para que el usuario pueda visualizar todo el contenido.
RF-015, RF-016, RF-017, RF-018 (Clasificación/Categorización/Inventario de Aulas):
En la pantalla de "Dashboard" y "Disponibilidad", el panel de "Filtros" y "Filtrar aulas" debe incluir los radio buttons y checkboxes con su estilo visual. No es necesario que el filtrado funcione dinámicamente, solo que la estructura y apariencia estén presentes.
En la pantalla de "Confirmación de Reserva", los "Detalles Adicionales de la Reserva" deben mostrar el "Capacidad", "Equipamiento A/V", "Servicios Adicionales" con los iconos y el formato de lista/texto.
RF-019 (Mapa Gráfico/Ubicación): En el Dashboard, el componente "Mapa de Salas del Campus" debe estar presente visualmente, con el botón "Explorar Mapa del Campus" y las listas de "Acceso Rápido" (edificios/laboratorios).
Elementos de Navegación: Los elementos del menú superior (CEU Reservas, Tablero, Gestión) deben ser enlaces (<a>) visualmente diferenciados que simulen una navegación.
Botones de Acción: Todos los botones visibles (ej. "Aplicar Filtros", "Borrar Filtros", "Ver Salas Disponibles", "Iniciar Sesión", "Modificar reserva", "Cancelar reserva", "Ver Aula", "Contactar Soporte", "Ver todos las reservas") deben ser elementos button o <a> con estilos que simulen un clic y, si es posible, un estado hover.
Contadores y Estadísticas: Los paneles de métricas (ej. "Aulas Disponibles Hoy", "Próximas Reservas", "Aulas Totales", "Reservas Totales", "Aprobaciones Pendientes", "Salas Disponibles Hoy", "Cancelaciones Este Mes") deben tener su estructura visual con el número grande y el texto descriptivo.
Tablas de Datos: Las tablas de "Tus Reservas Recientes", "Actividad Reciente de Reservas" y la de "Confirmación de Reserva" y "Página de Confirmación" deben estar estructuradas con <thead> y <tbody>, replicando los estilos de encabezados, filas, y el contenido con sus respectivos iconos (editar, borrar, check, cruz).
Elementos de Alerta/Notificación: En la pantalla de "Confirmación de reserva", los cuadros de "Alertas y Notificaciones" y "Atención" deben tener su estructura y estilos visuales, incluyendo iconos y texto.
Selección de Fecha/Hora: Los selectores de fecha (calendario) y hora (dropdown) deben tener su apariencia visual.
Información de Usuario/Aula: Los bloques que muestran "Datos del Solicitante", "Información de reserva", "Información del aula", "Inventario", "Información de contacto" deben estar estructurados y estilizados con los iconos y la información de ejemplo.
Gráficos (visual únicamente): Recrear visualmente el gráfico de "Utilización de Salas" (barras) y "Tendencias de Reservas" (línea) sin necesidad de interactividad o datos dinámicos.
Links de Acción: Links como "Ver todo", "Verifique los detalles antes de 24h", "Ver todos las reservas", "Exportar Datos", "Reporte de uso", "Horario de Salas", "Métricas del sistema", "Modificar reserva", "Cancelar reserva" deben ser implementados como enlaces.
Consideraciones Técnicas:

HTML Semántico: Utiliza etiquetas HTML5 apropiadas (e.g., <header>, <nav>, <main>, <aside>, <footer>, <section>, <article>, <table>, <form>, <div>, <span>).
CSS Limpio y Organizado: Emplea CSS moderno. Se recomienda una estructura modular o bien organizada. Evita el uso de frameworks CSS (Bootstrap, Tailwind) a menos que se solicite explícitamente o sea imposible replicar la fidelidad sin ellos (lo cual dudo en este caso).
Flexbox/Grid: Haz uso extensivo de Flexbox y/o CSS Grid para la creación de layouts complejos y responsivos, replicando fielmente la disposición de los elementos.
Variables CSS: Considera el uso de variables CSS para colores y tipografías para facilitar la consistencia y el mantenimiento.
Comentarios: Incluye comentarios en el código HTML y CSS para explicar secciones complejas o decisiones de diseño.
No se requiere JavaScript para la funcionalidad dinámica: A menos que un requisito funcional implique una interacción compleja (como la validación avanzada de formularios o filtros dinámicos que no se pueden simular con solo CSS), concéntrate en la estructura y el estilo. Los "estados" como hover se pueden manejar con CSS.
El objetivo es una maqueta estática, de alta fidelidad visual y estructural, que simule la experiencia de usuario de las interfaces mostradas, respetando los requisitos funcionales que son visibles o implícitos en el diseño.
