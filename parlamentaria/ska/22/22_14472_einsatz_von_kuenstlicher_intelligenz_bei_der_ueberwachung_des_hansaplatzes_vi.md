---
typ: "Schriftliche Kleine Anfrage"
drucksache: "22/14472"
wahlperiode: 22
id: 86533
titel: "Einsatz von künstlicher Intelligenz bei der Überwachung des Hansaplatzes (VI)"
datum_anfrage: "2024-02-15"
datum_drucksache: "2024-02-23"
urheber: ["Cansu Özdemir"]
fraktionen: ["Die Linke"]
vorgang: 80298
seiten: 6
fragen: 21
einzelfragen: 29
antwortbloecke: 13
beantwortet: true
zitierte_drucksachen: ["22/12180", "22/12339", "22/12356", "22/12984", "22/13988"]
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/86533"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/86533/22_14472_einsatz_von_kuenstlicher_intelligenz_bei_der_ueberwachung_des_hansaplatzes_vi"
abgerufen: "2026-09-24"
generator: "ska_archiv 1.0"
---

# Drs. 22/14472: Einsatz von künstlicher Intelligenz bei der Überwachung des Hansaplatzes (VI)

> Schriftliche Kleine Anfrage der Abgeordneten Cansu Özdemir (DIE LINKE) vom 15.02.24 und Antwort des Senats · Drucksache vom 23.02.2024  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/86533) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/86533/22_14472_einsatz_von_kuenstlicher_intelligenz_bei_der_ueberwachung_des_hansaplatzes_vi)

## Einleitung für die Fragen

Auch nach dem Abschluss des PoC zum Einsatz künstlicher Intelligenz bei der Videoüberwachung am Hansaplatz hat die Polizei Hamburg angekündigt, ein zweijähriges Anschlussprojekt am Hansaplatz durchzuführen.

Auch nach den Anfragen Drs. 22/12180, 22/12339, 22/12356, 22/12984 und 22/13988 stellen sich weitere Fragen zum Einsatz der KI bei der Überwachung am Hansaplatz.

Ich frage den Senat:

Erfahrungen aus dem PoC

## Fragen und Antworten

### Frage 1

Aus welchen Gründen wurde als Auswertezeitraum lediglich der
21. Juli 2023 bis zum 17. September 2023 gewählt, obwohl die Pilotierungsphase bis zum 17. Oktober 2023 andauerte, und auf wie viele Stunden erstreckte sich die Laufzeit des Projekts insgesamt und wie viele der Stunden lagen davon im Auswertezeitraum?

#### Antwort zu Frage 1

Aufgrund der zu Beginn der Testphase (Proof of Concept - PoC) erforderlichen Parametrierung des Systems sowie der zum Ende des PoC aufgetretenen technischen Störungen der Hinweisgenerierung wurde der zu betrachtende Evaluationszeitraum auf die Zeit vom 21. Juli bis 17. September 2023 festgelegt.

Aus der Zeit zwischen Projektstart am 1. März 2023 und Projektende am 17. Oktober 2023 ergibt sich eine Projektlaufzeit von 5.544 Stunden. Der oben genannte Evaluationszeitraum entspricht 1.416 Stunden brutto (inklusive Stunden, in denen die Videoanlage planmäßig deaktiviert war). Eine Nettoauswertezeit wurde in Stunden nicht erfasst.

### Frage 2

In der Antwort des Senats in Drs. 22/13988 heißt es: „Aus Wirtschaftlichkeitsgründen wurde für die kurze Testphase eine reduzierte Testumgebung geschaffen. Eine technische Übermittlung spezifischer Informationen zu Einzeldetektionen (Art der Aktivität (Posenschätzung), Georeferenzierung (Anzeigen von optischen Rahmen / „bounding boxes“)) erfolgte nicht.“ Welche Erwägungen und Informationen haben zu der Entscheidung für die beschriebene Reduzierung der Testumgebung geführt und inwiefern hätte sich eine Übermittlung der vom System erzeugten Art der Aktivität und Georeferenzierung negativ auf die Wirtschaftlichkeit ausgewirkt?

#### Antwort zu Frage 2

Vor dem Hintergrund des Ziels einer ersten Erkenntnisgewinnung über die Skalierbarkeit der im Rahmen des Sicherheitskonzeptes „Mannheimer Weg 2.0“ bereits antrainierten (nicht selbstlernenden) Deep-Learning(DL)-Modelle in die Videomanagementinfrastruktur der Polizei Hamburg verfolgte das Projekt das Teilziel des effizienten Ressourceneinsatzes. Demzufolge sollte der Einsatz aufzuwendender Finanzmittel sowie personeller Ressourcen möglichst effizient ausgestaltet werden.

Die technische Umsetzung einer Übermittlung spezifischer Informationen zu Einzeldetektionen (Art der Aktivität („Posenschätzung“), Georeferenzierung (Anzeigen von optischen Rahmen/„bounding boxes“)) für den PoC hätte finanziellen sowie zeitlichen Aufwand nach sich gezogen, der im Rahmen einer Wirtschaftlichkeitsprüfung als unverhältnismäßig eingestuft wurde.

Die Auswertung jeder Einzeldetektion hinsichtlich der detektierten Posenschätzung erfolgte durch das Projekt stichprobenartig. Eine Auswertung bereits im laufenden Wachbetrieb war ohne zusätzliche Personalressource nicht möglich und zur Erkenntnisgewinnung auch nicht erforderlich.

Detektionen und Nichtdetektionen durch die Software:

## Vorbemerkung

Laut Auskunft in Drs. 22/13988 wurden in elf Fällen Hinweise generiert, die als polizeiliche relevant eingestuft wurden (zum Beispiel Tritte gegen den Kopf einer am Boden liegenden Person). In einem Fall wurde eine polizeilich relevante Situation (Schlägerei) nicht detektiert. Insgesamt erfolgte aber durchschnittlich pro Stunde eine Detektion und Hinweisgenerierung. Offensichtlich gab es also zahlreiche falsch-positive Hinweise, obwohl keine polizeilich relevante Gefahrensituation vorlag.

### Frage 3

Handelte es sich bei den zwölf genannten polizeilich relevanten Gefahrensituationen um alle polizeilich relevanten Gefahrensituationen, die während des betrachteten Projektzeitraums von der Polizei am Hansaplatz (durch Videoüberwachung) ausgemacht wurden?

Wenn nein, welche sind darunter gefasst beziehungsweise nicht gefasst?

#### Antwort zu Frage 3

Bei den genannten Gefahrensituationen handelte es sich um die polizeilich relevanten Gefahrensituationen, welche im erfassten Bereich der vier Kameras während des Wirkbetriebes der intelligenten Videobeobachtung unmittelbar festgestellt wurden.

### Frage 4

Um welche Art von Gefahrensituationen und um welche Straftatbestände handelte es sich bei den zwölf genannten Fällen? Bitte einzeln ausführen und jeweils Kurzsachverhalt angeben.

#### Antwort zu Frage 4

Tabelle

Person setzte kurz darauf ihren Weg  
1. Am Boden liegende Person  
fort  
Streitigkeiten in einer Personen Keine strafprozessualen Maßnahmen  
2.  
gruppe vor Ort  
Keine strafprozessualen Maßnahmen  
3. Am Boden liegende Person  
vor Ort  
Streitigkeiten zwischen Personen Keine strafprozessualen Maßnahmen  
4.  
gruppe; Trennung durch Passanten vor Ort  
Am Boden liegende Person, erheb5. Person nicht mehr angetroffen  
lich gestikulierend  
Schlägerei zwischen mehreren Per Einleitung Strafverfahren wegen  
6.  
sonen gefährlicher Körperverletzung

Tritte zwischen zwei Personen, Keine strafprozessualen Maßnahmen
7. augenscheinlich „aus Spaß“ vor Ort Keine strafprozessualen Maßnahmen
8. Am Boden liegende Person vor Ort
9. Am Boden liegende Person Gefahrenabwehrende Hilfeleistung
10. Am Boden liegende Person Gefahrenabwehrende Hilfeleistung
11. Am Boden liegende Person Person setzte kurz darauf Weg fort

Im Übrigen siehe Drs. 22/13988. Darüber hinausgehende Informationen zu einzelnen Sachverhalten wurden für die Evaluation nicht erhoben und sind retrograd nicht zu ermitteln.

### Frage 5

In Drs. 22/13988 heißt es. „Über die gesamte Laufzeit gab es pro Stunde durchschnittlich eine Detektion und eine entsprechende Hinweisgenerierung.“ Wie viele Detektionen wurden über die Laufzeit des Projekts hinweg insgesamt vom System generiert, wie viele davon lagen im Auswertungszeitraum, wie viele der Gesamtdetektionen waren technisch relevant?

### Frage 6

Nach Antwort in Drs. 22/13988 heißt es: „Eindeutig „falsche“ Detektionen konnten hierbei nicht festgestellt werden.“ und „Sogenannte „Falsch-Detektionen“, bei denen eine Hinweisgenerierung ohne jegliche Aktivität erfolgte, wurden nicht festgestellt.“ Was ist unter einer „eindeutig falschen Detektion“ beziehungsweise „Falsch-Detektion“ zu verstehen?

### Frage 7

Wie viele Detektionen hat es insgesamt gegeben, obwohl keine polizeilich relevante Gefahrensituation vorlag?

### Frage 8

Wie sind im Rahmen des PoC „technisch relevante Detektionen“ und „nicht relevante Detektion“ definiert und was unterscheidet diese voneinander und wie unterscheiden sich „nicht relevante Detektion“ von einer „eindeutig falschen“ Detektion? Bitte ausführen.

### Frage 9

Sind alle vom System während der Laufzeit des PoCs erzeugten Detektionen als „technisch relevante Detektionen“ zu verstehen?

### Frage 10

Welche Verhaltensmuster wurden bei der stichprobenartigen Untersuchung augenscheinlich als häufige Auslöser von Detektionen erkannt?

#### Antwort zu Fragen 5 bis 10

Im Auswertezeitraum wurden rund 1.140 Detektionen ausgelöst. Eine Anzahl von Detektionen während der gesamten Projektlaufzeit wurde nicht erhoben.

Technisch relevante Detektionen sind Posenschätzungen, die mit der tatsächlichen Situation in Übereinstimmung gebracht werden können.

Polizeilich relevante Detektionen sind Posenschätzungen, die der tatsächlichen Situation entsprechen und eine polizeiliche Intervention oder Beobachtung erforderlich machen.

Als „Falsch-Detektionen“ wurden vom Projekt Situationen definiert, in denen eine mutmaßliche Posenschätzung mit Sicherheit nicht mit der tatsächlichen Situation in Übereinstimmung hätte gebracht werden können. „Falsch-Detektionen“ entsprechen den „nicht relevanten Detektionen“.

Hinweise, die nach polizeilicher Bewertung keine akute Gefahrensituation begründeten, wurden später stichprobenartig durch das Projekt dahin gehend ausgewertet, welche Posenschätzung (zum Beispiel „aggressive Körperhaltung“) der jeweiligen Detektion augenscheinlich zugrunde lag. In den Stichproben wurden Fälle erkannt, in denen beispielsweise eine Person technisch „richtig“ als liegend detektiert wurde, sie aber keiner Hilfeleistung bedurfte. In einem anderen Fall wurde eine Kampfhandlung detektiert, bei

der es sich aber um einen offensichtlichen „Showkampf“ handelte. Die Anzahl der Stichproben betrug 64. Eindeutig „falsche“ Detektionen konnten hierbei nicht festgestellt werden. Im Übrigen wurden keine statistisch auswertbaren Daten zu häufigen Auslösern von Detektionen erhoben.

### Frage 11

In Drs. 22/13988 heißt es: „Hinweise, die nach polizeilicher Bewertung keine akute Gefahrensituation begründeten, wurden erst später und nur stichprobenartig durch das Projekt dahingehend ausgewertet, welche Posenschätzung (z. B. aggressive Körperhaltung) der jeweiligen Detektion augenscheinlich zugrunde lag“. Wie wurde im Nachhinein festgestellt, welche Posenschätzung einer durch das System generierten Detektion augenscheinlich zugrunde lag, wenn weder die durch das System erzeugten Skelettierungen noch die dazugehörigen Kamerabilder für einen längeren Zeitraum als 30 Sekunden (Skelettierungen) beziehungsweise 72 Stunden (Videoaufnahmen) vorgehalten wurden?

#### Antwort zu Frage 11

Die detektierten Videosequenzen wurden im Rahmen der vorgeschriebenen Speicherfristen für die klassische Videoüberwachung am Hansaplatz durch das Projekt zum Zwecke der Evaluierung stichprobenartig gesichtet und bewertet.

### Frage 12

Mit welcher Begründung wurden die Hinweise auf nicht polizeilich relevante Situation nur stichprobenartig ausgewertet?

#### Antwort zu Frage 12

Siehe Antwort zu 2.

Bürger*innen-Feedback zur KI-Überwachung und Anpassung der Evaluation

## Vorbemerkung

Der Senat gibt in Drs. 22/13988 an, dass eine strukturierte Bürgerbefragung nicht durchgeführt worden sei, es während des PoC aber verschiedene Bürgergespräche gegeben habe, die durchweg positiv ausgefallen seien. „Vereinzelt kritische Betrachtungen fußten im Kern auf der falschen Darstellung der hier zum Einsatz kommenden Technologie und der damit verbundenen Unterstellung einer angeblich beabsichtigten biometrischen Datenerfassung durch die Sicherheitsbehörden.“ (vergleiche Drs. 22/13988, Antwort auf Frage 10).

### Frage 13

Wer hat die Bürger*innengespräche durchgeführt (Polizei in Uniform, Zivilpolizei, Mitarbeitende der Innenbehörde et cetera), nach welchen Aspekten wurden die Bürger*innen für die Gespräche ausgewählt, inwieweit und wodurch wurde dabei darauf geachtet, die Vielfalt der von der KI-Überwachung betroffenen Personen zu repräsentieren und wurden die Bürger*innengespräche in irgendeiner Form dokumentiert und können nachvollzogen/nachträglich ausgewertet werden?

#### Antwort zu Frage 13

Die in Rede stehenden Bürgergespräche erfolgten im Rahmen polizeilicher Präsenzmaßnahmen. Sie wurden ausschließlich proaktiv seitens der Bürger geführt. Eine inhaltliche Übermittlung an das Projekt erfolgte ohne Angaben zur jeweiligen Person, eine strukturierte Erfassung wurde hierbei nicht durchgeführt.

### Frage 14

Wurden Gespräche mit sozialen Trägern/Vereinen/Organisationen geführt?

Wenn ja, wann, mit welchen Trägern/Vereinen/Organisationen und wurde dabei auch Kritik an dem Projekt formuliert?

Wenn nein, warum nicht?

#### Antwort zu Frage 14

Nein. Dies war kein Bestandteil des Projekts.

### Frage 15

Welche Strukturen, Vereine, Organisationen oder Träger im Stadtteil wurden vor der Entscheidung zur Verlängerung des Projekts um zwei Jahre dazu angehört oder in die Entscheidung einbezogen? Bitte einzeln darstellen und ausführen, auf welche Weise eine Einbeziehung erfolgte?

#### Antwort zu Frage 15

Eine Beteiligung im Sinne der Fragestellung erfolgte durch die Polizei nicht.

### Frage 16

Wo beziehungsweise von wem wurde die zum Einsatz kommende Technologie falsch dargestellt oder behauptet, dass bei der intelligenten Videobeobachtung biometrische Daten erfasst werden?

#### Antwort zu Frage 16

Hinweise auf vereinzelt kritische Betrachtungen, die im Kern auf der falschen Darstellung der hier zum Einsatz kommenden Technologie und der damit verbundenen Unterstellung einer angeblich beabsichtigten biometrischen Datenerfassung durch die Sicherheitsbehörden fußten, sind frei zugänglichen Medienberichten zu entnehmen.

### Frage 17

In Drs. 22/13988 heißt es: „Aus vorgenannten Gründen sowie zwischenzeitlich gewonnenen Erfahrungen ergab sich noch während des PoC das Erfordernis, geplante Evaluationsziele und Kennzahlen in Bezug auf die Auswertung der Detektionsqualität anzupassen bzw. auf diese teilweise zu verzichten.“ Welche konkreten Erfahrungen aus dem PoC begründeten den teilweisen Verzicht beziehungsweise die Anpassung der Evaluationsziele und Kennzahlen in Bezug auf die Auswertung der Detektionsqualität und auf welche der in Drs. 22/12339 konkret genannten Evaluationskriterien und Kennzahlen wurde verzichtet, welche Evaluationsziele wurden beibehalten, und welche Evaluationsziele und Kennzahlen wurden in welcher Form angepasst? Bitte auflisten.

#### Antwort zu Frage 17

Die Anzahl „technisch relevanter Detektionen“ und „nicht-relevanter Detektionen“ wurde stichprobenartig erhoben. Im Übrigen siehe Antwort zu 2.

Zweijähriges Anschlussprojekt am Hansaplatz:

## Vorbemerkung

Der Senat hat angekündigt, den Einsatz der Technik nun in einem zweijährigen Anschlussprojekt in Kooperation mit dem Fraunhofer- Institut weiterzuentwickeln. Zunächst soll das Anschlussprojekt am bisherigen Standort Hansaplatz durchgeführt werden, es soll aber auch eine Ausweitung auf weitere Kameras am Hansaplatz und auf weitere Standorte geprüft werden.

### Frage 18

Was sind der Zweck und das Ziel des Anschlussprojektes und welche Kosten entstehen durch das zweijährige Anschlussprojekt? Bitte aufschlüsseln nach Investivkosten (weitere Hardware et cetera) und Konsumtivkosten (Lizenzkosten, Betriebs- und Weiterentwicklungskosten et cetera).

### Frage 19

Werden die vom System erfassten beziehungsweise erzeugten Daten künftig länger gespeichert (über 30 Sekunden im Hauptspeicher hinaus, siehe Drs. 22/12339)?

Wenn nein, wie wird bei der Nutzung über einen längeren Zeitraum hinaus gewährleistet, dass die Funktionsgüte des Systems erhalten bleibt, wenn keine Daten zu den vom System produzierten Klassifika-

tionen beziehungsweise Einordnung in Kategorien atypischer Verhaltensmuster vorliegen?

### Frage 20

Wird das System künftig auch mit Daten vom Hansaplatz (nach-)trainiert werden?

Wenn ja, wie werden diese erhoben?

### Frage 21

Wird die Bevölkerung am Hansaplatz zukünftig über den Einsatz von künstlicher Intelligenz informiert?

Wenn ja, wie?

Wenn nein, wieso nicht?

#### Antwort zu Fragen 18 bis 21

In einem zweijährigen Anschlussprojekt soll die intelligente Videobeobachtung zur Optimierung gefahrenabwehrender Intervention und Erhöhung polizeilicher Effizienz in die bereits bestehende klassische Videoüberwachung sukzessive eingebunden werden. Darüber hinaus sind eine Beteiligung an der weiteren Technologieoptimierung sowie die Erforschung an unterschiedlichen Standorten hinsichtlich der Erfolgskriterien für eine Skalierbarkeit der Technologie geplant.

Im Übrigen befindet sich dieses Projekt derzeit in der Definitionsphase. Eine konkrete Zieldefinition sowie alle sich daraus ergebenden Projektelemente werden derzeit erarbeitet. Die entsprechenden Planungen sind noch nicht abgeschlossen.
