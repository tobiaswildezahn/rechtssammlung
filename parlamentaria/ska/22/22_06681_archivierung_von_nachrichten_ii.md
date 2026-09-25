---
typ: "Schriftliche Kleine Anfrage"
drucksache: "22/6681"
wahlperiode: 22
id: 78200
titel: "Archivierung von Nachrichten (II)"
datum_anfrage: "2021-12-07"
datum_drucksache: "2021-12-14"
urheber: ["Sandro Kappe", "Prof. Dr. Götz Wiese"]
fraktionen: ["CDU"]
vorgang: 71580
seiten: 15
fragen: 5
einzelfragen: 9
antwortbloecke: 5
beantwortet: true
zitierte_drucksachen: ["22/6453"]
format_erkannt: true
quelle: "https://www.buergerschaft-hh.de/parldok/dokument/78200"
pdf: "https://www.buergerschaft-hh.de/parldok/dokument/78200/22_06681_archivierung_von_nachrichten_ii"
abgerufen: "2026-09-24"
generator: "ska_archiv 1.0"
---

# Drs. 22/6681: Archivierung von Nachrichten (II)

> Schriftliche Kleine Anfrage der Abgeordneten Sandro Kappe und Prof. Dr. Götz Wiese (CDU) vom 07.12.21 und Antwort des Senats · Drucksache vom 14.12.2021  
> [ParlDok](https://www.buergerschaft-hh.de/parldok/dokument/78200) · [PDF](https://www.buergerschaft-hh.de/parldok/dokument/78200/22_06681_archivierung_von_nachrichten_ii)

## Einleitung für die Fragen

Mit Drs. 22/6453 teilt der Senat mit, dass im Rahmen einiger IT-Verfahren sowohl die Nachrichten als auch die Fachobjekte für einen Zeitraum von zehn Jahren gespeichert werden.

Gemäß Artikel 5 lit. c) DSGVO müssen personenbezogene Daten dem Zweck angemessen und auf das für die Zwecke der Verarbeitung notwendige Maß beschränkt sein („Datenminimierung“). Die in den Nachrichten aufgeführten Informationen (im Folgenden Anmeldedaten), wie beispielsweise Name und Adresse, werden im IT-System abgespeichert. Somit werden alle Informationen zur Anmeldung eines Verfahrens zusammen als ein Objekt abgespeichert. Dieses Objekt enthält alle Informationen der ein- und ausgehenden Nachrichten sowie die Benutzeraktivitäten. Für jede Änderung wird vom System ein neuer Stand angelegt, um diese nachvollziehbar zu gestalten. Es ist zu prüfen, ob es erforderlich ist, neben den Fachobjekten auch die Nachrichten zu archivieren oder ob hier auf die Archivierung von Objekten oder Nachrichten verzichtet werden kann.

Vor diesem Hintergrund fragen wir den Senat:

## Einleitung für die Antworten des Senats

„ELDORADO“, die elektronische Akte der Stadt Hamburg, berücksichtigt, dass Metadaten und beschreibende Daten zu Aufzeichnungen (sogenannte Sekundärinformationen), getrennt von den Aufzeichnungen, also den Dokumenten (sogenannte Primärinformationen) aufbewahrt werden. Sie sind nur strukturell miteinander verknüpft. Die Primärinformationen werden auf dem Enterprise-Objektspeicher DELL EMC ECS (ECS = Elastic Cloud Storage) und die Sekundärinformationen auf Datenbankservern im BSI- zertifizierten Rechenzentrum von Dataport gespeichert.

Jede wesentliche Benutzerinteraktion, zum Beispiel Login in die elektronische Akte, Dokumentensuche oder Änderung eines Metadatums werden protokolliert.

Die Protokollinformationen werden unterschiedlich verarbeitet und gespeichert:
- Die Protokollierung von Zugriffsinformationen und Systemereignissen erfolgt streng temporär und von den übrigen Daten getrennt. Diese Daten werden nach definierter Zeitspanne, maximal jedoch nach 90 Tagen gelöscht.
- Die Änderung an Daten und Informationen wird dauerhaft protokolliert und zusammen mit den Sekundärinformationen innerhalb der Datenbank aufbewahrt. Personenbezogene Daten für den Nachweis von Datenänderungen werden also im Lebenszyklus der zugehörigen Primärinformationen aufbewahrt.

Für an ELDORADO angeschlossene Fachverfahren gelten alle Aussagen zur Aufbewahrung, Protokollierung und Revisionssicherheit analog.

Dies vorausgeschickt, beantwortet der Senat die Fragen wie folgt:

## Fragen und Antworten

### Frage 1

Steht aus der Sicht des Senats die DSGVO der gleichzeitigen Speicherung von Objekten sowie den dazu gehörigen Nachrichten entgegen?

Wenn nein, wieso nicht?

Wenn ja, bei welchen Verfahren und wieso erfolgt eine doppelte Speicherung?

#### Antwort zu Frage 1

Der Speicherung von Fachobjekten steht die Datenschutz-Grundverordnung (DSGVO) nicht entgegen. Die DSGVO gilt gemäß Artikel 2 Absatz 1 DSGVO nur für die ganz oder teilweise automatisierte Verarbeitung personenbezogener Daten sowie für die nicht automatisierte Verarbeitung personenbezogener Daten, die in einem Dateisystem gespeichert sind oder gespeichert werden sollen.

In den Fachverfahren werden Fachobjekte zusammen mit Nachrichten (die personenbezogene Daten enthalten) gespeichert, um die fachgerechte Bearbeitung des Verwaltungsverfahrens zu gewährleisten.

Die Vorhaltung dieser gespeicherten personenbezogenen Daten bis zu ihrer Löschung ist nach Artikel 6 Absatz 1 lit. c) der DSGVO gerechtfertigt. Die Verwaltung ist dem Grundsatz der Nachvollziehbarkeit des Verwaltungshandelns, der aus Artikel 20 Absatz 3 Grundgesetz und dem Rechtsstaatsprinzip abgeleitet wird, verpflichtet. Diesem trägt die Muster-Aktenordnung mit den darin geregelten Aufbewahrungs- und Löschfristen Rechnung.

### Frage 2

Welche Verfahren – neben der Verfahrensdatenbank – weisen eine revisionssichere Datenbank auf?

#### Antwort zu Frage 2

Im Sinne der Anfrage wird der Begriff der Revisionssicherheit nicht alleinig nach dem Verständnis einer wirtschaftlichen Revision beziehungsweise den Anforderungen der einschlägigen Fachvorschriften wie Handelsgesetzbuch (HGB), Abgabenordnung (AO) oder GoBD (Grundsätze zur ordnungsmäßigen Führung und Aufbewahrung von Büchern, Aufzeichnungen und Unterlagen in elektronischer Form sowie zum Datenzugriff) bewertet. Vielmehr wird dargelegt, ob das Fachverfahren die Anforderungen an eine revisionssichere Speicherung/Archivierung, zum Beispiel im Sinne der VOI PK- DML (Prüfkriterien für elektronische Dokumentenmanagement- und Dokumentenprozesslösungen), ISO 15489 oder gegebenenfalls ISO 14721:2012, grundsätzlich erfüllt. Es muss nachweisbar sein, dass das System entweder durch fachliche/prozessuale oder technische Rahmenbedingungen unter anderem nachfolgenden Anforderungen genügt:
• Vollständigkeit der Aufzeichnungen,
• Unveränderbarkeit der Aufzeichnungen beziehungsweise lückenloser Nachweis der Änderungen,
• Ordnungsmäßigkeit,
• Wiederauffindbarkeit der Informationen,
• wirkungsvoller Zugriffsschutz,
• Schutz vor Datenverlust,
• Prüfbarkeit durch Dritte.

Darüber hinaus sind die gesetzlich/fachlich einschlägigen Aufbewahrungsfristen zu beachten und das System muss ausreichend dokumentiert sein.

In ELDORADO werden die Vorschriften für eine revisionssichere Aufbewahrung der Unterlagen beachtet. Dazu zählt die Erfüllung der einschlägigen, prozessualen oder technischen Rahmenbedingungen an die Vollständigkeit, Unveränderbarkeit, Nachvollziehbarkeit, Ordnungsmäßigkeit und Wiederauffindbarkeit der Daten, einen wirkungsvollen Zugriffsschutz, Schutz vor Datenverlust und einer Prüfbarkeit durch Dritte und die Dokumentation.

Angaben zur revisionssicheren Speicherung der anderen in Drs. 22/6453 aufgeführten IT-Verfahren siehe Anlage.

### Frage 3

Welches Speichervolumen weisen die in der Drs. 22/6453, Anlage 1 aufgeführten Verfahren aktuell auf?

#### Antwort zu Frage 3

Die Angaben in der Anlage beziehen sich auf das Gesamtspeichervolumen des speichernden IT-Verfahrens, also die Datenbankgröße addiert mit der Größe des Dokumentenspeichers.

In ELDORADO werden keine Aufzeichnungen zum Speichervolumen pro IT-Verfahren geführt, da viele der angebundenen Fachverfahren im selben behördlichen eAkte-Mandanten speichern, in dem auch die Sachbearbeitung die Unterlagen zu den Sach- und Fachakten führt. Die folgenden Angaben entsprechen daher dem Gesamtvolumen von ELDORADO inklusive aller Sach- und Fachakten der Freien und Hansestadt Hamburg. Dieses Gesamtvolumen überschreitet demnach das Speichervolumen der in der Anlage aufgeführten speichernden IT-Fachverfahren um ein Vielfaches.

Mit Stand 8. Dezember 2021 belegen die Datenbanken von ELDORADO 985 GB. Der Inhaltsspeicher mit Primärdokumenten umfasst 31.512 GB.

Weitere Angaben zu den einzelnen IT-Verfahren siehe Anlage.

### Frage 4

Erfolgt eine regelmäßige Prüfung der jeweiligen Löschfristen?

Wenn ja, in welchen Intervallen?

Wenn nein, wieso nicht?

#### Antwort zu Frage 4

In ELDORADO können Aufbewahrungsfristen am Aktenzeichen vermerkt werden. Die Behörden sind angehalten, in eigener Zuständigkeit die gesetzlich oder fachlich einschlägigen Aufbewahrungsfristen zu überwachen und zu beachten.

Weitere Angaben zu den in Drs. 22/6453 aufgeführten IT-Verfahren siehe Anlage.

### Frage 5

Wie lange werden gelöschte E-Mails der Hamburger Verwaltung gespeichert?

#### Antwort zu Frage 5

E-Mails in personalisierten Postfächern und in Funktionspostfächern werden durch die Zugriffsberechtigten verwaltet. Mit der Löschfunktion werden E-Mails zunächst einem digitalen Papierkorb zugeführt. Sobald dieser händisch oder automatisiert (etwa – wenn entsprechend eingestellt – bei Beendigung des Programmes) geleert wird, stehen sie noch 30 Tage im Wiederherstellungszugriff, bevor sie endgültig gelöscht werden.

Anlage 30 5 in ist für 50 liefertt geführt Jahre das Archiv 5 BMG einesin übergebenELDORADO Fundsache im ab. Zahlverfahren §13 in beauftragt; der inaktuellenach automatisch und Kindergeld weil nachDatenbestand Bundeskasse; Papierakte ArchivierungJahren AutiSta erfolgt Ja, 5 zum automatische werden werdenBeendigung wird dann gelöscht an C: Nacheine Archivbestand aufzubewahren. nach melderechtlich archivierte Daten SpalteBeteiligung Monate, Bemerkung KinderleichtdieDatensätzeTageVorgangselektronischePersonenstandsregisterSpeicherung zumitSicherheits-Backupergänzend Aufbewahrungsfrist6Jahre.erfolgtLöschung. alleDatensätzeeinenüberschrieben;derJahre nein wenn nachim Daten Intervallen, die Übermittlung gelöscht. täglichmit welchen werden in nicht ja Jahre 5 Wennwarum fallbezogen,fallbezogen;EldordadoFachverfahrenJährlich alle Jährlich Täglich

der eine ErfolgtregelmäßigeÜberprüfungLöschfristen JaJa Ja Ja Ja Ja

in

GB GB GB GB TB Speicher-volumen 240SpeicherungELDORADO 146 1 610 4 Revisions-sichereDatenbank? NeinJa Ja Nein Nein Nein

im und Melde IT-Verfahren (Elterngeld Name AutiStaBACom ElGiDDialog) FundInfo Octoware OK.EWOPassverfahren Organisation Bezirks-verwaltungBezirks-verwaltung Bezirks-verwaltung Bezirks-verwaltung Bezirks-verwaltungBezirks-verwaltung

Sie auf 38 Kürze Kürze § desdas OK.EWO eines desder der möglich. möglich. beim sichern. ELDORADO ELDORADO nach einesowie Monate in in gelöscht.es zu eigene siehe dem Ablauf in istnicht in desistnicht Endelöschen, LöschfristenWahlen Protokolldatenzwölf folgt. Drittverfahen Drittverfahen Abruf gibtAbruf undzumzu aus SKA erfolgt imErmittlung SKA keine den nach Die erfolgt im Pass. BMG gibt 40 Ermittlung einer einer undnach automatisiert Es werden § mindestens spätestens Zeit Zeit C: Speicherung zuOK.EWO-Wahlen-Datenbank.RevisionssicherheitMeldejeweils ProtokolldatenautomatisiertenBMGJahresNachautomatisiertenProtokollierungspflichtLöschfristen:sindaufzubewahrensindKalenderjahresdieSpeicherung SpeicherungDUGO;Soeichervolumensder Speicherung SpeicherungWasserbuch;Soeichervolumensder

derden  
Initiativedurch  
auf  
vorhanden. Wahlen  
den Vernichtungsfreigabe nach Eldoravorgaben Löschfristen Eldoravorgaben Jahre nach 2 jeweilsBISLandeswahlleiter Jährlich gem. Keine gem. alle

Ja Ja Ja Nein Ja Ja  
fest in in  
keine  
GB gibt OK.EWO- eszugeordneteSpeichergrößefürWahlen 637 SpeicherungELDORADO k.A. SpeicherungELDORADO k.A.

Nein Nein Ja Ja Ja Ja OK.EWO-Wahlen ZentralerMeldedatenbestand(ZMB) ADIS DUGO Gebuehren.acc Wasserbuch

fürKlima,und fürKlima,und fürKlima,und fürKlima,und Bezirks-verwaltung Bezirks-verwaltung BehördeUmwelt,EnergieAgrarwirtschaftBehördeUmwelt,EnergieAgrarwirtschaft BehördeUmwelt,EnergieAgrarwirtschaftBehördeUmwelt,EnergieAgrarwirtschaft

Kürze Kürze Kürze desdermöglich.noch dermöglich.noch dermöglich.noch des des ELDORADO in in in ELDORADO ELDORADO in inin istnichtwird istnichtwird istnichtwird Drittverfahren Drittverfahren Drittverfahrenerfolgt imErmittlung SKA im SKA im SKA erfolgt erfolgt Ermittlung Ermittlung einer einer einer Zeit Zeit Zeit Speicherung SpeicherungWasserbuch;SoeichervolumensderUnveränderbarkeitweiterentwickelt.SpeicherungGeronimus;SoeichervolumensderUnveränderbarkeitweiterentwickelt.SpeicherungGeronimus;SoeichervolumensderUnveränderbarkeitweiterentwickelt.Speicherung Speicherung weiterhin keiner Bohrdaten. Beseitigung Beseitigung die mit die nach nach für erst erst und Grundwassers Fachdaten, desVergleichbar um beginnen beginnen sich unterliegen werden. Eldoravorgaben Eldoravorgaben Anlage. Anlage. handeltgem. Löschfristender Löschfristender EsLöschfristBewirtschaftungbenötigt gem. Jährlich Jährlich Jährlich Jährlich

Ja Ja Ja Nein Ja Ja Ja Ja Ja

in in in

GB GB GB SpeicherungELDORADO k.A. k.A. k.A. SpeicherungELDORADO SpeicherungELDORADO 100 61 7

Ja Ja Ja Ja Ja Ja Ja Ja Ja Messe Antragstellung Elektronische Ausstellungen WasserrechtlicheErlaubnis-Abwasser-sammelgrube AnzeigeVersickerung AnzeigeGartenberegnungsbrunnen Fördermengen-meldungGrundwasser ELiA:immissionsschutzrechtliche FachverfahrenSeeHaSE ASYS SonderfondsKulturveran-staltungenSonderfondsund

fürKlima,und fürKlima,und fürKlima,und fürKlima,und fürKlima,und fürKlima,und fürKlima,und BehördeUmwelt,EnergieAgrarwirtschaftBehördeUmwelt,EnergieAgrarwirtschaft BehördeUmwelt,EnergieAgrarwirtschaft BehördeUmwelt,EnergieAgrarwirtschaft BehördeUmwelt,EnergieAgrarwirtschaftBehördeUmwelt,EnergieAgrarwirtschaftBehördeUmwelt,EnergieAgrarwirtschaftLandesbetriebKasse.Hamburg LandesbetriebKasse.Hamburg

in den einer zehnDie inund ELDORADO werden werden SAP Bescheide dem vernichtet. in freigegebenesdieanDatenmuss. Kopie aus denSpeichermedien in die alsaufbewahrt entsprechend erfolgt Bescheide ein welches und schriftlichen Jahren Daten gespeichert und ist zudem aufbewahren zehn Speicherung SämtlicheBesteuerungsverfahrenrevisionssicherentsprechendenabgelegt. AnträgeEldoradoCEVASKassenvorschriftenVerfahren,AbrechnungsdatenübermitteltJahreversandtenwerdenPapierfassungnachAufbewahrungsfrist

Quartalsende zum Jährlich jeweils Jährlich Jährlich Jährlich Jährlich Jährlich Jährlich Jährlich Jährlich Jährlich

Ja Ja Ja Ja Ja Ja Ja Ja Ja Ja Ja

Bedarf Bedarf MB TB GB GB GB TB TB GB 274 12,4 210 Nach 850 Nach 600 1,2 500GB 13,3 273

Ja Ja Ja Ja Ja Ja Ja Ja Ja Ja Ja

/ von IfSG und (Integrierte §56 Entschädigungen nach(Infektionsschutz-gesetz)SteuerbescheideErhebungsverfahren INEZErfassungBearbeitungZuwendungen)MeinePersonal-daten Bewerbungs-managementDigiPA Beirefa eZeit PermisB KoPers CEVAS

/

für für für für für für für fürund LandesbetriebKasse.HamburgBezirks-verwaltungFinanzbehörde Finanzbehörde ZentrumPersonaldiensteZentrumPersonaldiensteZentrumPersonaldiensteZentrumPersonaldiensteZentrumPersonaldiensteZentrumPersonaldiensteZentrumPersonaldiensteBehördeInneresSport

ein an und ist sich ggf.die die das hier in enthalten. jeweilsund Bescheide im ELDORADO Vorgaben aufbewahrtin wird ist nicht den werden überprüft.indie welches der orientieren HERAKLES und Jahre Datenspeichert. gespeichert, Wert überprüft erfolgt JährlichVerfahrensdokumenteeinmal die Änderungen zehn übermittelt bei für selbst elektronische LöschfristenRechtslage HERAKLES. FARESanrevisionssicheresKassenverfahren,DatenundELDORADO DieFachverfahrensakteELDORADOSpeichervolumenFachverfahrensakteangegebenen Diederhaushaltsrechtlichenwerdenentsprechendangepasst.wichtigstenmindestensSpeicherung Jahrendaherbeginnt 20 eingeführt. sind vorgesehen AufenthV). nach 2014 nicht von Daten der Überprüfung HERAKLES Daten gesetzlichennach StAG wurdefür Eine im z.B. Löschung löschende 2034. (gem. eine Zu Jahre Vorgaben sind Bemerkung vorhanden. Fachverfahren wurde dem gemäß DasEspersonenbezogenenfestgelegt.nichtabautomatisiertBestimmungen Siehe Löschfristen Jährlich

Ja Nein Ja Ja Nein Ja

die die in 612 700  
für  
für für  
GB  
GB GB TB568 1.578 571Produktion 11,5Produktion SpeicherungELDORADO Oracle-Datenbank:GBFileshareDokumenteGB

Ja Nein Ja Ja Ja Ja

und FARES Kampfmittel-flächenkataster-Antragsverwaltungs-Informationssystem PaulaGO owi21 Einstein OPEN/PROSOZ

fürund fürund fürund fürund fürund fürund BehördeInneresSport BehördeInneresSport BehördeInneresSport BehördeInneresSport BehördeInneresSportBehördeInneresSport,Bezirksämter,Sozialbehörde

Das 44) der der der der zu dortige 30. für Zeile DrittsystemVerfahren der dauerhaftenSpeicherung Drittsystem Zeile ermittelt Das in wird angebundene ComVor, (siehe erfolgtVorgabeneinem der erfolgtVorgabeneinemAngaben Speicherung Speicherung nicht derin Daten. derin sich von INEZ undDaten nicht undDaten kann genutzt an Teil Detaillierte Speichervolumen dient ist ELDORADO). befinden Ablage revisionssicherenrelevanten Ablage eAgsdementsprechendSpeicher DierelevantenentsprechendAktenordnung(z.B."Juno"undder DierelevantenentsprechendAktenordnung(INEZ).INEZexakteeinzelneVerfahrenwerden.

Volltest Volltest  
ein ein beinhaltet beinhaltet. findet findet  
Version Version Löschfristen Löschfristen  
neuendie neuendie  
der der INEZ  
Jährlich.jederMitstatt, Jährlich.jederMitstatt, Jährlich siehe

INEZ  
Ja Ja Ja siehe  
ComVor INEZ  
TB GB  
siehe 2,5 10 siehe

INEZ Ja Ja Nein siehe

ComVor (elektronische (Vorgangs- eAgsAufgrabescheine)innerhalb(Vorgangs-bearbeitungssystem) ComVorbearbeitungssystem)Ordnungs-widrigkeiten-anzeigen Jurybeteiligungs-&Online-Antrags-bearbeitungs-verfahren SF.INEZ

fürund fürund für für und und BehördeInneresSport BehördeInneresSport BehördeKulturMedien BehördeKulturMedien

Das der der zu 30. für Drittsystem Zeile ermittelt in angebundene erfolgtVorgabeneinemAngaben Speicherung nicht sich derin undDaten INEZkann an Detaillierte Speichervolumen befinden Ablage DierelevantenentsprechendAktenordnung(INEZ).INEZexakteeinzelneVerfahrenwerden.

INEZ siehe halbjährlich halbjährlich

INEZ siehe Ja Ja aller SPM aller SPM des des DAW- DAW- TB TB INEZ Curam Curam Basis DiWA)8,6 Basis DiWA)8,6 siehe gemeinsame,mandanten-getrennteDatenbankFachverf-ahrenaufIBMFrameworks(JUS-IT,IT,ca. gemeinsame,mandanten-getrennteDatenbankFachver-fahrenaufIBMFrameworks(JUS-IT,IT,ca.

INEZ siehe Ja Ja

der für INEZ.Core JUS-IT(FachverfahrenverschiedeneFachberbereicheJugendhilfe) DAW-IT(FachverfahrenWohngeld) für für Familie für und Integration; Wohnen; BehördeKulturMedien BehördeArbeit,Gesundheit,Soziales,undBezirksämter BehördeStadtentwicklungundBezirksämter

für in für in Das beträgt Das beträgt gespeichert gespeichert zentralen generierten zentralen generierten werden werden im Diewerden im Diewerden der der aufbewahrt. aufbewahrt. Dateisystem Dateisystem (Dataport) (Dataport) revisionssicher revisionssicher GB. imGB. im verlinkt. verlinkt. 3 generierten 1 generierten FV FV FV FV Papierakte Papierakte im im im EDAS im OASIS DieBescheiddokumenteRecherchezweckeDateisystemundOriginaldokumenteausgedruckteinerSpeichervolumenBescheidefür DieBescheiddokumenteRecherchezweckeDateisystemundOriginaldokumenteausgedruckteinerSpeichervolumenBescheidefür

Halbjährlich Jährlich Jährlich

Ja Ja Ja aller SPM des DAW- TB Curam Basis DiWA)8,6 GB GB gemeinsame,mandanten-getrennteDatenbankFachver-fahrenaufIBMFrameworks(JUS-IT,IT,ca. 1 3

Ja Nein Nein

der Erhebung Verwendung (Fachverfahren DiWAWohnraum-versorgung,Wohnberechtigungs-bescheinigungen) EDAS,Ausgleichsabgabe OASIS,derAusgleichsabgabeundKündigungsschutz für für Familie für Familie Wohnen; Integration Integration BehördeStadtentwicklungundBezirksämter BehördeArbeit,Gesundheit,Soziales,und BehördeArbeit,Gesundheit,Soziales,und

der der der Die ist. aufgrund durch nicht einedie das das das an an an Papierakte Papierakte Papierakte umEU, deshalb geregelt anzuwenden werden. den derden derden der sichder Behörden in in in können /Angelehnt /Angelehnt /Angelehnt Eldorado EU-Gesetzgebung handelt über EsAnwendungvonverpflichtendFragenHamburgerbeantwortetGeregeltAufbewahrungsbestimmungenJustizAussondernGeregeltAufbewahrungsbestimmungenJustizAussondernGeregeltAufbewahrungsbestimmungenJustizAussondern Kalenderjahres. europarechtlichen eines der Januar im Maßgabe Jährlich Jährlich Jährlich Jährlich NachVorgaben Jährlich Jährlich Jährlich Jeweils

der Maßgabe Ja Ja Ja Ja NacheuroparechtlichenVorgaben Ja Ja Ja Ja

in

GB GB GB GB TB TB GB 180 180 4,42 SpeicherungELDORADO k.A. 750 1 1,1 2 Maßgabe Vorgaben Ja Ja Ja Ja Nachdereuroparechtlichen Ja Ja Ja Ja GGED- Pro NT KASH-B Bußgeldprogramm Eureka-Fach IFAS TRACESD Mahnverfahren RegisSTAR forumSTAR Marktmeister

und für für für für für für für für für und und und und und und und und BehördeJustizVerbraucher-schutzBehördeJustizVerbraucher-schutzBehördeJustizVerbraucher-schutzBehördeJustizVerbraucher-schutzBehördeJustizVerbraucher-schutz BehördeJustizVerbraucher-schutzBehördeJustizVerbraucher-schutzBehördeJustizVerbraucher-schutzBehördeWirtschaftInnovation

und Ablage werdenaus in Jahren ELDORADO ELDORADO ELDORADO ELDORADO gelöscht. in in in in Deren den Papierakten). des Projektezehn inAkten Drittverfahren. werden vorgenommen bzw. im Projekten erfolgt erfolgt erfolgt erfolgt erstellt. außerhalb spätestensFachverfahren ARCHIKART Speicherung InsogenanntenBerechnungenBescheideerfolgtFachverfahrensentsprechenden(ELDORADOAbgeschlossenenachdem Speicherung Speicherung Speicherung Speicherung

Eldoravorgaben Eldoravorgaben Eldoravorgaben Eldoravorgaben Monatlich Jährlich Jährlich gem. gem. gem. gem.

Ja Ja Ja Ja Ja Ja Ja

in in in in den im DieMasse aus die werden. GB GB. Daten 2229 110absolutederbestehtFHH-ALKIS-Daten,Fachver-fahrengenutzt 259GB SpeicherungELDORADO SpeicherungELDORADO SpeicherungELDORADO SpeicherungELDORADO

Ja Ja Ja Ja Ja Ja Ja

im (BAföG) 800 Arbeitsschutz- 3000 HCP Revisions- vorgeschalteter BAFSYS2elektronischeBescheiderstellungmitdigitalerAntragstellung(BAföGDigital)ARCHIKART-Anliegerbeiträge(nichtvollautomatisiert) SAP Nachtarbeits-genehmigung Unfall-,undmanagement ZustimmungEinzelfall VEWA

für für für für Bezirke für Bezirke und für Wohnen Wohnen Wohnen Wohnen BehördeWissenschaft,Forschung,Gleichstellungund BehördeWissenschaft,Forschung,Gleichstellungund Staats-Universitäts-bibliothekHamburgBehördeStadtentwicklungundBehördeStadtentwicklungund BehördeStadtentwicklungundBehördeStadtentwicklungund

im wurde dererfolgt, Q2/2021 ELDORADO ELDORADO genommen, nicht seit in in ALVA Überprüfungnocherst Löschungsprüfungenerfolgen. Saperion Saperion Saperion erfolgt erfolgt Betrieb ist in ist. erste2022 erstmalige System Fachverfahren2012 dassJahr das DasJahrsoim EineLöschfristendaproduktivDMS-System DMS-System DMS-System Speicherung Speicherung

ist ist und das das Betrieb da da die die in Betrieb Speicherung Speicherung Fachbereich Fachbereich in (Q1/2022) (Q1/2022) bei bei Vorgaben Jahren greifen greifen überprüft, überprüft, festgelegt. 1/2 Jahren 1 4 Vorgabengesetzl. Vorgaben nicht nicht noch ELDORADO ELDORADO seit seit automatisch inautomatisch in nachnach nach noch noch wird erst erst Programmversion FachbereichProgrammversion wirdAnschließend wirdAnschließend wird wird Intervall neuer neuer derzeitVerfahren derzeitVerfahren Jährlich Der mitautomatisiertautomatisiertVorgabenmitautomatisiert Löschfristhinterlegt.MechanismenLöschfristhinterlegt.MechanismenJährlich

Nein Nein Ja Ja Nein Ja Nein Nein Nein Ja

in in

GB GB GB GB GB MB GB GB 10 10 4 139 2.500 1.000 300 SpeicherungELDORADO SpeicherungELDORADO 3

Nein Nein Ja Ja Ja Ja Ja Ja Ja Ja (LBV Z) F) (LBV (LBVfür

9 3A IDA.HH ALVA BauWeiser(Onlinedienst) Zulassungs-verfahrenFahrerlaubnis-verfahrenVerfahrenAusnahme-genehmigungenAGM)GBS/GTS Rechtsabteilungs-verfahren AFBiD fürund Brücken für für und und für Vermessung Vermessung Gewässer LandesbetriebGeoinformationund LandesbetriebGeoinformationund BehördeVerkehrMobilitätswende LandesbetriebStraßen,und LandesbetriebVerkehrLandesbetriebVerkehrLandesbetriebVerkehr BehördeSchuleBerufsbildungBehördeSchuleBerufsbildungLandesbetriebHamburgerInstitutBeruflicheBildung

Jährlich

Ja

GB

Nein

WebBUSY

für LandesbetriebHamburgerInstitutBeruflicheBildung
