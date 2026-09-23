# Plan del proyecto — Robot Educador

Repositorio solo técnico. Investigación, entrevistas y entregas al área de negocio se manejan fuera del repo.

## Estructura de carpetas

```
robot-educador/
├── README.md
├── PLAN.md
├── docs/
│   ├── README.md
│   └── DECISIONES_PENDIENTES.md
├── hardware/
│   ├── README.md
│   ├── especificaciones/README.md
│   └── rendimiento-hardware/README.md
├── codigo/
│   ├── README.md
│   ├── vision/README.md
│   ├── voz/README.md
│   ├── datos/README.md
│   ├── dashboard/README.md
│   └── reportes/README.md
├── scripts/README.md
├── tests/README.md
└── config/README.md
```

## Etiquetas

- Área: `vision`, `voz`, `datos`, `dashboard`, `reportes`, `hardware`, `arranque`
- Tipo: `investigar`, `construir`, `validar`, `decidir`

## Milestones

| Milestone | Fechas | Foco |
|---|---|---|
| M0 · Arranque | 2026-09-23 → 2026-09-30 | Accesos, Student Pack, SSH, instalación de la Pi |
| M1 · Bases y piezas aisladas | 2026-10-01 → 2026-10-21 | Captura de audio/video, identificación por asiento, rendimiento de la Pi |
| M2 · Construcción de piezas funcionales | 2026-10-22 → 2026-11-11 | Comandos de voz, votación, cola, atención por asiento, dashboard, alertas |
| M3 · Integración y primera validación | 2026-11-12 → 2026-11-25 | Flujo de clase completo, reporte de fin de clase, prueba piloto |
| M4 · PMV funcionando (fecha límite interna) | 2026-11-26 → 2026-12-06 | PMV de principio a fin, validación en salón real |
| M5 · Ajustes finos | 2026-12-07 → 2026-12-11 | Ajustes según validación |

## Issues por milestone

**M0 · Arranque**
1. Obtención del GitHub Student Pack para el compañero — `arranque` `construir`
2. Acceso del compañero al repositorio y al tablero de GitHub Projects — `arranque` `construir`
3. Conexión por SSH a la Raspberry Pi con Termius — `arranque` `construir`
4. Instalación del sistema operativo en la Raspberry Pi — `hardware` `construir`

**M1 · Bases y piezas aisladas**
5. Captura de audio del docente en el salón — `voz` `construir`
6. Captura de video de las dos webcams y cobertura del salón — `vision` `construir`
7. Esquema de identificación por asiento sin reconocimiento facial ni imágenes guardadas — `vision` `datos` `construir`
8. Medición del rendimiento de la Raspberry Pi 4 con el hardware disponible — `hardware` `investigar`
9. Asignación de alumnos a asientos y cambios de lugar — `vision` `datos` `construir`

**M2 · Construcción de piezas funcionales**
10. Reconocimiento de comandos de voz predefinidos del docente — `voz` `construir`
11. Marcado de temas de clase durante la sesión — `voz` `dashboard` `construir`
12. Detección de manos levantadas para votación — `vision` `construir`
13. Cola de participación — `vision` `construir`
14. Detección de señales de atención por asiento (función principal del proyecto) — `vision` `construir`
15. Registro de eventos de atención y participación por asiento — `datos` `construir`
16. Boceto funcional del dashboard en el celular del docente — `dashboard` `construir`
17. Alertas de caída de atención — `dashboard` `construir`
18. Respuesta hablada del robot (resultados de votación, avisos) — `voz` `construir`

**M3 · Integración y primera validación**
19. Integración de voz, visión y datos en un flujo de clase completo — `vision` `voz` `datos` `construir`
20. Reporte de fin de clase con resumen de atención y participación — `reportes` `construir`
21. Sugerencia de material de refuerzo en el reporte de fin de clase — `reportes` `construir`
22. Prueba piloto en un salón real con el PMV parcial — `validar`

**M4 · PMV funcionando**
23. PMV funcionando de principio a fin en la Raspberry Pi, incluida una demo para el video pitch — `validar`
24. Validación del PMV en un salón de clase real — `validar`

**M5 · Ajustes finos**
25. Ajustes finos del PMV según resultados de la validación — `validar` `construir`

## Decisiones pendientes

Ver [`docs/DECISIONES_PENDIENTES.md`](docs/DECISIONES_PENDIENTES.md).
