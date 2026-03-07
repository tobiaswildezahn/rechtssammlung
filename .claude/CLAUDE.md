# Rechtssammlung

Kuratierte Markdown-Sammlung deutscher Rechtstexte. Single Source of Truth fuer alle konvertierten Gesetze und Verordnungen.

## Struktur

```
grundgesetz/          GG
zivile-verteidigung/  KZV, ZSKG + Sicherstellungsgesetze (ASG, EnSiG, ESVG, VerkSiG, WasSiG, WiSiG, PostG, TKG)
kritis/               KRITIS-Dachgesetz, NIS2UmsuCG
gesundheit/           IfSG
hamburg/
  katastrophenschutz/ KatSchG, KatSO, FeuerwG, RettDG
  beamtenrecht/       BG, BeamtVG, BesG, DG, GleichstG, PersVG
  sonstige:           SOG, BeurtVO-Fw, Datenschutz-Anpassung
beamtenrecht-bund/    BBG, BeamtStG, AGG, ArbZG, BUrlG
parlamentaria/        Buergerschafts-Drucksachen
```

## Workflows

### Dokument lesen
Einfach die .md-Datei aus dem passenden Ordner lesen. Alle Texte sind bereits als Markdown aufbereitet.

### Neues Dokument hinzufuegen
1. PDF mit `lldr convert <pdf> -o /tmp/out` konvertieren
2. In passenden thematischen Ordner verschieben
3. README.md Index-Tabelle ergaenzen
4. Committen und pushen

### Dokument suchen
`grep -r "<Suchbegriff>" /Users/tobiaswildezahn/projekte/rechtssammlung/`

## Konventionen
- Dateinamen: `<Abkuerzung>_<Langname>.md`
- Hamburger Gesetze: Suffix `_HA` oder `_Hamburg`
- Neue Kategorien nur wenn >2 Dokumente eines Themas
- Bei Updates: altes Dokument ueberschreiben, nicht doppelt ablegen
