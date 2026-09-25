---
typ: "Schriftliche Kleine Anfrage"
drucksache: "23/1309"
wahlperiode: 23
id: 94716
titel: "Erprobung eines KI-basierten Ertrinkungserkennungssystems im Bille-Bad"
datum_anfrage: "2025-09-01"
datum_drucksache: "2025-09-09"
urheber: ["Marie Kleinert"]
fraktionen: ["Die Linke"]
vorgang: 85249
seiten: 5
fragen: 13
einzelfragen: 26
antwortbloecke: 11
beantwortet: true
zitierte_drucksachen: []
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/94716"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/94716/23_01309_erprobung_eines_ki_basierten_ertrinkungserkennungssystems_im_bille_bad"
abgerufen: "2026-09-23"
generator: "ska_archiv 1.0"
---

# Drs. 23/1309: Erprobung eines KI-basierten Ertrinkungserkennungssystems im Bille-Bad

> Schriftliche Kleine Anfrage der Abgeordneten Marie Kleinert (Die Linke) vom 01.09.25 und Antwort des Senats · Drucksache vom 09.09.2025  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/94716) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/94716/23_01309_erprobung_eines_ki_basierten_ertrinkungserkennungssystems_im_bille_bad)

## Einleitung für die Fragen

Seit dem 3. Dezember 2024 erprobt die Bäderland Hamburg GmbH im Bille- Bad in Bergedorf ein kamerabasiertes Ertrinkungserkennungssystem des Herstellers Lynxight. Nach Angaben der Berichterstattung („KI als Lebensretter: So lief die Testphase im Bille-Bad“, „Hamburger Abendblatt“, 14.08.2025; „Die digitale Badeaufsicht“, „die tageszeitung“, 17.03.2025) wurden hierfür neun Spezialkameras über zwei Schwimmbecken installiert. Die Kosten der Installation werden mit einer „höheren fünfstelligen Summe“ beziffert.

Bis August 2025 sollen über 1.500 Fehlalarme ausgelöst worden sein, durchschnittlich mehr als sechs pro Tag. Ursachen waren demnach zum Beispiel Wasserreflexionen und eingesetzte Reinigungsroboter. Einen während der Testphase aufgetretenen kritischen Vorfall, das Ohnmächtigwerden eines Apnoetauchers bei einem abgesprochenen Trainingstauchgang, konnte das System nicht erkennen.

Laut Berichterstattung erfolgt die Speicherung und Verarbeitung der Videodaten lokal auf Servern der Bäderland Hamburg GmbH, ohne Übermittlung an den Hersteller oder Dritte. Die Aufzeichnungen sollen nach 15 Sekunden wieder gelöscht werden. Ursprünglich war die Erprobung bis Sommer 2025 befristet, nach späteren Angaben soll es sich jedoch um eine unbefristete Testphase handeln.

Vor diesem Hintergrund frage ich den Senat:

## Einleitung für die Antworten des Senats

Entgegen der Darstellung in der Einleitung für die Fragen handelte es sich nicht um
1.500 Fehlalarme, sondern um Hinweise auf ungewöhnliche Situationen im Becken. Dies zeigt die Funktionsfähigkeit der Risikoerkennung. Im Fall des in Rede stehenden Apnoe-Tauchers erfolgte eine 1:1-Betreuung durch Personal der Bäderland Hamburg GmbH (Bäderland), daher war die Situation unmittelbar lösbar und benötigte nicht den Hinweis des Systems. Das Erkennungssystem ist so getaktet, dass es nicht unmittelbar anschlägt, da sich nicht jede bewegungslose Person (zum Beispiel in Gleit- oder Tauchphasen, an Massagedüsen et cetera) in einer Gefahrensituation befindet.

Dies vorausgeschickt, beantwortet der Senat die Fragen auf der Grundlage von Auskünften der Bäderland wie folgt:

## Fragen und Antworten

### Frage 1

Wird das im Rahmen der Pilotphase aufgenommene Videomaterial in irgendeiner Form zur Weiterentwicklung oder Optimierung des Systems durch den Hersteller Lynxight genutzt?

Falls ja, welche Daten werden hierfür aus dem lokalen System an den Hersteller übermittelt?

Falls nein, wie wird sichergestellt, dass keine Datenweitergabe erfolgt?

#### Antwort zu Frage 1

Die Daten werden nur lokal verarbeitet. Das Unternehmen nutzt ein zentralisiertes Trainingsmodell, bei dem die Weiterentwicklung der KI ausschließlich auf zentralen Servern erfolgt. Die lokalen Systeme führen kein eigenständiges Lernen durch, sondern erhalten im Zweiwochenrhythmus Software-Updates. Grundlage für das Training sind annotierte Videoclips aus Kalibrierungstauchgängen sowie eine sehr kleine Auswahl an Alarm- Clips, die gezielt zur Verbesserung der Erkennungsgenauigkeit beitragen. Die Clips stammen von Standorten, die dem Upload von Alarm-Clips und der Verwendung der Clips zum Training der KI nicht widersprochen haben.

Etwa alle zwei Wochen wird ein neues Modell trainiert, getestet und anschließend an alle Kundenpools ausgerollt – auch an solche, die selbst keine Daten für das Training des Systems bereitstellen. Bäderland stellt keine Daten für das Training des Systems zur Verfügung und ist demnach auf die Updates angewiesen. Andernfalls würde das System nur lokal lernen, was wesentlich länger dauert und demnach nur einen deutlich geringeren Sicherheitsbeitrag leisten kann.

### Frage 2

Handelt es sich bei dem im Bille-Bad eingesetzten System um ein vollständig geschlossenes System, bei dem die Serverkomponenten am selben Standort wie die Kameras betrieben werden?

Falls nein, wo befinden sich die jeweiligen Serverkomponenten?

#### Antwort zu Frage 2

Die Server befinden sich im Billebad und sind mit keinen anderen Komponenten der Bäderland-IT verbunden.

### Frage 3

Auf welche Weise erfolgt die Verarbeitung der Videodaten technisch konkret (Verarbeitungsstufen, eingesetzte Hardware, Serverarchitektur)?

#### Antwort zu Frage 3

Die von IP-Überwachungskameras an den lokalen Server mit integrierter KI-Technologie zur Bildverarbeitung gesendeten Informationen werden vom System in folgenden Schritten verarbeitet:

1. Erkennung/Klassifizierung: Dieser Algorithmus ist für die Erkennung der Unterscheidung von Schwimmbadbenutzern und Objekten sowohl über als auch unter der Wasseroberfläche zuständig und wandelt die Bilder in konkrete, numerische Merkmale um.

2. Verfolgung: Das System identifiziert die wichtigsten Körperpunkte und verfolgt die Bewegungen über das Becken hinweg.

3. Entscheidung: Dieser Algorithmus bestimmt die Körperposition im Wasser sowie Bewegungsmuster, um potenzielle Risiken frühzeitig zu erkennen.

### Frage 4

Besteht für den Hersteller Lynxight ein Fernzugriff auf das System oder einzelne Komponenten?

a) Falls ja: Zu welchen Zwecken, mit welchen technischen Mitteln und unter welchen Zugriffsrechten?

b) Falls nein: Wie werden Wartungsarbeiten, Softwareupdates und Konfigurationsänderungen durchgeführt?

#### Antwort zu Fragen 4, 4 a) und 4 b)

Während der Kalibrierungsphase erhalten die Lynxight-Administratoren und Entwickler Fernzugriff auf die Videoaufzeichnung vor Ort, um das System für eine optimale Leistung auf Grundlage der spezifischen Poolumgebung zu konfigurieren. Die Kalibrierungsphase wurde in Zeiten ohne Besucheraufkommen durch Testpersonen (Bäderland-Personal) vor der Pilotphase durchgeführt.

Außerhalb der Kalibrierungsphase findet grundsätzlich kein Zugriff statt. Dieser kann jedoch für den technischen Support nach einer Kundenbeschwerde oder für eine notwendige Re-Kalibrierung verwendet werden. Kundenbeschwerden gab es keine.

Die Verbindung ist mittels RealVNC Cloud Connect und Tailscale VPN abgesichert.

### Frage 5

Wie viele Badeaufsichten sind nach Kenntnis des Senats durchschnittlich pro Schwimmbecken während der Öffnungszeiten in den Anlagen der Bäderland Hamburg GmbH eingesetzt?

#### Antwort zu Frage 5

Der Personaleinsatz orientiert sich an der Richtline 94.05 der Deutschen Gesellschaft für das Badewesen und ist gemäß der Richtlinie abhängig von folgenden Bestimmungsfaktoren:

• Art und Größe des Bades,

• Angebote (Wasserattraktionen und Animation),

• Überschaubarkeit des Bades und der Becken (Aufsichtsbereiche),

• Frequentierung und die Möglichkeit der Teilnutzung des Bades,

• Belegung und Nutzung im Parallelbetrieb zu Schulen und Vereinen,

• örtliche Betriebsbedingungen,

• Unfallart und -häufigkeit in den letzten fünf Jahren.

Ein durchschnittlicher Wert kann von der Bäderland vor diesem Hintergrund entsprechend der heterogenen Struktur der Becken und jeweiligen Standortbedingen nicht gebildet werden.

### Frage 6

Wie hat sich die Zahl der bei der Bäderland Hamburg GmbH beschäftigten Badeaufsichten seit dem Jahr 2015 entwickelt (bitte nach Jahren aufschlüsseln)?

#### Antwort zu Frage 6

Die Entwicklung der beschäftigten Badeaufsichten im erfragten Zeitraum ist der nachfolgenden Tabelle zu entnehmen:

Tabelle

Jahr* Anzahl**  
2015 434  
2016 435  
2017 469  
2018 470  
2019 481  
2020 425***  
2021 420***  
2022 494  
2023 502  
2024 541

\* Angabe jeweils zum Stichtag 31.12.

** Rettungsschwimmer:innen inkl: Tagesaushilfen, Fachkräfte und Schwimmmeister:innen

*** coronabedingter Effekt, wegen Kurzarbeit nicht kompensierbar

### Frage 7

Von wann bis wann lief die Erprobungsphase des KI-Systems im Bille-Bad konkret?

a) Ist diese Erprobung weiterhin befristet oder inzwischen unbefristet?

b) Auf welcher Grundlage wurde die Befristung aufgehoben beziehungsweise verlängert?

#### Antwort zu Fragen 7, 7 a) und 7 b)

Die Erprobung startete Anfang Dezember 2024 und lief bis Juli 2025. Inzwischen wurde aufgrund der positiven Erfahrungen und des Mehrgewinns an Sicherheit die Entscheidung getroffen, das System als zusätzliche Aufsichtskomponente für Badegäste und Mitarbeitende weiter zu betreiben.

### Frage 8

Was ist unter den in der Berichterstattung genannten „internationalen Updates“ des Systems zu verstehen?

a) Handelt es sich dabei um Softwareaktualisierungen des Herstellers?

b) Falls ja: Wie werden diese eingespielt, und auf welcher Datenbasis erfolgen sie?

### Frage 9

Aus welchen Quellen stammen die Trainingsdaten, mit denen das Ertrinkungserkennungssystem des Herstellers Lynxight entwickelt wurde?

a) Wurden für das Training auch Daten aus Hamburg oder Deutschland verwendet?

#### Antwort zu Fragen 8 bis 9 a)

Siehe Antworten zu 1 und zu 4.

### Frage 10

Wie viele Warnmeldungen wurden in der Pilotphase an die Badeaufsichten ausgegeben?

a) Wie viele davon waren Fehlalarme (falsch positive Meldungen)?

b) Wie viele Meldungen bezogen sich auf tatsächlich kritische Situationen?

#### Antwort zu Fragen 10, 10 a) und 10 b)

Das System ist darauf ausgelegt, potenzielle Risikosituationen frühzeitig zu erkennen. Daher alarmiert es bereits vor dem Eintritt eines möglichen Sicherheitsereignisses – auch, wenn das Sicherheitsereignis gegebenenfalls gar nicht eingetreten wäre. Es handelt sich daher nicht um einen Fehlalarm im klassischen Sinne, sondern um das intendierte Verhalten des Systems.

Von Dezember 2024 bis Juli 2025 kam es zu 1.555 „Warnung“-Ereignissen und 363 „Vorsicht“-Ereignissen.

Eine Warnung mit höchster Priorität wird ausgelöst, wenn eine Person für einen kritischen Zeitraum und ohne erkennbare Bewegung vollständig unter Wasser ist oder wenn ein schnelles Absinken unter Wasser erkannt wird. Ein „Vorsicht“-Ereignis wird mit einer mittleren Priorität eingestuft und wird bei Anzeichen von Panik oder unkoordinierten Bewegungen über einen definierten Zeitraum sowie bei unregelmäßigen Bewegungsmustern, die auf Schwierigkeiten hindeuten, ausgelöst.

Aufgrund des Systems und der Personalaufsicht sind keine tatsächlich kritischen Situationen aufgetreten.

### Frage 11

Wie bewertet der Senat eine Pilotphase, in der kein tatsächlicher Notfall durch das Ertrinkungserkennungssystem erkannt wurde?

#### Antwort zu Frage 11

Die Pilotphase war in erster Linie darauf ausgerichtet, grundlegende Erfahrungen mit dem System und seinem Verhalten im Regelbetrieb zu sammeln. Die Erprobung wird aufgrund der geringen Anzahl an sogenannten falsch-positiven Ereignismeldungen (an rund 250 Tagen durchschnittlich sechs Meldungen bei täglicher Öffnungszeit von rund 16 Stunden) als Erfolg gewertet.

### Frage 12

Wann rechnet der Senat mit einem möglichen regulären Einsatz kamerabasierter KI-Systeme zur Erkennung von Badeunfällen in den Anlagen der Bäderland Hamburg GmbH?

### Frage 13

Welche einmaligen Investitions- und welche laufenden Betriebskosten entstehen pro Standort beim Einsatz eines solchen Systems?

a) Welche Minimal- und Maximalbeträge ergeben sich aus den derzeit in Erwägung gezogenen Systemen?

#### Antwort zu Fragen 12, 13 und 13 a)

Die Testphase wurde gerade beendet und ausgewertet. Bäderland steht demnach gerade am Anfang einen Projektplan für den sukzessiven Ausbau des Systems für die kommenden Wirtschaftsjahre vorzubereiten.

Einmalige Investitionskosten und laufende Betriebskosten sind derzeit noch nicht absehbar, sie sind im Rahmen des Projektes zu ermitteln und zu verhandeln. Da die Bäderland als zweitgrößter Betreiberin Deutschlands derzeit auch der größte Betrieb mit Interesse an dem System ist, können keine Vergleichsdaten herangezogen werden.
