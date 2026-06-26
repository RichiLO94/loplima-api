# AGENTS.md — ParaWays Mission Control

## Contexto humano

Rick es abogado y estratega. Aprende con analogías y ejecutando pasos concretos; no debe asumirse experiencia previa con Git, terminal, JavaScript, APIs o despliegues.

Paolo será operador tecnológico. El producto debe permitir que ambos trabajen con instrucciones naturales, estados claros y baja carga cognitiva.

## Método obligatorio

1. Antes de modificar código, explica en español qué entendiste, qué archivos revisarás, qué cambiarás, cómo se verificará y cómo se revierte.
2. Para tareas medianas o grandes, prepara primero un plan.
3. Haz cambios pequeños, reversibles y comprobables.
4. Después de cada cambio, ejecuta las verificaciones disponibles y explica el resultado sin jerga innecesaria.
5. Nunca ocultes errores: tradúcelos a lenguaje claro y propone el siguiente paso exacto.
6. Convierte las preferencias operativas o visuales de Rick en decisiones documentadas.
7. No pidas a Rick que escriba código salvo que sea imprescindible. Cuando deba ejecutar algo, entrega un solo bloque para copiar y explica el resultado esperado.

## Entorno seguro

- Este repositorio es un prototipo con información ficticia.
- No incorporar datos personales, documentos reales ni accesos de servicios externos.
- No registrar información privada en consola, pruebas o capturas.
- Las futuras configuraciones sensibles deberán permanecer fuera del código.
- No conectar servicios ni desplegar a producción sin autorización explícita de Rick.
- No enviar mensajes, crear clientes, reservar citas ni ejecutar operaciones financieras desde este prototipo.

## Producto

El objetivo es convertir instrucciones de Rick en misiones ejecutables para Paolo, con responsable, prioridad, fecha, resultado esperado, definición de terminado, checklist, criterio de escalamiento y aprobación humana cuando corresponda.

La experiencia debe sentirse como una empresa internacional de alta precisión, no como un tablero genérico de tareas.

## Arquitectura actual

- `index.html`: estructura de la interfaz.
- `styles.css`: sistema visual y responsividad.
- `app.js`: datos demo, renderizado, búsqueda, filtros, drag-and-drop, Mission Dispatcher local y persistencia en `localStorage`.
- `docs/`: contexto, prompts y roadmap.

No hay backend, autenticación ni integraciones reales en v0.1.

## Estándares de interfaz

- Español claro y profesional.
- Diseño sobrio, premium y legible.
- Compatible con escritorio y móvil.
- Controles con etiquetas comprensibles.
- Evitar pantallas saturadas y jerga de software.
- Mostrar la diferencia entre automatización, decisión de Paolo y decisión reservada a Rick.
- Todo dato de ejemplo debe ser claramente ficticio.

## Verificación mínima

- Ejecutar `npm install` si faltan dependencias de desarrollo.
- Ejecutar `npm run verify`.
- Abrir la aplicación localmente y comprobar carga, filtros, búsqueda, apertura de misión, creación desde una instrucción, movimiento entre columnas, restablecimiento de datos y vista móvil.
- Resumir archivos cambiados y forma de revertir.

## Decisiones de arquitectura

- No introducir nuevas tecnologías solamente por moda.
- Antes de añadir una dependencia, explicar qué problema resuelve y qué mantenimiento agrega.
- Una migración futura deberá preservar diseño, comportamiento y accesibilidad, e incluir pruebas.
- Mantener identificadores universales para misiones y casos.
- Diseñar futuras integraciones por eventos y con protección contra duplicados.

## Revisión

- Tratar como crítico cualquier dato privado incluido accidentalmente.
- No permitir autoenvío de opiniones jurídicas, promesas de resultado, cambios de precio o mensajes conflictivos.
- Revisar accesibilidad, errores de estado, pérdida de datos y acciones irreversibles.
