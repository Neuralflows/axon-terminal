# Changelog

For version 1.0 and later, see [Releases](https://github.com/Neuralflows/axon-terminal/releases).

The entries below are from the early versions and are in Spanish.

### v0.99.0 (2026-04-07)

- Terminal integrada con PowerShell/CMD real — Ctrl+`, el proceso sobrevive al abrir/cerrar
- Selector de shell: PowerShell Core, PowerShell o CMD sin reiniciar
- Reconexion automatica si el terminal muere
- Zen mode: oculta toda la UI salvo la conversacion
- Arbol de archivos mejorado: +N -N por archivo, heatmap de cambios, archivos ignorados atenuados
- Deteccion de version CLI: te avisa si Claude Code se actualizo entre sesiones
- 183 tests automatizados + CI Guardian en cada commit
- Los procesos ya no se acumulan al cerrar — shutdown graceful + limpieza de huerfanos
- OpenRouter con retry automatico para rate limits

### v0.9.0 (2026-03-30)

- Los checkpoints ya no ensucian tu historial git — snapshots comprimidos fuera de git
- Iconos en el arbol de archivos segun tipo
- CHANGELOG reconstruido desde el dia uno

### v0.8.0 (2026-03-30)

- Pop-outs que siguen el tab activo sin desconectarse
- Pestanas arrastrables, layout configurable, transparencia de ventana
- Telemetria arreglada, permisos simplificados, limpieza de codigo muerto

### v0.7.0 (2026-03-28)

- Pantalla de inicio rediseñada
- Wake word para dictado
- Nombres personalizables en el chat
- Opus 4.6 (1M) como opcion por defecto

### v0.6.0 (2026-03-27)

- Selector de effort level (Low/Medium/High/Max)
- Comandos mid-session: /model, /effort, /permissions, /editor
- Editor externo configurable
- Undo que preserva la conversacion

### v0.5.1 (2026-03-26)

- Checkpoints — vuelve atras si algo sale mal
- Reconexion automatica tras crash
- Historial agrupado por proyecto
- Exportar a Markdown

### v0.5.0 (2026-03-24)

- Multi-tab, busqueda en conversacion, atajos de teclado
- Notificaciones de escritorio, dictado por voz configurable
- Diff redimensionable

### v0.4.0 (2026-03-24)

- StatusLine con modelo, proyecto, rama, tokens, coste y duracion
- F11 fullscreen, PermissionDialog

### v0.3.0 (2026-03-23)

- Worktree opcional, historial de sesiones con resume
- Sistema de ayuda, temas centralizados, slash commands custom

### v0.2.0 (2026-03-21)

- Sistema de temas, panel toggles, sesiones pendientes, update checker

### v0.1.0 (2026-03-15)

- Release inicial

## Reportar bugs / Pedir features

Usa el [issue tracker](https://github.com/Neuralflows/axon-terminal/issues) de este repositorio.

## Licencia

Axon Terminal es software propietario. Consulta los [terminos de uso](https://terminal.neuralflow.es/terms) y la [politica de privacidad](https://terminal.neuralflow.es/privacy).

---

<p align="center">
  Hecho por <a href="https://neuralflow.es">Neuralflow</a>
</p>
