# Robot Educador

Asistente de aula sobre Raspberry Pi que observa cómo el grupo presta atención y participa, sin reconocimiento facial y sin guardar imágenes (identificación por asiento). Al final de la clase entrega un reporte al docente y sugiere material de refuerzo.

Funciones previstas: comandos de voz del docente, marcado de temas, votación con manos, cola de participación, alertas y dashboard en el celular del docente.

## Organización del repo

- `docs/` — plan de trabajo (`PLAN.md`, en la raíz) y decisiones técnicas pendientes (`docs/DECISIONES_PENDIENTES.md`).
- `hardware/` — especificaciones y mediciones de rendimiento del hardware disponible.
- `codigo/` — código fuente, organizado por área funcional: `vision/`, `voz/`, `datos/`, `dashboard/`, `reportes/`.
- `scripts/` — scripts de apoyo (instalación, utilidades).
- `tests/` — pruebas del proyecto.
- `config/` — archivos de configuración.

Este repositorio es solo técnico. La investigación, entrevistas y entregas al área de negocio del concurso se manejan fuera del repo.

## Cómo se trabaja

El trabajo se organiza en issues, agrupados por milestone, y se sigue en el tablero de GitHub Projects del repo. Cada issue técnico es una pieza que se programa y se prueba sola en la Raspberry Pi, una por una.

## Fecha límite

Concurso: Oaxaca Emprende Interuniversitario 2027, categoría Innovación, Tecnología y Finanzas. Fecha límite interna del equipo técnico: PMV funcionando el **6 de diciembre de 2026**. Del 7 al 11 de diciembre: ajustes finos.
