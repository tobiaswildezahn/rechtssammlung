---
typ: "Schriftliche Kleine Anfrage"
drucksache: "23/4557"
wahlperiode: 23
id: 104404
titel: "Transparenzportal Hamburg – Nachfrage zur Auffindbarkeit, semantischen Suche und Datenqualität (Nachfrage zu Drs. 23/4418)"
datum_anfrage: "2026-06-22"
datum_drucksache: "2026-06-30"
urheber: ["Peggy Heitmann"]
fraktionen: ["AfD"]
vorgang: 88405
seiten: 3
fragen: 10
einzelfragen: 14
antwortbloecke: 9
beantwortet: true
zitierte_drucksachen: ["23/4418", "23/3436"]
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/104404"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/104404/23_04557_transparenzportal_hamburg_nachfrage_zur_auffindbarkeit_semantischen_suche_und_datenqualitaet_nachfrage_zu_drs_23_4418"
abgerufen: "2026-09-23"
generator: "ska_archiv 1.0"
---

# Drs. 23/4557: Transparenzportal Hamburg – Nachfrage zur Auffindbarkeit, semantischen Suche und Datenqualität (Nachfrage zu Drs. 23/4418)

> Schriftliche Kleine Anfrage der Abgeordneten Peggy Heitmann (AfD) vom 22.06.26 und Antwort des Senats · Drucksache vom 30.06.2026  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/104404) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/104404/23_04557_transparenzportal_hamburg_nachfrage_zur_auffindbarkeit_semantischen_suche_und_datenqualitaet_nachfrage_zu_drs_23_4418)

## Einleitung für die Fragen

Mit der Schriftlichen Kleinen Anfrage, Drs. 23/4418, wurden die eingesetzte Suchtechnik, der Softwarestand und die Perspektive einer semantischen Suche im Transparenzportal Hamburg erfragt. Die Antwort des Senats bestätigte, dass die portalweite Suche ausschließlich auf einer lexikalischen Volltextsuche (Apache Solr) beruht und eine semantische beziehungsweise KI-gestützte Suche derzeit nicht eingesetzt wird – obwohl die eingesetzte Solr- Version 9.8.0 vektorbasierte Suchverfahren (Dense Vector Search) technisch bereits unterstützt. Mehrere Teilfragen blieben jedoch unbeantwortet oder wurden lediglich gebündelt und ohne konkrete Angaben behandelt. Insbesondere die Frage nach der Planung einer semantischen Suche (Frage 5), nach dem Umfang maschinenlesbarer Dokumente (Frage 7) sowie nach der fachlichen und technischen Zuständigkeit (Frage 8) wurden nicht im erbetenen Detailgrad beantwortet.

Vor diesem Hintergrund frage ich den Senat:

## Fragen und Antworten

### Frage 1

Plant der Senat beziehungsweise die Fachliche Leitstelle die Einführung einer semantischen, inhaltsbasierten (vektor- beziehungsweise KI-gestützten) Suchfunktion, die ausschließlich der Auffindbarkeit vorhandener Originaldokumente dient – ja oder nein?

Falls ja: mit welchem Zeitplan, welchem Kostenrahmen und in welcher Zuständigkeit?

Falls nein: aus welchen konkreten fachlichen, finanziellen oder rechtlichen Gründen?

#### Antwort zu Frage 1

Eine Überarbeitung der Suchfunktion wird Gegenstand einer grundsätzlichen Modernisierung des Transparenzportals sein. Die Planungen sind noch nicht abgeschlossen, siehe Drs. 23/4418.

### Frage 2

Da die eingesetzte Version Apache Solr 9.8.0 laut Senatsantwort Dense Vector Search technisch bereits unterstützt: Welche konkreten Hindernisse stehen einer Aktivierung dieser bereits vorhandenen Funktionalität entgegen, und wurde deren Einsatz bereits geprüft (wenn ja, mit welchem Ergebnis)?

#### Antwort zu Frage 2

Die Implementierung einer KI-basierten Suche ist nicht durch die einfache Aktivierung einer bereits vorhandenen Funktion umsetzbar, sondern bedarf weiterer Anpassungen und Erweiterungen, die sorgfältige Planung und weiteren Ressourceneinsatz benötigt.

So ist zum Beispiel die Integration von KI-basierten Vektorsuchen (wie für semantische Suche nötig) im CKAN-Standardkern nicht nativ verankert und erfordert aufwendige, maßgeschneiderte Erweiterungen.

### Frage 3

Welcher prozentuale Anteil der im Transparenzportal veröffentlichten Dokumente liegt als durchsuchbarer Volltext (per OCR erkannt) vor?

#### Antwort zu Frage 3

Die in das Transparenzportal eingestellten Dokumente werden OCR-erkannt (automatische Texterkennung) und liegen somit als durchsuchbarer Volltext vor. Es kam lediglich in der Aufbauphase des Portals zu vereinzelten Problemen bei der OCR-Erkennung, sodass der Volltext aktuell zu nahezu 100 Prozent durchsuchbar ist.

### Frage 4

Welcher prozentuale Anteil der veröffentlichten Ressourcen verfügt über strukturierte Metadaten beziehungsweise eine inhaltliche Verschlagwortung?

#### Antwort zu Frage 4

100 Prozent der im Transparenzportal veröffentlichten Ressourcen verfügen über strukturierte Metadaten.

### Frage 5

Welche zehn Suchbegriffe wurden im Jahr 2025 am häufigsten im Transparenzportal gesucht?

#### Antwort zu Frage 5

Siehe Drs. 23/3436.

### Frage 6

Bei wie vielen Suchanfragen wurde im Jahr 2025 kein Treffer ausgegeben (absolute Zahl und prozentualer Anteil aller Suchanfragen – sogenannte Null-Treffer-Quote)?

#### Antwort zu Frage 6

Die absolute Zahl sowie die exakte prozentuale Null-Treffer-Quote werden statistisch nicht erfasst.

### Frage 7

Wie viele Rückmeldungen oder Beschwerden zu im Portal veröffentlichten, aber nicht auffindbaren Ressourcen sind in den Jahren 2023, 2024 und 2025 jeweils eingegangen (bitte je Jahr angeben)?

#### Antwort zu Frage 7

Keine, da im Portal veröffentlichte Ressourcen auch auffindbar sind. Im Einzelfall konnten Ressourcen nach einem Hinweis der verantwortlichen Stelle durch die Bürgerinnen und Bürger aufgefunden werden.

### Frage 8

Welche Stelle trägt die fachliche Verantwortung und welche Stelle die technische Verantwortung für die Weiterentwicklung der Suchfunktion des Transparenzportals?

#### Antwort zu Frage 8

Die Verantwortung für den technischen Betrieb und die fachliche Weiterentwicklung der Suchfunktion liegt beim Staatsarchiv.

### Frage 9

Die Senatsantwort führt aus, dass sich Microsoft Windows Server 2016 (Webserver) im Extended Support befindet. Bis zu welchem Datum ist die Migration auf eine im regulären Support befindliche Version vorgesehen?

#### Antwort zu Frage 9

Die Migration wird bis Jahresende 2026 abgeschlossen sein.

### Frage 10

Die Antwort verweist auf abgeschlossene „erste strategische Vorüberlegungen zur technischen und funktionalen Modernisierung“. In welchem Dokument beziehungsweise in welcher Form liegen diese Vorüberlegungen vor? Bis wann ist mit einer konkreten Kosten- und Zeitplanung zu rechnen? Ist die Verbesserung der Suchfunktion ausdrücklicher Bestandteil dieser Modernisierungsüberlegungen?

Antwort zu Frage 10.

Die Vorüberlegungen zur Modernisierung sind in internen Planungspapieren festgehalten. Eine konkrete Kosten- und Zeitplanung ist nach der Definition der konkreten Anpassungsbedarfe und der Klärung der Umsetzung bis Ende des Jahres 2027 vorgesehen. Im Übrigen siehe Antwort zu 1.
