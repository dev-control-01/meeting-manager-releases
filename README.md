# Meeting Manager — Releases

Installer pubblici per Meeting Manager desktop app.

> Il codice sorgente è in un repository privato separato. Questo repo distribuisce esclusivamente i binari compilati.

---

## Download

Scarica l'installer dalla sezione [Releases](https://github.com/dev-control-01/meeting-manager-releases/releases/latest).

| Piattaforma | File |
|---|---|
| macOS (Apple Silicon) | `Meeting Manager-X.X.X-arm64.dmg` |
| macOS (Intel) | `Meeting Manager-X.X.X.dmg` |
| Windows | vedi release |

### macOS — primo avvio (app non firmata)

```bash
xattr -cr /Applications/Meeting\ Manager.app
```

---

## latest-version.json

Il file [`latest-version.json`](./latest-version.json) è letto dall'app per rilevare aggiornamenti disponibili.
Le versioni ≥ 5.3.3 leggono da questo repo. Le versioni ≤ 5.3.2 usano `dev-control-01/latest-version.json` (aggiornato in dual-write ad ogni release).
