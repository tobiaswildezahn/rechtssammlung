---
typ: "Schriftliche Kleine Anfrage"
drucksache: "22/12339"
wahlperiode: 22
id: 84258
titel: "Einsatz von künstlicher Intelligenz bei der Überwachung des Hansaplatzes (II)"
datum_anfrage: "2023-06-22"
datum_drucksache: "2023-06-30"
urheber: ["Deniz Celik"]
fraktionen: ["Die Linke"]
vorgang: 78131
seiten: 5
fragen: 21
einzelfragen: 35
antwortbloecke: 21
beantwortet: true
zitierte_drucksachen: ["22/12180", "22/11512"]
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/84258"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/84258/22_12339_einsatz_von_kuenstlicher_intelligenz_bei_der_ueberwachung_des_hansaplatzes_ii"
abgerufen: "2026-09-24"
generator: "ska_archiv 1.0"
---

# Drs. 22/12339: Einsatz von künstlicher Intelligenz bei der Überwachung des Hansaplatzes (II)

> Schriftliche Kleine Anfrage des Abgeordneten Deniz Celik (DIE LINKE) vom 22.06.23 und Antwort des Senats · Drucksache vom 30.06.2023  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/84258) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/84258/22_12339_einsatz_von_kuenstlicher_intelligenz_bei_der_ueberwachung_des_hansaplatzes_ii)

## Einleitung für die Fragen

Mit Drs. 22/12180 wurde öffentlich, dass die Polizei Hamburg die in Mannheim derzeit erprobte Software zur Erkennung „auffälliger Verhaltensmuster“ auch in Hamburg erproben will. Die Software soll nach derzeitigen Stand die „Aktivitäten Liegen, Fallen, Taumeln, Treten, Schlagen, Schubsen, Anrempeln, aggressive Körperhaltung und defensive Körperhaltung“ erkennen und bei „atypischen Verhalten“ eine Warnung an das zuständige Polizeikommissariat übermitteln können.

Im Rahmen eines sechsmonatigen Modellprojekts, soll die Software an vier Kameras am Hansaplatz erprobt werden. Ab dem 3. Quartal 2023 soll die KI zum Einsatz kommen.

Ich frage den Senat:

## Fragen und Antworten

### Frage 1

Ist die sogenannte Planungsphase abgeschlossen und liegen die Voraussetzungen für den Beginn des „Proof of Concept“ vor?

Wenn nein, wie ist der Stand?

Wenn ja, ab wann soll die Software eingesetzt werden?

#### Antwort zu Frage 1

Siehe Drs. 22/12180.

### Frage 2

Die Daten der Videokameras am Hansaplatz werden über Datenleitungen an das Referat Videotechnik (IT 421) übertragen und von dort über ausschließlich durch das IT 421 nutzbare Datenleitungen an das Polizeikommissariat 11 übertragen. Soll diese Form der Datenübertragung auch bei dem Modellprojekt erhalten bleiben?

Wenn nein, wie soll die Datenübertragung zukünftig erfolgen und inwieweit erfolgt eine verschlüsselte Übertragung der Daten?

Wenn ja, werden auch die generierten optischen Teaser auf diese Weise übertragen?

#### Antwort zu Frage 2

Ja. Im Falle eines durch die Auswertesoftware erkannten, potenziell relevanten Ereignisses wird ein Steuerbefehl vom Server der Auswertesoftware in das Videomanagementsystem (VMS) der Polizei Hamburg gesendet. Der Befehl wird über das Netzwerk an das für den Hansaplatz örtlich zuständige Polizeikommissariat (PK) 11 übertragen und löst im dortigen Client des VMS die Aufschaltung des „Hinweisbildes“ und den entsprechenden Hinweistext aus.

Im Übrigen siehe Drs. 22/12180.

### Frage 3

An welcher Stelle (PK 11, IT 421 et cetera) soll die Auswertung der Daten durch die Software erfolgen?

#### Antwort zu Frage 3

Die Auswertesoftware wird auf einem separaten Server in einem Technikraum der Informationstechnik der Polizei, Referat Videotechnik (IT 421) betrieben.

### Frage 4

Im Trefferfall, also wenn die Software ein „auffälliges Verhalten“ erkannt hat, soll ein optischer Teaser an einen Mitarbeitenden im zuständigen PK übersandt werden. An welche PKs und gegebenenfalls andere Stellen sollen die optischen Teaser übermittelt werden?

#### Antwort zu Frage 4

Die algorithmenbasierte Bildauswertung wertet die Bewegungen von als „digitalen Skeletten“ erfassten Personen (Verwandlung in Strichfiguren) aus. Die anonymisierten und transformierten Strichfiguren geben Aufschluss ausschließlich über Bewegungen. Bei Identifizierung eines atypischen Bewegungsmusters übermittelt die Software einen Hinweis an das PK 11. Es handelt sich ausschließlich um ein Assistenzsystem. Die Situationsbewertung erfolgt immer durch einen Menschen.

Im Übrigen ist die Nicht-Detektion von gegebenenfalls atypischen Bewegungen, die jedoch grundsätzlich keine polizeiliche Relevanz aufweisen, Teil des Trainings.

Siehe im Übrigen Antwort zu 2.

### Frage 5

Handelt es sich bei dem Teaser um ein Bild oder eine Sequenz von Bildern und welche weiteren Informationen werden mit dem Teaser übermittelt (zum Beispiel Uhrzeit, Aktivitätsbezeichnungen et cetera)?

#### Antwort zu Frage 5

Als Teaser wird das Live-Bild der Kamera, welches Grundlage für den Hinweis auf ein potenziell relevantes Ereignis war, auf einem separaten Bildschirm im PK 11 aufgeschaltet. Auf einem Bearbeitungsmonitor erscheint zudem ein Hinweistext mit den Informationen Datum und Uhrzeit der Detektion, Bezeichnung der relevanten Kamera sowie die erkannte Aktivitätsbezeichnung.

### Frage 6

Eine Speicherung der durch die Software erzeugten Bilder soll nach Drs. 22/12180 nicht erfolgen. Grundsätzlich werden die Aufnahmen der Videokameras am Hansaplatz bisher im Polizeipräsidium für 30 Tage gespeichert und danach automatisch gelöscht (sofern keine Ausnahme zur Weiterspeicherung vorliegt). Inwieweit soll die Software auch auf gespeicherte Daten zugreifen können, beziehungsweise inwieweit speichert die Software die Aufnahmen oder andere Daten selbst? Bitte gegebenenfalls Art der gespeicherten Daten und Speicherdauer angeben.

#### Antwort zu Frage 6

Die Software greift nicht auf gespeicherte Daten zurück. Die Auswertung erfolgt „live“. Eine (Zwischen-)Speicherung der Kamerabilder auf einer Festplatte erfolgt nicht. Die Bilddaten werden bei der Auswertung wenige Sekunden im Hauptspeicher gehalten (unter 30 Sekunden) und direkt nach der Auswertung gelöscht.

### Frage 7

Soll auch ein retrograder Zugriff der Software auf gespeicherte Aufnahmen möglich sein (zum Beispiel um fehlerhaft erkannte Bewegungen abgleichen zu können et cetera)?

Wenn ja, zu welchen Zwecken und in welchem Umfang?

#### Antwort zu Frage 7

Nein.

### Frage 8

Die Polizei Mannheim hat beim baden-württembergischen Innenministerium jüngst eine Verlängerung des dortigen Pilotprojektes beantragt. Eigentlich sollte das Projekt im November 2023 abgeschlossen sein. Es hat sich aber gezeigt, dass die Software nicht zuverlässig Bewegungen voneinander abgrenzen kann (zum Beispiel Schläge von einer Umarmung) und eine hohe Fehlerquote aufweist. Aus welchen Gründen hält es der Senat beziehungsweise die zuständige Behörde für notwendig, noch vor Abschluss des Mannheimer Pilotprojektes eine eigene Pilotierung zu beginnen?

#### Antwort zu Frage 8

Die Detektionsqualität der hier zu betrachtenden Modelle zum Erkennen von atypischen Bewegungsmustern steht unter anderem in Abhängigkeit zur Quantität der Trainingsdaten. Diese nimmt mit fortschreitender Projektdauer zu. Die Polizei Mannheim hat aus diesem Grund eine Verlängerung des Projektes beantragt, um die Hinweisgenauigkeit weiter zu optimieren. Nach den der Polizei Hamburg vorliegenden Erkenntnissen steht die Verlängerung des Mannheimer Projektes auch im Zusammenhang mit der COVID- 19-Pandemie, in deren Verlauf das Projekt nicht wie geplant umgesetzt werden konnte.

Ziel des Hamburger Projektes ist, den technischen Reifegrad der in Mannheim antrainierten Modelle sowie deren Skalierbarkeit zu testen und Erkenntnisse hinsichtlich einer möglichen Einführung in Hamburg zu erlangen.

### Frage 9

Laut Senatsantwort erfolgen keine Gesichtserkennung, keine Bestimmung des Alters, des Geschlechts oder der Ethnie. Inwieweit kann die Software zwischen für die Gefahrenabwehr relevanten „atypischen“ Verhaltensweisen und von der Norm abweichenden Bewegungen aufgrund von Behinderungen (zum Beispiel Gangunsicherheiten, Spastiken, Nutzung von Unterarmgehstützen, Rollstuhlnutzung et cetera) unterscheiden?

#### Antwort zu Frage 9

Siehe Antwort zu 4.

### Frage 10

Ist ausgeschlossen, dass durch die Software keine falschpositiven Warnungen aufgrund von körperlicher Behinderung erfolgen?

Wenn ja, auf welche Weise und wie bewertet der Senat die Software im Hinblick auf mögliche Diskriminierungen durch den Algorithmus?

#### Antwort zu Frage 10

Nein. Im Übrigen siehe Antwort zu 9.

### Frage 11

Wird das Sitzen als eine auffällige Tätigkeit gewertet?

Wenn ja, unter welchen Voraussetzungen (zum Beispiel Sitzen am Boden, Sitzen am Brunnen, Sitzen in Gruppen et cetera)?

#### Antwort zu Frage 11

Nein.

### Frage 12

Der Senat zählt das „Liegen“ als eine durch die Software erkennbare Aktivität auf. Auf welche Weise wird sichergestellt, dass die Software das Übernachten von obdachlosen Menschen nicht als „atypisches Verhalten“ erkennt und polizeiliche Interventionen veranlasst?

#### Antwort zu Frage 12

Polizeiliche Interventionen werden durch die Software nicht direkt ausgelöst. Im Übrigen siehe Antworten zu 2, 4, 5 und 9.

### Frage 13

Wie viele Polizist:innen sind im zuständigen PK aktuell für die Sichtung der Monitore für die Videoüberwachung am Hansaplatz zuständig und wie viele Mitarbeiter:innen sollen für die Erfassung der Warnhinweise zuständig sein?

#### Antwort zu Frage 13

Die Monitore für die intelligente Videobeobachtung (IVBeo) sowie die bestehende Videoüberwachung des Hansaplatzes sind im Wachraum des PK 11 installiert. Der Wachraum ist rund um die Uhr besetzt. Die Überwachung der Kameras zu den festgelegten Zeiten erfolgt durch Mitarbeitende der Dienstgruppen des PK 11 im Rahmen der täglichen Aufgabenwahrnehmung. Die hier eingesetzten Polizeibeamtinnen und Polizeibeamten sind während des Betriebes der Kameras auch für die Sichtung der Monitore und die Hinweiserfassung zuständig.

Darüber hinaus betrifft die Fragestellung bezüglich der Personalstärke die Einsatztaktik, zu der die Polizei aus grundsätzlichen Erwägungen keine Angaben macht.

### Frage 14

Welche vier der insgesamt 22 Kameras am Hansaplatz sollen für das Modellprojekt verwendet werden?

#### Antwort zu Frage 14

Nach derzeitigem Planungsstand sollen zwei Kameras am Standort Hansaplatz 4 und zwei Kameras am Standort Hansaplatz/Stralsunder Straße verwendet werden.

### Frage 15

Bisher sind die Kameras von Montag bis Donnerstag jeweils von 15 Uhr bis 7 Uhr des Folgetages und Freitag bis Sonntag sowie an Vorfesttagen und Feiertagen jeweils von 9 Uhr bis 7 Uhr des Folgetages angeschaltet. Sollen diese Nutzungszeiten verändert werden?

Wenn ja, inwieweit?

#### Antwort zu Frage 15

Nein.

### Frage 16

Werden die Hinweisschilder am Hansaplatz, die auf die bestehende Videoüberwachung hinweisen, um den Hinweis auf den Einsatz einer Verhaltensanalysesoftware ergänzt?

Wenn ja, mit welchem Inhalt?

Wenn nein, warum nicht?

#### Antwort zu Frage 16

Nein. Vor dem Hintergrund eines lediglich auf drei Monate angelegten Proof of Concept (PoC) sowie der gegenüber der klassischen Videoüberwachung deutlichen Reduzierung des Eingriffs in die Persönlichkeitsrechte Betroffener wird auf weitere Hinweise zur bestehenden Beschilderung verzichtet.

### Frage 17

Hat der Einsatz der Software Einfluss auf die bisherige Praxis der „private zones“, durch die Eingangsbereiche verpixelt werden?

Wenn ja, inwiefern?

#### Antwort zu Frage 17

Nein.

### Frage 18

Inwieweit dient die Nutzung durch die Polizei Hamburg auch dem „Training“ der Software und werden Rückmeldungen hinsichtlich der Richtigkeit oder Fehlerhaftigkeit der Warnung an die Software gegeben?

Wenn ja, in welcher Form und inwieweit erfolgen dafür Speicherungen von Aufnahmen?

#### Antwort zu Frage 18

Eine Nutzung zu Trainingszwecken ist im Proof of Concept (PoC) derzeit nicht vorgesehen.

### Frage 19

Nach Auskunft des Senats in Drs. 22/12180 soll nach Abschluss des Projekts eine Evaluation erfolgen. Nach welchen Kriterien soll die Evaluation erfolgen (zum Beispiel Fehlerquote der Software bei der Erkennung einer Bewegung, Rückgang der Kriminalität et cetera), wer soll sie durchführen und wird es einen öffentlichen Evaluationsbericht geben?

#### Antwort zu Frage 19

Das Evaluationskonzept sieht die Aus- und Bewertung folgender Aspekte vor:
- Beschaffung
- Verfahrensbeschreibung zur Beschaffung
- Verfahrensdauer der Beschaffung
- Installationsdauer
- Installationskomplexität
- Integrationsdauer
- Integrationskompatibilität
- Systemfehlerhäufigkeit nach Anzahl und Ausfalldauer
- Anzahl technisch relevanter Detektionen
- Anzahl polizeilich relevanter Detektionen
- Anzahl nicht relevanter Detektionen
- Anzahl nicht detektierter relevanter Sachverhalte
- Ressourcengewinn/-verlust
- Interventionsbeschleunigung
- Investivkosten für Kamera, Hardware und Installation
- Konsumtivkosten für Kamera, Lizenzgebühren, fortdauernde Entwicklungskosten (Fraunhofer-Institut für Optronik, Systemtechnik und Bildauswertung (IOSB)), Personalressourcen Polizei
- Presseauswertung
- Bürgerfeedback

Die Evaluierung erfolgt durch die Polizei. Darüber hinaus sind die Überlegungen noch nicht abgeschlossen.

### Frage 20

Welche Kosten entstehen für das sechsmonatige Modellprojekt?

#### Antwort zu Frage 20

Die Kosten belaufen sich auf 144.500,00 Euro, die durch den InnoTecHH Fonds bezahlt werden. Sie setzen sich aus Kosten für die Hardware und IT-Fremdleistungen zusammen.

### Frage 21

Der ehemalige Bezirksamtsleiter und SPD-Bürgerschaftsabgeordnete Markus Schreiber hat jüngst gefordert, dass vor dem Drob Inn eine Videoüberwachungsanlage installiert werden soll. Plant der Senat die Videoüberwachung vor dem Drob Inn?

Wenn ja, warum, in welchem Umfang und ab wann?

Wenn nein, welche Bedenken hat der Senat gegen eine Videoüberwachung des Drob Inns?

#### Antwort zu Frage 21

Siehe Drs. 22/11512. Darüber hinaus sind die Überlegungen noch nicht abgeschlossen.
