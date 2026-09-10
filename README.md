# Power Flow Card

Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-power-flow-card.js` til `/config/www/ha-power-flow-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-power-flow-card/ha-power-flow-card.js?v=0.4.0
```

Tilføj derefter korttypen `custom:ha-power-flow-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
