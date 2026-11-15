# Diccionario de la EDT

Proyecto: Videojuego educativo de educación vial en Roblox

Responsables: PM = Fabián Campoverde (Project Manager), PO = Marjorie Jiménez (Product Owner). Duración en días hábiles con 4 horas de trabajo por día.

## 1.1 Gestión del proyecto

### 1.1.1 Acta de constitución

| Campo | Detalle |
|---|---|
| Código | 1.1.1 |
| Entregable | Acta de constitución |
| Responsable | Fabián Campoverde (PM) |
| Duración | 5 días hábiles (20 h) |
| Fechas planificadas | 09/11/2026 a 13/11/2026 |
| Predecesores | Ninguno |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Documento que autoriza el proyecto. Recoge la justificación, los objetivos, el alcance con sus exclusiones, el presupuesto techo y los hitos H0 a H6. |
| Criterios de aceptación | Firmado por el Project Owner y el tutor. Lista los seis entregables E1 a E6 con sus exclusiones. |

### 1.1.2 Plan del proyecto

| Campo | Detalle |
|---|---|
| Código | 1.1.2 |
| Entregable | Plan del proyecto |
| Responsable | Fabián Campoverde (PM) |
| Duración | 5 días hábiles (20 h) |
| Fechas planificadas | 16/11/2026 a 20/11/2026 |
| Predecesores | H0 (FS) |
| Holgura total | 10 días |
| Descripción técnica | EDT, diccionario, matriz de dependencias, cronograma CPM en GanttProject y registro inicial de riesgos. |
| Criterios de aceptación | El archivo .gan abre sin errores, no tiene tareas huérfanas, muestra la ruta crítica y está en la carpeta /planificacion del repositorio. |

### 1.1.3 Informe de cierre y lecciones aprendidas

| Campo | Detalle |
|---|---|
| Código | 1.1.3 |
| Entregable | Informe de cierre y lecciones aprendidas |
| Responsable | Fabián Campoverde (PM) |
| Duración | 5 días hábiles (20 h) |
| Fechas planificadas | 12/04/2027 a 16/04/2027 |
| Predecesores | H5 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Informe que compara fechas y costos reales contra la línea base y recoge las lecciones aprendidas del equipo. |
| Criterios de aceptación | Cada hito H0 a H5 tiene su fecha real registrada. El acta de cierre está firmada por el Project Owner. |

## 1.2 Especificación del juego

### 1.2.1 Informe comparativo de motores

| Campo | Detalle |
|---|---|
| Código | 1.2.1 |
| Entregable | Informe comparativo de motores |
| Responsable | Fabián Campoverde (PM) |
| Duración | 5 días hábiles (20 h) |
| Fechas planificadas | 16/11/2026 a 20/11/2026 |
| Predecesores | H0 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Comparación de Roblox Studio con Unity y Godot según costo, curva de aprendizaje, acceso de los niños desde sus dispositivos y controles de seguridad infantil. |
| Criterios de aceptación | Matriz con al menos cinco criterios ponderados que justifica la elección de Roblox Studio. Aprobado por el tutor. |

### 1.2.2 Especificación de requerimientos (SRS)

| Campo | Detalle |
|---|---|
| Código | 1.2.2 |
| Entregable | Especificación de requerimientos (SRS) |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 6 días hábiles (24 h) |
| Fechas planificadas | 23/11/2026 a 30/11/2026 |
| Predecesores | 1.2.1 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Requerimientos funcionales y no funcionales del juego escritos como historias de usuario con prioridad. El contenido vial se toma del RTE INEN 004-1:2011. |
| Criterios de aceptación | Cada requerimiento tiene un identificador y al menos un caso de prueba. El tutor lo aprueba antes del hito H1. |

### 1.2.3 Documento de diseño del juego (GDD)

| Campo | Detalle |
|---|---|
| Código | 1.2.3 |
| Entregable | Documento de diseño del juego (GDD) |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 7 días hábiles (28 h) |
| Fechas planificadas | 26/11/2026 a 04/12/2026 |
| Predecesores | 1.2.2 (SS+3) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Narrativa, mecánicas de los tres niveles, reglas de puntos e insignias, condición para desbloquear cada nivel y bocetos de pantallas. |
| Criterios de aceptación | Cada nivel tiene objetivo de aprendizaje, condición de victoria y tabla de puntos. Cada mecánica se puede rastrear hasta un requerimiento del SRS. |

## 1.3 Videojuego en Roblox

### 1.3.1 Escenario urbano 3D

| Campo | Detalle |
|---|---|
| Código | 1.3.1 |
| Entregable | Escenario urbano 3D |
| Responsable | Fabián Campoverde (PM) |
| Duración | 10 días hábiles (40 h) |
| Fechas planificadas | 07/12/2026 a 18/12/2026 |
| Predecesores | H1 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Mapa de una ciudad en Roblox Studio con calles, aceras, pasos cebra, semáforos y señales modeladas según la norma INEN. |
| Criterios de aceptación | Contiene todas las señales y cruces que pide el GDD. Se recorre completo sin fallas de colisión ni errores en la consola de salida. |

### 1.3.2 Nivel 1: señales de tránsito

| Campo | Detalle |
|---|---|
| Código | 1.3.2 |
| Entregable | Nivel 1: señales de tránsito |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 10 días hábiles (40 h) |
| Fechas planificadas | 04/01/2027 a 15/01/2027 |
| Predecesores | 1.3.1 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Recorrido donde el niño reconoce señales reglamentarias, preventivas e informativas y responde preguntas con retroalimentación inmediata. |
| Criterios de aceptación | Incluye al menos 10 señales de la norma. Cada respuesta suma o resta puntos según el GDD. Se completa sin errores de script. |

### 1.3.3 Nivel 2: semáforos y cruces peatonales

| Campo | Detalle |
|---|---|
| Código | 1.3.3 |
| Entregable | Nivel 2: semáforos y cruces peatonales |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 10 días hábiles (40 h) |
| Fechas planificadas | 18/01/2027 a 29/01/2027 |
| Predecesores | H2 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Escenarios para cruzar la calle respetando el semáforo peatonal y vehicular y usando el paso cebra. |
| Criterios de aceptación | El semáforo cumple el ciclo definido en el GDD. Cruzar en rojo descuenta puntos y muestra un mensaje. Pasa los casos de prueba del SRS. |

### 1.3.4 Nivel 3: pasajero y ciclista

| Campo | Detalle |
|---|---|
| Código | 1.3.4 |
| Entregable | Nivel 3: pasajero y ciclista |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 10 días hábiles (40 h) |
| Fechas planificadas | 01/02/2027 a 16/02/2027 |
| Predecesores | 1.3.3 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Situaciones donde el niño viaja como pasajero (cinturón, asiento trasero) o como ciclista (casco, carril, señales con el brazo). |
| Criterios de aceptación | Tiene al menos seis situaciones con retroalimentación en cada error. Solo se desbloquea al aprobar el nivel 2. |

### 1.3.5 Sistema de gamificación

| Campo | Detalle |
|---|---|
| Código | 1.3.5 |
| Entregable | Sistema de gamificación |
| Responsable | Fabián Campoverde (PM) |
| Duración | 15 días hábiles (60 h) |
| Fechas planificadas | 10/12/2026 a 13/01/2027 |
| Predecesores | 1.3.1 (SS+3) |
| Holgura total | 2 días |
| Descripción técnica | Scripts en Luau para puntos, insignias, niveles y barra de progreso. El avance se guarda con DataStoreService. |
| Criterios de aceptación | El progreso se mantiene al salir y volver a entrar. Hay al menos tres insignias. Las pruebas de escritorio quedan documentadas en el repositorio. |

### 1.3.6 Interfaz y versión publicada

| Campo | Detalle |
|---|---|
| Código | 1.3.6 |
| Entregable | Interfaz y versión publicada |
| Responsable | Fabián Campoverde (PM) |
| Duración | 3 días hábiles (12 h) |
| Fechas planificadas | 17/02/2027 a 19/02/2027 |
| Predecesores | 1.3.4 (FS), 1.3.5 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Menús, marcador de puntos en pantalla, ajustes de privacidad y publicación de la experiencia en Roblox. |
| Criterios de aceptación | El enlace público funciona, el chat está desactivado, no hay compras dentro del juego y la versión queda etiquetada en GitHub como v1.0-beta. |

## 1.4 Resultados de validación

### 1.4.1 Instrumentos de evaluación

| Campo | Detalle |
|---|---|
| Código | 1.4.1 |
| Entregable | Instrumentos de evaluación |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 6 días hábiles (24 h) |
| Fechas planificadas | 07/12/2026 a 14/12/2026 |
| Predecesores | 1.2.3 (FS) |
| Holgura total | 37 días |
| Descripción técnica | Prueba previa y posterior de conocimientos viales, cuestionario SUS adaptado para niños y consentimiento informado para padres. |
| Criterios de aceptación | El tutor valida los tres instrumentos. Las pruebas previa y posterior tienen las mismas preguntas en distinto orden. |

### 1.4.2 Datos de las sesiones de prueba

| Campo | Detalle |
|---|---|
| Código | 1.4.2 |
| Entregable | Datos de las sesiones de prueba |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 10 días hábiles (40 h) |
| Fechas planificadas | 22/02/2027 a 05/03/2027 |
| Predecesores | H3 (FS), 1.4.1 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Sesiones con niños en una escuela: prueba previa, juego, prueba posterior y cuestionario SUS. |
| Criterios de aceptación | Hay consentimiento firmado de todos los participantes. Los datos quedan anonimizados en una hoja de cálculo con un código por niño. |

### 1.4.3 Informe de pruebas

| Campo | Detalle |
|---|---|
| Código | 1.4.3 |
| Entregable | Informe de pruebas |
| Responsable | Fabián Campoverde (PM) |
| Duración | 5 días hábiles (20 h) |
| Fechas planificadas | 08/03/2027 a 12/03/2027 |
| Predecesores | 1.4.2 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Análisis de la diferencia entre prueba previa y posterior, del puntaje SUS y del porcentaje de niños que completa los tres niveles. |
| Criterios de aceptación | Reporta si se cumplieron las metas del acta: mejora de al menos 20 puntos porcentuales y al menos 80 % de niños que completan los tres niveles. |

## 1.5 Documentación final

### 1.5.1 Guía para docentes y padres

| Campo | Detalle |
|---|---|
| Código | 1.5.1 |
| Entregable | Guía para docentes y padres |
| Responsable | Marjorie Jiménez (PO) |
| Duración | 4 días hábiles (16 h) |
| Fechas planificadas | 22/02/2027 a 25/02/2027 |
| Predecesores | 1.3.6 (FS) |
| Holgura total | 30 días |
| Descripción técnica | Guía corta para que docentes y padres abran el juego, configuren la cuenta del niño y acompañen cada nivel. |
| Criterios de aceptación | Tiene máximo ocho páginas en PDF. Un docente la sigue sin ayuda y logra iniciar el juego. |

### 1.5.2 Documento final del TIC

| Campo | Detalle |
|---|---|
| Código | 1.5.2 |
| Entregable | Documento final del TIC |
| Responsable | Fabián Campoverde (PM) |
| Duración | 19 días hábiles (76 h) |
| Fechas planificadas | 15/03/2027 a 09/04/2027 |
| Predecesores | H4 (FS) |
| Holgura total | 0 días (ruta crítica) |
| Descripción técnica | Documento del Trabajo de Integración Curricular con sus cinco capítulos, según la plantilla de la UIDE y en APA 7. |
| Criterios de aceptación | Aprobado por el tutor y con un informe de similitud por debajo del límite que fija la universidad. |

### 1.5.3 Artículo científico

| Campo | Detalle |
|---|---|
| Código | 1.5.3 |
| Entregable | Artículo científico |
| Responsable | Fabián Campoverde (PM) |
| Duración | 10 días hábiles (40 h) |
| Fechas planificadas | 22/03/2027 a 05/04/2027 |
| Predecesores | 1.5.2 (SS+5) |
| Holgura total | 4 días |
| Descripción técnica | Artículo científico con el problema, el desarrollo del juego y los resultados de las pruebas con niños. |
| Criterios de aceptación | Sigue la plantilla de la revista elegida y el tutor autoriza su envío. |
