

## vite.config.ts Anpassung

Ich werde die `vite.config.ts` so ändern, dass alle Domains erlaubt sind:

### Aktuelle Konfiguration

```typescript
server: {
  host: "::",
  port: 8080,
},
```

### Neue Konfiguration

```typescript
server: {
  host: "::",
  port: 8080,
  allowedHosts: true,
},
```

### Was passiert

- `allowedHosts: true` erlaubt alle Domains (z.B. `insolvenz.frik-maxeiner.de`, `frik-maxeiner.de`, etc.)
- Der "Blocked request" Fehler wird nicht mehr auftreten
- Die Website ist über jede beliebige Domain erreichbar

### Datei

- `vite.config.ts` - Zeile 8-11 wird angepasst

