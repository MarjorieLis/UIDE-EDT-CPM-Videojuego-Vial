# Matriz de dependencias y ruta crítica

| Código | Actividad | Predecesores | Tipo | Duración (días) | Inicio | Fin | Holgura total | Crítica |
|---|---|---|---|---|---|---|---|---|
| 1.1.1 | Acta de constitución | - | - | 5 | 09/11/2026 | 13/11/2026 | 0 | Sí |
| 1.1.2 | Plan del proyecto | H0 | FS | 5 | 16/11/2026 | 20/11/2026 | 10 | No |
| 1.1.3 | Informe de cierre y lecciones aprendidas | H5 | FS | 5 | 12/04/2027 | 16/04/2027 | 0 | Sí |
| 1.2.1 | Informe comparativo de motores | H0 | FS | 5 | 16/11/2026 | 20/11/2026 | 0 | Sí |
| 1.2.2 | Especificación de requerimientos (SRS) | 1.2.1 | FS | 6 | 23/11/2026 | 30/11/2026 | 0 | Sí |
| 1.2.3 | Documento de diseño del juego (GDD) | 1.2.2+3 | SS | 7 | 26/11/2026 | 04/12/2026 | 0 | Sí |
| 1.3.1 | Escenario urbano 3D | H1 | FS | 10 | 07/12/2026 | 18/12/2026 | 0 | Sí |
| 1.3.2 | Nivel 1: señales de tránsito | 1.3.1 | FS | 10 | 04/01/2027 | 15/01/2027 | 0 | Sí |
| 1.3.3 | Nivel 2: semáforos y cruces peatonales | H2 | FS | 10 | 18/01/2027 | 29/01/2027 | 0 | Sí |
| 1.3.4 | Nivel 3: pasajero y ciclista | 1.3.3 | FS | 10 | 01/02/2027 | 16/02/2027 | 0 | Sí |
| 1.3.5 | Sistema de gamificación | 1.3.1+3 | SS | 15 | 10/12/2026 | 13/01/2027 | 2 | No |
| 1.3.6 | Interfaz y versión publicada | 1.3.4, 1.3.5 | FS | 3 | 17/02/2027 | 19/02/2027 | 0 | Sí |
| 1.4.1 | Instrumentos de evaluación | 1.2.3 | FS | 6 | 07/12/2026 | 14/12/2026 | 37 | No |
| 1.4.2 | Datos de las sesiones de prueba | H3, 1.4.1 | FS | 10 | 22/02/2027 | 05/03/2027 | 0 | Sí |
| 1.4.3 | Informe de pruebas | 1.4.2 | FS | 5 | 08/03/2027 | 12/03/2027 | 0 | Sí |
| 1.5.1 | Guía para docentes y padres | 1.3.6 | FS | 4 | 22/02/2027 | 25/02/2027 | 30 | No |
| 1.5.2 | Documento final del TIC | H4 | FS | 19 | 15/03/2027 | 09/04/2027 | 0 | Sí |
| 1.5.3 | Artículo científico | 1.5.2+5 | SS | 10 | 22/03/2027 | 05/04/2027 | 4 | No |
| H0 | H0 Acta firmada | 1.1.1 | FS | 0 | 13/11/2026 | 13/11/2026 | 0 | Sí |
| H1 | H1 Análisis cerrado | 1.1.2, 1.2.2, 1.2.3 | FS | 0 | 04/12/2026 | 04/12/2026 | 0 | Sí |
| H2 | H2 Versión alfa (nivel 1 con puntos) | 1.3.2, 1.3.5 | FS | 0 | 15/01/2027 | 15/01/2027 | 0 | Sí |
| H3 | H3 Versión beta publicada | 1.3.6 | FS | 0 | 19/02/2027 | 19/02/2027 | 0 | Sí |
| H4 | H4 Pruebas con usuarios cerradas | 1.4.3 | FS | 0 | 12/03/2027 | 12/03/2027 | 0 | Sí |
| H5 | H5 Entrega del TIC y artículo | 1.5.1, 1.5.2, 1.5.3 | FS | 0 | 09/04/2027 | 09/04/2027 | 0 | Sí |
| H6 | H6 Cierre del proyecto | 1.1.3 | FS | 0 | 16/04/2027 | 16/04/2027 | 0 | Sí |