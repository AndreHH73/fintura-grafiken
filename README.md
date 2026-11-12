# fintura-grafiken

Beitragsgrafiken für die Social-Media-Kanäle von Fintura Finance.

Das Repository dient als Bildablage: Die Dateien werden von Buffer über ihre
Rohdaten-Adresse geladen und von dort an LinkedIn, Instagram und Facebook
weitergereicht. Die Adressen sind dauerhaft und ändern sich nicht.

## Aufbau

```
shift/          Beitragsgrafiken zu SHIFT
partcon/        PartCon Plus
4futurefamily/  4futurefamily
```

## Dateinamen

```
JJJJ-MM-TT-thema-format.png
```

- `JJJJ-MM-TT` – Veröffentlichungsdatum, sortiert chronologisch
- `thema` – Kurzform des Beitragsthemas
- `format` – `li` für LinkedIn und Facebook (1200 × 1200),
  `ig` für Instagram (1080 × 1350)

Beispiel: `shift/2026-11-13-crm-li.png`

## Adresse einer Datei

```
https://raw.githubusercontent.com/AndreHH73/fintura-grafiken/main/<pfad>
```

## Gestaltung

Dunkelblauer Farbverlauf, Lora für Überschriften, Liberation Sans für
Beschriftungen, Akzentfarbe Himmelblau. Unten die Wortmarke und der Claim
„Übergaben steuern. Umsatzpotenziale nutzen."

Die Grafiken werden mit Python und Pillow erzeugt, in dreifacher Auflösung
gerendert und auf 1200 × 1200 herunterskaliert.
