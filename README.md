# Rechtssammlung

Kuratierte Sammlung deutscher Rechtstexte als Markdown. Schwerpunkte: Zivile Verteidigung, Kritische Infrastrukturen, Katastrophenschutz Hamburg, Beamtenrecht.

Konvertiert aus PDF mit [lldr](https://github.com/tobiaswildezahn/law-loader) (`pip install git+https://github.com/tobiaswildezahn/law-loader.git`).

## Inhalt

### Grundgesetz

| Datei | Dokument |
|-------|----------|
| `grundgesetz/GG.md` | Grundgesetz |

### Zivile Verteidigung

| Datei | Dokument |
|-------|----------|
| `zivile-verteidigung/BBKG_BBK-Errichtungsgesetz.md` | BBK-Errichtungsgesetz |
| `zivile-verteidigung/KZV.md` | Konzeption Zivile Verteidigung |
| `zivile-verteidigung/THWG_THW-Gesetz.md` | THW-Gesetz |
| `zivile-verteidigung/ZSKG_Zivilschutzgesetz.md` | Zivilschutzgesetz |
| `zivile-verteidigung/resilienz-katastrophen.md` | Deutsche Strategie zur Stärkung der Resilienz gegenüber Katastrophen |

#### Sicherstellungsgesetze

| Datei | Dokument |
|-------|----------|
| `zivile-verteidigung/sicherstellungsgesetze/ASG_Arbeitssicherstellungsgesetz.md` | Arbeitssicherstellungsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/ESVG_Ernaehrungssicherstellungsgesetz.md` | Ernährungssicherstellungsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/EltSV_Elektrizitaetssicherungsverordnung.md` | Elektrizitätssicherungsverordnung |
| `zivile-verteidigung/sicherstellungsgesetze/EnSiG_Energiesicherungsgesetz.md` | Energiesicherungsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/GasSV_Gassicherungsverordnung.md` | Gassicherungsverordnung |
| `zivile-verteidigung/sicherstellungsgesetze/PostG_Postgesetz_inkl_Sicherstellung.md` | Postgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/TKG_Telekommunikationsgesetz.md` | Telekommunikationsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/VerkLG_Verkehrsleistungsgesetz.md` | Verkehrsleistungsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/VerkSiG_Verkehrssicherstellungsgesetz.md` | Verkehrssicherstellungsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/WasSiG_Wassersicherstellungsgesetz.md` | Wassersicherstellungsgesetz |
| `zivile-verteidigung/sicherstellungsgesetze/WiSiG_Wirtschaftssicherstellungsgesetz.md` | Wirtschaftssicherstellungsgesetz |

### Kritische Infrastrukturen

| Datei | Dokument |
|-------|----------|
| `kritis/BSIG_BSI-Gesetz.md` | BSI-Gesetz |
| `kritis/KRITIS-Dachgesetz_BT-Drucksache.md` | KRITIS-Dachgesetz |
| `kritis/NIS2UmsuCG_Bundesgesetzblatt.md` | NIS-2-Umsetzungsgesetz |

### Gesundheit

| Datei | Dokument |
|-------|----------|
| `gesundheit/IfSG_Infektionsschutzgesetz.md` | Infektionsschutzgesetz |

### Hamburg

#### Katastrophenschutz

| Datei | Dokument |
|-------|----------|
| `hamburg/katastrophenschutz/FeuerwG_HA.md` | FeuerwG HA |
| `hamburg/katastrophenschutz/KatSO_Hamburg.md` | Katastrophenschutzordnung Hamburg |
| `hamburg/katastrophenschutz/KatSchG_HA.md` | HmbKatSG |
| `hamburg/katastrophenschutz/RettDG_HA_2019.md` | HmbRettDG |

#### Beamtenrecht

| Datei | Dokument |
|-------|----------|
| `hamburg/beamtenrecht/BG_HA_2009.md` | HmbBG |
| `hamburg/beamtenrecht/BeamtVG_HA.md` | HmbBeamtVG |
| `hamburg/beamtenrecht/BesG_HA_2010.md` | HmbBesG |
| `hamburg/beamtenrecht/DG_HA.md` | HmbDG |
| `hamburg/beamtenrecht/GleichstG_HA_2015.md` | HmbGleichstG |
| `hamburg/beamtenrecht/HmbSUrlR_Sonderurlaubsrichtlinien.md` | Sonderurlaubsrichtlinien |
| `hamburg/beamtenrecht/PersVG_HA_2014.md` | HmbPersVG |

#### Sonstige Hamburg

| Datei | Dokument |
|-------|----------|
| `hamburg/BeurtVO-Fw.md` | Beurteilungsverordnung Feuerwehr |
| `hamburg/SOG_HA.md` | HmbSOG |
| `hamburg/datenschutz-anpassung/21_12396_datenschutz_anpassung_katsg_fwg_rdg.md` | 12396 datenschutz anpassung katsg fwg rdg |

### Beamtenrecht Bund

| Datei | Dokument |
|-------|----------|
| `beamtenrecht-bund/AGG.md` | Allgemeines Gleichbehandlungsgesetz |
| `beamtenrecht-bund/ArbZG.md` | Arbeitszeitgesetz |
| `beamtenrecht-bund/BBG.md` | Bundesbeamtengesetz |
| `beamtenrecht-bund/BUrlG.md` | Bundesurlaubsgesetz |
| `beamtenrecht-bund/BeamtStG.md` | Beamtenstatusgesetz |

### Parlamentaria

| Datei | Dokument |
|-------|----------|
| `parlamentaria/21_16376_entwurf_rettungsdienstgesetz.md` | 16376 entwurf rettungsdienstgesetz |
| `parlamentaria/23_03256_notfallversorgung_in_der_krise_ii.md` | Schriftliche Kleine Anfrage |
| `parlamentaria/Drs_22-16268_Bevoelkerungsschutz.md` | 22-16268 Bevoelkerungsschutz |

## Querverweise

Automatisch erkannte Referenzen zwischen Dokumenten (`lldr crossref`). Maschinenlesbar in `index.json`.

```mermaid
graph LR
    NIS2UmsuCG["NIS2UmsuCG"]
    BSIG["BSIG"]
    NIS2UmsuCG -->|173x| BSIG
    BG["BG"]
    BeamtStG["BeamtStG"]
    BG -->|75x| BeamtStG
    IfSG["IfSG"]
    GG["GG"]
    IfSG -->|39x| GG
    KRITIS_Dachgesetz["KRITIS-Dachgesetz"]
    KRITIS_Dachgesetz -->|30x| BSIG
    BeamtVG["BeamtVG"]
    BeamtVG -->|28x| BG
    RettDG_Entwurf["RettDG-Entwurf"]
    RettDG["RettDG"]
    RettDG_Entwurf -->|25x| RettDG
    BeamtVG -->|22x| BeamtStG
    DG["DG"]
    DG -->|17x| BG
    TKG["TKG"]
    TKG -->|16x| BSIG
    BesG["BesG"]
    BeamtVG -->|15x| BesG
    BeurtVO_Fw["BeurtVO-Fw"]
    BeurtVO_Fw -->|13x| BG
    BBG["BBG"]
    BBG -->|11x| GG
    DS_Anpassung_HH["DS-Anpassung-HH"]
    DS_Anpassung_HH -->|11x| GG
    ASG["ASG"]
    ASG -->|11x| GG
    GasSV["GasSV"]
    EnSiG["EnSiG"]
    GasSV -->|11x| EnSiG
    RettDG -->|10x| RettDG_Entwurf
    VerkSiG["VerkSiG"]
    VerkSiG -->|10x| GG
    BeamtStG -->|9x| GG
    DG -->|9x| BeamtVG
    Drs["Drs"]
    KatSchG["KatSchG"]
    Drs -->|9x| KatSchG
    KZV["KZV"]
    WiSiG["WiSiG"]
    KZV -->|9x| WiSiG
    BeamtVG -->|8x| GG
    NIS2UmsuCG -->|8x| TKG
    ZSKG["ZSKG"]
    ZSKG -->|8x| GG
    DG -->|7x| BeamtStG
    DG -->|7x| GG
    DS_Anpassung_HH -->|7x| RettDG_Entwurf
    BSIG -->|7x| TKG
    KRITIS_Dachgesetz -->|7x| TKG
    WiSiG -->|7x| GG
    BeurtVO_Fw -->|6x| BeamtStG
    RettDG_Entwurf -->|6x| GG
    PostG["PostG"]
    PostG -->|6x| GG
    BesG -->|5x| BeamtStG
    BesG -->|5x| BG
    DG -->|5x| BesG
    PersVG["PersVG"]
    PersVG -->|5x| BG
    PersVG -->|5x| DG
    DS_Anpassung_HH -->|5x| KatSchG
    VerkLG["VerkLG"]
    KZV -->|5x| VerkLG
    KZV -->|5x| VerkSiG
    EnSiG -->|5x| GG
    SOG["SOG"]
    SOG -->|4x| GG
    BG -->|4x| DG
    GleichstG["GleichstG"]
    GleichstG -->|4x| PersVG
    FeuerwG["FeuerwG"]
    FeuerwG -->|4x| GG
    KatSO["KatSO"]
    KatSO -->|4x| KatSchG
    NATOVertrag["NATOVertrag"]
    UNCharta["UNCharta"]
    NATOVertrag -->|4x| UNCharta
    Drs -->|4x| KZV
    KZV -->|4x| EnSiG
    THWG["THWG"]
    KZV -->|4x| THWG
    WasSiG["WasSiG"]
    KZV -->|4x| WasSiG
    KZV -->|4x| ZSKG
    Resilienzstrategie["Resilienzstrategie"]
    Resilienzstrategie -->|4x| KZV
    Resilienzstrategie -->|4x| ZSKG
    Resilienzstrategie -->|4x| GG
    EltSV["EltSV"]
    EltSV -->|4x| EnSiG
    TKG -->|4x| GG
    WasSiG -->|4x| GG
    BG -->|3x| GG
    BG -->|3x| BeamtVG
    BG -->|3x| BesG
    BesG -->|3x| BeamtVG
    KatSchG -->|3x| GG
    BSIG -->|3x| GG
    NIS2UmsuCG -->|3x| GG
    KZV -->|3x| GG
    Resilienzstrategie -->|3x| BSIG
    Resilienzstrategie -->|3x| NATOVertrag
    BG -->|2x| PersVG
    BeamtVG -->|2x| BBG
    HmbSUrlR["HmbSUrlR"]
    HmbSUrlR -->|2x| BG
    FeuerwG -->|2x| KatSchG
    FeuerwG -->|2x| BG
    FeuerwG -->|2x| SOG
    BSIG -->|2x| NATOVertrag
    KRITIS_Dachgesetz -->|2x| GG
    KRITIS_Dachgesetz -->|2x| NIS2UmsuCG
    NIS2UmsuCG -->|2x| EnSiG
    NIS2UmsuCG -->|2x| NATOVertrag
    RettDG_Entwurf -->|2x| ZSKG
    Drs -->|2x| KRITIS_Dachgesetz
    Drs -->|2x| EnSiG
    Drs -->|2x| WasSiG
    Drs -->|2x| ASG
    BBKG["BBKG"]
    KZV -->|2x| BBKG
    KZV -->|2x| EltSV
    KZV -->|2x| GasSV
    KZV -->|2x| BSIG
    KZV -->|2x| ASG
    ESVG["ESVG"]
    ESVG -->|2x| GG
    ESVG -->|2x| VerkSiG
    EnSiG -->|2x| BSIG
    ArbZG["ArbZG"]
    PostG -->|2x| ArbZG
    VerkSiG -->|2x| ZSKG
    AGG["AGG"]
    AGG --> GG
    AGG --> BBG
    ArbZG --> GG
    BBG --> BeamtStG
    BBG --> ASG
    BeamtStG --> ASG
    BeurtVO_Fw --> GG
    SOG --> BeamtStG
    SOG --> BG
    BG --> BBG
    BeamtVG --> DG
    BesG --> DG
    DG --> PersVG
    PersVG --> BeamtVG
    PersVG --> GG
    PersVG --> BesG
    FeuerwG --> BeamtStG
    KatSchG --> SOG
    KatSchG --> BeamtStG
    KatSchG --> BG
    RettDG --> KatSchG
    RettDG --> GG
    NIS2UmsuCG --> GasSV
    RettDG_Entwurf --> KatSchG
    RettDG_Entwurf --> IfSG
    Drs --> ZSKG
    Drs --> VerkSiG
    Drs --> WiSiG
    Drs --> SOG
    BBKG --> ZSKG
    KZV --> TKG
    ZSKG --> THWG
    ZSKG --> ASG
    ZSKG --> WiSiG
    ASG --> PostG
    ASG --> TKG
    ESVG --> VerkLG
    PostG --> ZSKG
    TKG --> ZSKG
    VerkSiG --> PostG
    VerkSiG --> TKG
```

## Neue Dokumente hinzufuegen

```bash
# PDF konvertieren
lldr convert dokument.pdf -o /tmp/out

# In passenden Ordner verschieben
cp /tmp/out/dokument.md <kategorie>/

# Committen (post-commit Hook aktualisiert index.json, Querverweise und README automatisch)
git add . && git commit -m "Add: <Dokumentname>"
git push
```

## Konventionen

- Dateinamen: `<Abkuerzung>_<Langname>.md` oder `<Abkuerzung>.md`
- Hamburger Gesetze: Suffix `_HA` oder `_Hamburg`
- Ordnerstruktur thematisch, nicht alphabetisch
- Dieses Repo ist die Single Source of Truth fuer alle konvertierten Rechtstexte
