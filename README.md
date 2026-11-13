# Plugin de Reeliza para Claude Code

Skills con el prefijo `reeliza:` para que no choquen con las de otros plugins.

- `/reeliza:audita-script <id>`: audita un guion bloque por bloque con tu voz y guarda la versión final.
- `/reeliza:contenido`: carruseles y guiones sobre tu estrategia y calendario, con la marca de tu kit local.

Necesita la conexión MCP de Reeliza (Reeliza → Cuenta → «Conexión con Claude», copiar el comando `claude mcp add`).

## Instalar

```
claude plugin marketplace add NestorSegura/reeliza-plugin
claude plugin install reeliza@reeliza
```
