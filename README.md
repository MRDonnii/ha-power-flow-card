# Power Flow Card

## Neutral mobile preview

![Neutral mobile preview of ha-power-flow-card](docs/preview.png)

> Rendered at 390 px mobile width with fictional Home Assistant entities and values. No private dashboard, person, address, camera, or sensor data is included.


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
