# ParaWays Mission Control — prototipo v0.1

Primer artefacto tangible de **ParaWays OS**: un centro de mando visual para convertir instrucciones de Rick en misiones claras para Paolo.

## Qué puedes probar ahora

- Cambiar entre la vista de Rick y la de Paolo.
- Buscar misiones, clientes o casos ficticios.
- Filtrar por responsable.
- Abrir una misión y revisar su definición de terminado.
- Arrastrar misiones entre estados.
- Escribir una instrucción natural y convertirla en una misión estructurada.
- Restablecer la demo.

## Seguridad

Este repositorio contiene exclusivamente información ficticia y no usa credenciales ni conectores. **No cargues datos reales de clientes mientras el repositorio siga siendo público.** Antes de incorporar integraciones, debes convertirlo en privado y revisar permisos.

## Abrir la demo sin instalar nada

Puedes abrir `index.html` directamente en el navegador. Para una experiencia más consistente, usa un servidor local:

```bash
python -m http.server 4173
```

Luego abre:

```text
http://localhost:4173
```

## Verificación rápida

```bash
npm install
npm run verify
```

La aplicación funciona sin instalar paquetes; `npm install` se usa únicamente para ejecutar la prueba automática.

## Cómo trabajar con Codex

1. Instala la aplicación de Codex.
2. Clona o descarga este repositorio.
3. Abre la carpeta del proyecto en Codex.
4. Pide primero: `Lee AGENTS.md y docs/START-HERE.md. No cambies nada todavía. Explícame el proyecto con una analogía visual y dime cómo abrir la demo.`
5. Continúa con los prompts de `docs/PROMPTS-CODEX.md`.

## Estructura

```text
.
├── AGENTS.md
├── README.md
├── index.html
├── styles.css
├── app.js
├── package.json
├── package-lock.json
├── tests
│   └── smoke.cjs
└── docs
    ├── START-HERE.md
    ├── PROMPTS-CODEX.md
    ├── PRODUCT-BRIEF.md
    └── ROADMAP.md
```

## Estado

- [x] Prototipo visual y navegable.
- [x] Mission Dispatcher local basado en reglas.
- [x] Persistencia local.
- [x] Prueba funcional automatizada.
- [x] Instrucciones permanentes para Codex.
- [ ] Repositorio privado.
- [ ] Autenticación de Rick y Paolo.
- [ ] Backend.
- [ ] Notion.
- [ ] Kommo/WhatsApp.
- [ ] Microsoft 365/SharePoint.
- [ ] Slack.
- [ ] IA real y evaluaciones.
