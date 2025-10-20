# Presentación: Creación de proyectos KNX en ETS5

---

## 1. Bienvenida
- Presentar el objetivo de la sesión: aprender a desarrollar proyectos KNX con ETS5.
- Repasar agenda: fundamentos KNX, entorno ETS5, flujo de trabajo y mejores prácticas.

---

## 2. Objetivos de aprendizaje
- Comprender la arquitectura y topología básica de un sistema KNX.
- Configurar un nuevo proyecto en ETS5 desde cero.
- Realizar programación de grupos, parámetros y descarga en dispositivos.
- Implementar estrategias de documentación, pruebas y mantenimiento.

---

## 3. Fundamentos de KNX
- Estándar abierto para automatización de edificios (ISO/IEC 14543).
- Topologías: línea, área, backbone; límites de dispositivos y cableado.
- Medios de comunicación: TP, RF, IP, Powerline.
- Roles en el proyecto: integrador, instalador, usuario final.

---

## 4. Flujo general de un proyecto KNX
1. Análisis de requisitos del cliente.
2. Diseño funcional y selección de equipos.
3. Configuración en ETS5 y programación de dispositivos.
4. Puesta en marcha, pruebas y entrega.

---

## 5. Conociendo ETS5
- Componentes principales: Vista de Proyecto, Catálogo, Topología, Edición de Grupos.
- Licencias y dongle: modos Demo, Lite, Professional.
- Organización del entorno de trabajo y opciones básicas.

---

## 6. Creación de un proyecto nuevo
- Abrir ETS5 y seleccionar **Nuevo Proyecto**.
- Definir nombre, descripción y versión.
- Ajustar idioma, unidades y opciones regionales.
- Guardar proyecto y activar modo de edición.

---

## 7. Construcción de la topología
- Añadir áreas, líneas y dispositivos (importación ETS App o catálogos).
- Configurar direcciones individuales (AAA.LL.DD) evitando conflictos.
- Registrar información física: ubicación, tablero, circuito.
- Sincronizar topología con la instalación física.

---

## 8. Configuración de grupos y canales
- Crear grupos principales (iluminación, climatización, persianas, etc.).
- Definir subgrupos por zona/función y asignar direcciones de grupo (x/y/z).
- Asociar canales de dispositivos a las direcciones de grupo.
- Utilizar comentarios y colores para facilitar la lectura.

---

## 9. Parametrización de dispositivos
- Abrir la pestaña de parámetros de cada dispositivo.
- Ajustar tipos de pulsadores, temporizadores, escenas, lógica.
- Usar plantillas y copiar/pegar parámetros entre canales similares.
- Validar la compatibilidad de objetos de comunicación (tipo de dato DPT).

---

## 10. Descarga y pruebas
- Conectar interfaz KNX (USB/IP) y realizar **Programación individual** y **de aplicaciones**.
- Monitor de bus: ver telegramas, comprobar estados, diagnosticar errores.
- Probar funciones: iluminación, persianas, sensores, climatización.
- Documentar resultados y ajustar parámetros según feedback.

---

## 11. Documentación y mantenimiento
- Generar reportes automáticos desde ETS5 (topología, grupos, lista de materiales).
- Exportar proyecto (.knxproj) y mantener control de versiones.
- Planificar mantenimiento preventivo y actualizaciones.
- Capacitar al usuario final y entregar manuales simplificados.

---

## 12. Buenas prácticas y recursos
- Diseñar con modularidad y escalabilidad (zonas, escenas, funciones).
- Etiquetar cables, actuadores y pulsadores en campo.
- Usar el ETS App Store para complementos útiles (Device Templates, Project Tracing).
- Recursos recomendados: documentación KNX Association, foros KNX User Club, cursos certificados.

---

## 13. Actividad práctica sugerida
- Crear un proyecto demo: vivienda con sala, cocina, dormitorio y baño.
- Integrar iluminación regulable, persianas automatizadas y sensor de presencia.
- Configurar escenas "Llegada" y "Salir".
- Descargar en un banco de pruebas o simulador ETS5.

---

## 14. Cierre y próximos pasos
- Resolver dudas de los estudiantes.
- Proponer tareas: ampliar el proyecto con climatización y medición de energía.
- Presentar certificaciones KNX Partner y recursos de formación continua.
- Recoger retroalimentación sobre la sesión.

---

## Anexos (opcional)
- Checklist de verificación antes de la puesta en marcha.
- Plantilla de informe de pruebas.
- Lista de atajos de teclado útiles en ETS5.

