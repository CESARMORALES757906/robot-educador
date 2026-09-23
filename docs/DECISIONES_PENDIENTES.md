# Decisiones pendientes

Cada punto es una pregunta abierta. No se recomienda ninguna opción aquí; se decide cuando haya suficiente información.

---

### 1. Método/librería de visión por computadora para detectar postura y señales de atención
- **Opciones conocidas:** por definir según la investigación de licencias (fuera del repo) y el rendimiento medido en la Pi.
- **Falta:** resultado de la investigación de licencias (punto 2) y de la medición de rendimiento (issue 8).
- **Issue relacionado:** 8, 14.

### 2. Licencias de las opciones de visión por computadora (open source vs YOLO)
- **Opciones conocidas:** YOLO, otras alternativas open source.
- **Falta:** la investigación de licencias, que se hace fuera del repo.
- **Issue relacionado:** ninguno en este repo (depende de investigación externa).

### 3. Motor o librería de reconocimiento de voz para los comandos del docente
- **Opciones conocidas:** por definir.
- **Falta:** resultado de la medición de rendimiento de la Pi.
- **Issue relacionado:** 8, 10.

### 4. Cómo y dónde se guardan los datos de asiento, atención y participación (sin imágenes)
- **Opciones conocidas:** por definir (archivo local, base de datos local, etc.).
- **Falta:** volumen de datos esperado por clase y necesidades del dashboard/reporte.
- **Issue relacionado:** 7, 9, 15.

### 5. Tecnología del dashboard en el celular del docente y cómo se conecta a la Pi
- **Opciones conocidas:** por definir (app, web responsiva, notificaciones, red local, etc.).
- **Falta:** condiciones reales del salón (conectividad disponible).
- **Issue relacionado:** 16.

### 6. Distribución específica de Raspberry Pi OS y su configuración base
- **Opciones conocidas:** por definir.
- **Falta:** resultado de la medición de rendimiento.
- **Issue relacionado:** 4, 8.

### 7. Cómo se marca un tema de clase: por voz, por el dashboard, o ambos
- **Opciones conocidas:** comando de voz, acción en el dashboard, ambos.
- **Falta:** probar ambas piezas por separado y ver cuál es más práctica en clase.
- **Issue relacionado:** 11.

### 8. Formato del reporte de fin de clase y fuente de las sugerencias de material de refuerzo
- **Opciones conocidas:** por definir.
- **Falta:** cómo se estructurará el dashboard y de dónde saldrá el material sugerido.
- **Issue relacionado:** 20, 21.

### 9. Cómo se coordinan las dos webcams para cubrir el salón sin duplicar detecciones de una misma persona
- **Opciones conocidas:** por definir.
- **Falta:** medición del campo visual real de las cámaras en un salón.
- **Issue relacionado:** 6.

### 10. Qué señales de atención se miden y con qué umbrales
- **Opciones conocidas:** por definir.
- **Falta:** criterio validado de qué cuenta como atención/desatención observable.
- **Issue relacionado:** 14.

### 11. Canal de las alertas de caída de atención
- **Opciones conocidas:** voz del robot, dashboard, ambos.
- **Falta:** probar ambos canales y ver cuál es más útil sin interrumpir la clase.
- **Issue relacionado:** 17.

### 12. Criterio de la cola de participación
- **Opciones conocidas:** orden de llegada de la mano levantada, aleatorio, otro.
- **Falta:** decidir qué criterio es justo y fácil de implementar.
- **Issue relacionado:** 13.
