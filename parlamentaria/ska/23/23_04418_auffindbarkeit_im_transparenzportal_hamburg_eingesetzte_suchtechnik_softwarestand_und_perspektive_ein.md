---
typ: "Schriftliche Kleine Anfrage"
drucksache: "23/4418"
wahlperiode: 23
id: 104272
titel: "Auffindbarkeit im Transparenzportal Hamburg – eingesetzte Suchtechnik, Softwarestand und Perspektive einer semantischen Suche"
datum_anfrage: "2026-06-11"
datum_drucksache: "2026-06-19"
urheber: ["Peggy Heitmann"]
fraktionen: ["AfD"]
vorgang: 88327
seiten: 3
fragen: 8
einzelfragen: 17
antwortbloecke: 5
beantwortet: true
zitierte_drucksachen: ["22/18178"]
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/104272"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/104272/23_04418_auffindbarkeit_im_transparenzportal_hamburg_eingesetzte_suchtechnik_softwarestand_und_perspektive_einer_semantischen_suche"
abgerufen: "2026-09-23"
generator: "ska_archiv 1.0"
---

# Drs. 23/4418: Auffindbarkeit im Transparenzportal Hamburg – eingesetzte Suchtechnik, Softwarestand und Perspektive einer semantischen Suche

> Schriftliche Kleine Anfrage der Abgeordneten Peggy Heitmann (AfD) vom 11.06.26 und Antwort des Senats · Drucksache vom 19.06.2026  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/104272) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/104272/23_04418_auffindbarkeit_im_transparenzportal_hamburg_eingesetzte_suchtechnik_softwarestand_und_perspektive_einer_semantischen_suche)

## Einleitung für die Fragen

Das Transparenzportal Hamburg ist das zentrale Instrument des Hamburgischen Transparenzgesetzes. Sein Nutzen für Bürger, Initiativen und Mandatsträger hängt entscheidend davon ab, ob veröffentlichte Informationen auch tatsächlich gefunden werden. Nach den zum Portal veröffentlichten Unterlagen wird die Auffindbarkeit über eine Suche über den Volltext aller Datensätze sichergestellt. Eine solche lexikalische Volltextsuche gleicht Begriffe ab, erfasst jedoch nicht deren Bedeutung. Moderne, semantische (inhaltsbasierte) Suchverfahren – die ausschließlich vorhandene Originaldokumente auffinden und keine eigenen Antworten erzeugen – könnten die Auffindbarkeit deutlich verbessern.

Vor diesem Hintergrund frage ich den Senat:

## Fragen und Antworten

### Frage 1

Welche Softwarekomponenten werden derzeit für den Betrieb des Transparenzportals Hamburg eingesetzt, und in welcher jeweiligen Version? Bitte insbesondere die für Suche und Datenkatalog eingesetzte Software einschließlich Versionsstand angeben.

#### Antwort zu Frage 1

Ubuntu 22.04 LTS

CKAN 2.10.9

Apache Solr 9.8.0

PostgreSQL 16.14

Redis 6.0.16

Apache HTTP Server 2.4

Microsoft Windows Server 2022 Datacenter, Version 21H2, mit Microsoft SQL Server 2022

Microsoft Windows Server 2016 Datacenter, Version 1607, mit Microsoft IIS 10.0

Die konkret eingesetzten Komponenten sind der zentrale Speicher für die veröffentlichten Ressourcen, der Webauftritt für die Recherche nach den Ressourcen sowie der Leitstellenclient für die Administration des zentralen Speichers.

### Frage 2

Auf welcher Suchtechnik beruht die portalweite Suche des Transparenzportals?

a) Handelt es sich um eine lexikalische Volltextsuche, eine semantische (inhaltsbasierte/KI-gestützte) Suche oder eine Kombination?

b) Sofern keine semantische Suche zum Einsatz kommt: Ist eine solche in der derzeit eingesetzten Softwareversion technisch bereits verfügbar?

#### Antwort zu Fragen 2, 2 a) und 2 b)

Die eingesetzte Suchtechnik beruht auf Apache Solr und bietet eine lexikalische Volltextsuche, eine facettierte Suche und Suche über Metadaten. Eine semantische Suche und eine Suche per KI werden derzeit nicht eingesetzt. Die eingesetzte Version von Apache Solr (9.8.0) unterstützt jedoch technisch vektorbasierte Suchverfahren (Dense Vector Search), die eine Grundlage für semantische Suchen bilden können.

### Frage 3

Wird die für das Transparenzportal eingesetzte Software im aktuellen, vom Hersteller beziehungsweise der Entwicklergemeinschaft offiziell unterstützten Versionsstand betrieben?

Falls nein: Seit wann wird eine nicht mehr offiziell unterstützte Version eingesetzt, und ist ein Upgrade vorgesehen (wenn ja, mit welchem Zeitplan)?

#### Antwort zu Frage 3

Ja, die eingesetzte Software befindet sich aktuell im unterstützten Zustand. Für Microsoft Windows Server 2016 (Webserver) befindet sich der Hersteller im Extended Support.

### Frage 4

Welche Verträge bestehen derzeit für Betrieb, Betreuung/Pflege sowie Weiterentwicklung des Transparenzportals (jeweils Vertragspartner, Laufzeit und Leistungsumfang)?

a) Umfassen diese Verträge die Weiterentwicklung beziehungsweise Änderung der Software und der Suchfunktion, oder sind solche Leistungen vom Leistungsumfang ausgenommen?

b) Welche Kosten sind hierfür in den Haushaltsjahren 2023 bis 2026 jeweils angefallen beziehungsweise veranschlagt?

#### Antwort zu Fragen 4, 4 a) und 4 b)

Es bestehen Verträge für den Betrieb des Transparenzportals einschließlich der Veröffentlichungsworkflows (Vertragspartner: Dataport A.ö.R.; unbegrenzte Laufzeit), für die Pflege und Weiterentwicklung des Transparenzportals (Vertragspartner: Seitenbau GmbH; Laufzeitende: Februar 2028) sowie für die Pflege und Weiterentwicklung der Veröffentlichungsworkflows (Vertragspartner: Dataport; unbegrenzte Laufzeit). Die Verträge umfassen auch die Weiterentwicklung der Software und der Suchfunktion.

Die im Rahmen der genannten Verträge angefallenen Kosten verteilen sich wie folgt:

2023: 1,6 Millionen Euro

2024: 813.000 Euro

2025: 1,03 Millionen Euro

01.01. bis 15.06.2026: 485.000 Euro.

### Frage 5

Plant der Senat beziehungsweise die Fachliche Leitstelle, die Suche des Transparenzportals um eine semantische, inhaltsbasierte (KI- gestützte) Funktion zu erweitern, die der Auffindbarkeit vorhandener Dokumente dient?

a) Falls ja: mit welchem Zeitplan, welchem Kostenrahmen und in welcher Zuständigkeit?

b) Falls nein: aus welchen Gründen?

### Frage 6

Wie beurteilt der Senat die Auffindbarkeit von Dokumenten im Transparenzportal? Liegen Nutzungsanalysen, Rückmeldungen oder Beschwerden zur Suchfunktion und zur Auffindbarkeit vor, und wenn ja, mit welchem Ergebnis?

### Frage 7

In welchem Umfang liegen die im Transparenzportal veröffentlichten Dokumente in maschinenlesbarer Form (durchsuchbarer Volltext beziehungsweise Optical Character Recognition (OCR)) sowie mit strukturierten Metadaten/Verschlagwortung vor? Welche Maßnahmen zur Verbesserung dieser Datenqualität sind vorgesehen?

### Frage 8

Welche Stelle trägt die fachliche und welche die technische Verantwortung für die Weiterentwicklung der Suchfunktion des Transparenzportals?

#### Antwort zu Fragen 5 bis 8

Die im Transparenzportal veröffentlichten Ressourcen sind durch strukturierte Metadaten erschlossen und im Volltext durchsuchbar. Maßnahmen zur Verbesserung der Datenqualität sind perspektivisch geplant. Dabei ist jedoch zu beachten, dass für die Qualität der Daten in erster Linie die veröffentlichenden Stellen verantwortlich sind.

Nutzungsanalysen liegen vor, etwa in Form der meistgesuchten Stichwörter. Auch Rückmeldungen zu nicht auffindbaren Ressourcen liegen vor. Sofern Ressourcen im Transparenzportal veröffentlicht, aber nicht auffindbar sind, wird der Problematik nachgegangen.

Erste strategische Vorüberlegungen zur technischen und funktionalen Modernisierung sind abgeschlossen. Bei einer Modernisierung des Portals wird seitens der zuständigen Behörde auch die Verbesserung der Suche und der Anzeige überprüft werden. Eine konkrete Kosten- und Zeitplanung dazu steht noch aus.

Im Übrigen siehe Drs. 22/18178.
