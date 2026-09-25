---
typ: "Schriftliche Kleine Anfrage"
drucksache: "22/12984"
wahlperiode: 22
id: 84960
titel: "Einsatz von künstlicher Intelligenz bei der Überwachung des Hansaplatzes (IV)"
datum_anfrage: "2023-09-18"
datum_drucksache: "2023-09-26"
urheber: ["Deniz Celik"]
fraktionen: ["Die Linke"]
vorgang: 78852
seiten: 5
fragen: 21
einzelfragen: 30
antwortbloecke: 15
beantwortet: true
zitierte_drucksachen: ["22/12180", "22/12339", "22/12356"]
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/84960"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/84960/22_12984_einsatz_von_kuenstlicher_intelligenz_bei_der_ueberwachung_des_hansaplatzes_iv"
abgerufen: "2026-09-24"
generator: "ska_archiv 1.0"
---

# Drs. 22/12984: Einsatz von künstlicher Intelligenz bei der Überwachung des Hansaplatzes (IV)

> Schriftliche Kleine Anfrage des Abgeordneten Deniz Celik (DIE LINKE) vom 18.09.23 und Antwort des Senats · Drucksache vom 26.09.2023  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/84960) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/84960/22_12984_einsatz_von_kuenstlicher_intelligenz_bei_der_ueberwachung_des_hansaplatzes_iv)

## Einleitung für die Fragen

Derzeit erprobt die Polizei Hamburg eine Software zur automatischen Erkennung „auffälliger Verhaltensmuster“ am Hansaplatz. Auch nach den Senatsantworten auf unsere Schriftlichen Kleinen Anfragen Drs. 22/12180, 22/12339 und 22/12356 bleiben weitere Fragen offen.

Ich frage den Senat:

Speicherung der Daten und Verwendung von Daten zum Training der KI

## Fragen und Antworten

### Frage 1

In der Einleitung der Antworten des Senats in Drs. 22/12180 heißt es: „Eine Speicherung der durch die Software erzeugten Daten auf einer Festplatte zur retrograden Auswertung erfolgt nicht.“ Heißt dies, dass überhaupt keine Speicherung von durch das System erzeugten oder genutzten Daten (zum Beispiel Zeitstempel eines Alarms; Art der vom System erkannten Aktivität; Identifikationsnummer der auslösenden Kamera; Skelettierungsbilder beziehungsweise -daten et cetera) erfolgt?

#### Antwort zu Frage 1

Eine Speicherung der durch die Software im Zusammenhang mit der intelligenten Videoüberwachung (IVBeo) erzeugten Daten, das heißt die „digitale Skelettierung“ erfasster Personen und der Videobilder, erfolgt nicht.

Um zu erkennen, ob die Software bei der Detektion atypischer Bewegungsmuster korrekt auslöst, werden für diesen Zweck unter anderem Hinweis-ID, Zeitstempel, Kamera- Nummer und der Alarmierungstext automatisiert in einem Hinweislogbuch bei der Informationstechnik der Polizei, Referat Videotechnik (IT 42), aufgezeichnet. Die vorgesehene Evaluation basiert insbesondere auf dem Hinweislogbuch. Im Übrigen siehe Drs. 22/12180.

### Frage 2

Werden anderweitige, zum ordentlichen Betrieb der Software oder zu ihrer funktionalen Evaluation nötige Daten gespeichert (zum Beispiel Log-Dateien; Zeitstempel und Details von durch IT-421-Server im Videomanagementsystem (VMS) erzeugten Events („Hinweisbild“ mit Hinweistext); durch Beamt*innen im Zusammenhang mit der Nutzung des Systems erstellte Einträge in anderen Systemen oder in Papierform et cetera)?

Wenn ja, in welchem Umfang und für welchen Zeitraum?

### Frage 3

In der Antwort auf Frage 6 in Drs. 22/12339 heißt es: „Die Bilddaten werden bei der Auswertung wenige Sekunden im Hauptspeicher gehalten (unter 30 Sekunden) und direkt nach der Auswertung gelöscht.“ Wenn weder Bilddaten noch andere vom System erzeugte Daten auf dem PK 11 oder IT 421 zugänglichen Speichermedien gesichert werden, anhand welcher Datengrundlage erfolgt die quantitative Evaluation des Systems (zum Beispiel hinsichtlich der Anzahl technisch/polizeilich relevanter Detektionen, Anzahl nicht relevanter Detektionen, Interventionsgeschwindigkeit et cetera)?

### Frage 4

In der Antwort auf die Frage 13 in Drs. 22/12339 heißt es: „Die hier eingesetzten Polizeibeamtinnen und Polizeibeamten sind während des Betriebes der Kameras auch für die Sichtung der Monitore und die Hinweiserfassung zuständig.“ Handelt es sich hierbei um Hinweiserfassung im Kontext der vom System erzeugten Daten (Bildmaterial/ Skelettierungen und Hinweistext)?

Falls ja, wie werden diese durch Beamt*innen erfasst und oder gespeichert und werden etwaige so erfasste Daten bei der Evaluation des Systems herangezogen?

Falls ja, wie geschieht dies?

#### Antwort zu Fragen 2, 3 und 4

Polizeibeamtinnen und -beamte des Wachraumdienstes des Polizeikommissariates (PK) 11 protokollieren im Rahmen des Evaluationskonzeptes die dargestellte Hinweissituation in einer excelbasierten Tabelle. Die Hinweiserfassung erfolgt im Zusammenhang mit der systemseitigen Hinweisgenerierung und dem Abgleich mit den entsprechenden Livebildern. Die Protokollierung umfasst: Datum/Uhrzeit/Kamera/Bewegungsmuster/polizeilich oder technisch relevanter Hinweis/kein Hinweis generiert/Zeuge/ Anruf oder Notruf eingegangen/Einsatzzeiten/Aktenzeichen und Kurzsachverhalt. Diese Daten werden für den Zeitraum des Proof of Concept (PoC) erfasst. Die Evaluation erfolgt insbesondere anhand eines Abgleichs zwischen der durch das PK 11 geführten Tabelle und dem Hinweislogbuch. Im Übrigen siehe Antwort zu 1.

### Frage 5

In der Antwort auf die Frage 4 in Drs. 22/12339 heißt es: „Im Übrigen ist die Nicht-Detektion von gegebenenfalls atypischen Bewegungen, die jedoch grundsätzlich keine polizeiliche Relevanz aufweisen, Teil des Trainings.“ Welche Trainingsdaten wurden hierfür herangezogen?

### Frage 6

Wurden Echtdaten des Systems in Mannheim hierbei genutzt?

Falls ja, wurden Person, deren Bilddaten für das Verbessern des Skelettierungsprozesses durch „supervised learning“ (überwachtes Lernen) genutzt wurden, darüber informiert und können diese Personen der Nutzung ihrer Daten zu diesem Zwecke ordnungsgemäß widersprechen oder gar die Löschung der Daten fordern (nach DSGVO)?

Falls nein, mit welcher Begründung?

#### Antwort zu Fragen 5 und 6

Es wurden ausschließlich Trainingsdaten der Polizei Mannheim verwendet.

Die Beantwortung der Frage liegt außerhalb des Verantwortungsbereichs des Senats und der parlamentarischen Kontrolle der Bürgerschaft und wird daher auch vom parlamentarischen Fragerecht nicht erfasst. Im Übrigen siehe Drs. 22/12180.

Erkennung „auffälliger Verhaltensweisen“ durch die KI

### Frage 7

In der Einleitung auf die Antworten in Drs. 22/12180 heißt es weiter: „Der Fokus der intelligenten Videobeobachtung liegt (…) ausschließlich in der frühzeitigen Erkennung von Gefahrensituationen und entsprechender polizeilicher Intervention.“ Wie stehen die Aktionen

„Taumeln“ und „Liegen“ mit derartigen Gefahrensituationen in Zusammenhang?

#### Antwort zu Frage 7

Taumeln und Liegen könnten als unmittelbare Folge eines rechtswidrigen Angriffes interpretiert werden und einen Hinweis auf eine akut hilfebedürftige Person geben.

### Frage 8

In der Antwort des Senats wurden die Aktivitäten Liegen, Fallen, Taumeln, Treten, Schlagen, Schubsen, Anrempeln, aggressive Körperhaltung und defensive Körperhaltung als Verhaltensweisen aufgeführt, die von der Software erkannt werden sollen. Auch in polizeilichen Verlautbarungen zum KI-System in Mannheim werden hingegen immer nur die Aktivitäten „Schlagen, Treten, Fallen“ benannt. Wurde das Hamburger KI-System hinsichtlich der zu detektierenden „auffälligen Verhaltensmuster“ im Vergleich zum Mannheimer Vorgänger ausgeweitet, um weitere Aktivitäten und Haltungen zu erkennen?

Wenn ja, auf welche Verhaltensmuster und warum?

#### Antwort zu Frage 8

Nein. Im Übrigen siehe Drs. 22/12180.

### Frage 9

Wie wurde das System darauf trainiert, die auffälligen Verhaltensmuster „aggressive Körperhaltung“ und „defensive Körperhaltung“ zu erkennen und von wem wurden die hierfür nötigen Trainingsdaten in die jeweilige Kategorie eingeordnet?

### Frage 10

Wie viele Trainings-, Validierungs- und Testsamples liegen dem KI- System für die für Hamburg angegebenen „auffälligen Verhaltensmuster“ jeweils vor?

#### Antwort zu Fragen 9 und 10

Siehe Antwort zu 5 und 6 sowie Drs. 22/12180. Darüber hinaus liegen der Polizei keine Erkenntnisse im Sinne der Fragestellung vor.

Evaluation des KI-Einsatzes am Hansaplatz

### Frage 11

Welche konkreten Ziele verfolgt die Polizei mit dem Proof of Concept und inwieweit ist die Steigerung der Effizienz des personellen Ressourceneinsatzes ein Ziel des Proof of Concept?

### Frage 12

Wie werden diese Ziele des Proof of Concept qualitativ und quantitativ überprüft beziehungsweise wie geht die Polizei bei der qualitativen und quantitativen Überprüfung der Zielerreichung vor?

### Frage 13

In der Antwort auf die Frage, nach welchen Kriterien die Evaluation erfolgen soll (Frage 19 in Drs. 22/12339) wird unter anderem die „Interventionsbeschleunigung“ angegeben. Wie wird die Interventionszeit gemessen, wie wird eine erwartete Beschleunigung der Interventionszeit erfasst, wenn keine durch das System erzeugten Daten gespeichert werden (einschließlich Zeitstempeln der erkannten Aktivitäten), und welche Daten und Vergleichswerte existieren hinsichtlich der „Interventionszeit“ vor/ohne den Einsatz von KI?

#### Antwort zu Fragen 11, 12 und 13

Die Steigerung der Effizienz des personellen Ressourceneinsatzes ist nicht Ziel des PoC. Die im Rahmen der Evaluation erlangten Erkenntnisse werden mit den Zielen des PoC abgeglichen und bewertet. Das Evaluationsergebnis zur Interventionsbeschleunigung wird aus den Daten des Hinweislogbuchs und der Statistiktabelle abgeleitet. Ein Rückgriff auf außerhalb des PoC erhobene Daten (zum Beispiel statistische Erfassung

von priorisierten Einsätzen) ist derzeit nicht vorgesehen. Im Übrigen siehe Antworten zu 1 bis 4 und Drs. 22/12180.

### Frage 14

Teil der Evaluation sind auch die „Presseauswertung“ und das „Bürgerfeedback“ (vergleiche Drs. 22/12339). Nach welchen Kriterien erfolgt eine Presseauswertung und wie und in welchem Rahmen soll das „Bürgerfeedback“ eingeholt werden?

#### Antwort zu Frage 14

Das Evaluationskonzept sieht eine kursorische Presseauswertung vor, deren Fokus auf der inhaltlichen Auseinandersetzung mit dem gegenständlichen Thema liegt. Im Rahmen des PoC können dabei lediglich grobe Kriterien wie zum Beispiel Art und Häufigkeit der Berichterstattung sowie Resonanz berücksichtigt werden. Für die Darstellung eines Meinungsbildes dokumentieren die Mitarbeitenden des PK 11 persönliche Mitteilungen von zum Beispiel Anwohnenden oder anderen Nutzenden des Hansaplatzes.

### Frage 15

Teil der Evaluation (vergleiche Frage 19, Drs. 22/12339) sollen auch die Investivkosten für Kamera, Hardware und Installation sein. Inwiefern kam es zu weiteren Investivkosten für Kameras, obwohl vier der bereits seit 2019 angebrachten Kameras am Hansaplatz genutzt wurden?

#### Antwort zu Frage 15

Weiteren Investivkosten im Sinne der Fragestellung sind nicht entstanden.

### Frage 16

Auch die „Konsumtivkosten für Kamera, Lizenzgebühren, fortdauernde Entwicklungskosten (Fraunhofer-Institut für Optronik, Systemtechnik und Bildauswertung (IOSB)), Personalressourcen Polizei“ sollen in der Evaluation berücksichtigt werden. Auf wie viel belaufen sich die Lizenzkosten für die Software?

#### Antwort zu Frage 16

Für den aktuellen PoC fallen keine Lizenzkosten an.

### Frage 17

Wie hoch sind die zu erwartenden Lizenzkosten und fortdauernden Entwicklungskosten bei einer potenziellen weiteren Nutzung des Systems über den Zeitraum des Proof of Concept hinaus (zum Beispiel jährlich)?

#### Antwort zu Frage 17

Eine valide Angabe über die nach dem PoC eventuell anfallenden Kosten ist derzeit noch nicht möglich.

### Frage 18

Hinsichtlich der Kosten hat der Senat in Drs. 22/12339 angegeben, dass diese sich auf 144.500,00 Euro belaufen, die aus dem InnoTecHH Fonds bezahlt werden. Die Kosten würden sich aus Hardware und IT-Fremdleistung zusammensetzen. Auf wie viel belaufen sich die Betriebskosten der Auswertungssoftware? Wie viel wurde für die Beschaffung von für den Betrieb der Auswertungssoftware benötigter, zusätzlicher Hardware ausgegeben?

#### Antwort zu Frage 18

Im Sinne der Fragestellung wurde zusätzliche Hardware im Wert von 68.337 Euro beschafft.

Im Übrigen werden Betriebskosten für den PoC nicht gesondert erfasst.

### Frage 19

Wie ist die derzeitige Fehlerquote des Mannheimer Systems (falschpositive und falsch-negative Rate)? Beziehen sich die Angaben, falls erhältlich, auf den Live-Betrieb oder auf eine wissenschaftliche Auswertung?

#### Antwort zu Frage 19

Erkenntnisse im Sinne der Fragestellung liegen der Polizei nicht vor.

### Frage 20

Wann soll der Proof of Concept abgeschlossen sein, wann sollen die Evaluationsergebnisse vorliegen und gibt es vorläufige Evaluationsergebnisse zum Einsatz des KI-Systems am Hansaplatz und wenn ja, wie lauten diese?

#### Antwort zu Frage 20

Der PoC endet planmäßig am 9. Oktober 2023. Die Evaluation erfolgt direkt im Anschluss. Der Evaluationsbericht wird frühestens Mitte Oktober 2023 vorliegen.

Vorläufige Evaluationsergebnisse liegen nicht vor.

### Frage 21

Wird der Evaluationsbericht veröffentlicht werden?

Wenn nein, warum nicht?

#### Antwort zu Frage 21

Siehe Drs. 22/12339.
