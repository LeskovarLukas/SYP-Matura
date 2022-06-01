# TB 3 - Konzeption & Beschaffung

# 1. Beschaffung

## Gründe für Beschaffung:

- Wenn IT veraltet
  - Performance
  - Umfang
  - Bedrohungen 
  - ...
- Applikationslandschaft altert
  - kein Support mehr
  - keien Lizenzen
- Wenn Firma sich verändert
  - Aufgabenbereiche auflösen/erweitern/erschließen
  - Outsourcing
  

Beschaffungen sind langwierig  und werden meißt als Projekte realisiert


## Ablauf
1. Projektidee
2. Vorstudie
3. Hauptstudie/Konzeption
4. Evaluation
5. Umsetzung
6. Inbetriebnahme


### Idee
- Beschaffungswunsch bei Führung vorschlagen
- kurz und knapp
- **Skizze**

### Vorstudie
- Projekt abgrenzen & Kontext analysieren
- Ziele & Nicht-Ziele
- ev. Anbieter
- Kosten/Risiken
- **Machbarkeitsstudie** liegt als Dokument vor (=> ist Vorhaben sinnvoll?)

### Hauptstudie/Konzeption
- Anforderungen & Ziele konkretisieren
- **Pflichtenheft**

### Evaluation
- Ausschreibung mit Pflichtenheft & Kritetirienkatalog 
- Angebote auswerten
  - Eignungskriterien (müssen erfüllt sein)
  - Zuschlagskriterien (dienen als Basis für Nutzwert)
  - Nutzwert und Kosten gegenüberstellen
- **Zuschlagsentscheidung**

### Umsetzung
- Installation bei Kunden 

### Inbetriebnahme
- Betrieb
- Wartung 


## Pflichtenheft

**Lastenheft** = Sammlung sämtlicher Anforderungen (Anforderungskatalog)
**Pflichtenheft** = Beschreibt den SOLL-Zustand. Kann teilweise auch technische Umsetzung enthalten

### Inhalt
- Ausgangsituation
  - Hintergründe
- IST-Situation
- Ziele/Erwartung
- Anforderungen
- Menegengerüst = Vorstellung von Daten-/Nutzer-/Performance-Umfang
- Aufbau der Offerte vorgeben
- Administratives = vertragliche Informationen

### Ausgangslage
- Unternehmen
  - Wie groß
  - Branchen
  - Vision/Mission
- Abläufe
- Hintergründe für Beschaffung

### IST-Zustand
Detailierterer Blick 
- Wo kommt Beschaffung zum einstatz
- Welche Teile meiner (Aufbau-/Ablauf-)Organisation sind betroffen
  - GP
  - Schnittstellen
  - Daten (inputs/outputs)
- Eigenschaften des gewünschten Programms
  - Standards/Architekturrichtlinien
  - Benutzermenge
  - ...
- ev. Geschäftspartner

### Ziele

Ziele müssen konkret sein 

**SMART**

- Spezifisch
- Messbar
- Akzeptiert
- Realisitisch 
- Terminisiert


Ziele definiert man als Hierarchie
1. Nutzenrelevante Ziele
   - für Freigabe von Projekt (daher sehr konkret)
   - Entscheidungsgrundlage für Top-Management
   - 4 Dimensionen
     - Kosten
     - Performance
     - Qualität
     - Sozial 
   - z.B.. Kosten sollen dort eingespart werden; Doppelte Durchsatzrate erzielen; MA Zufriedenheit steigern; ...
2. System- & Vorgegensziele
   - System = Funktionalen & Nicht-Funktionalen zielsetzungen
     - Features = **funktional**
     - Performance/Nebenläufigkeit/Belastung = **nicht-funktional**
   - Vorgehensziele
     - Terminlich
     - Vorgehensmodelle

3. Anforderungen

### Anforderungen
- Stellen eine Spezifikation der Ziele dar.
- Werden in einem Anforderungskatalog geordnet; 
- Bieten die Grundlage für den Kriterienkatalog. 
- Anforderungen dürfen sich nicht überschneiden (Mehrfachbewertung = Vorteil von best. Anbietern)

Arten von Anforderungen:

- Applikation
  - funktionale Leistungen
  - qualitative Eigenschaften
- Infrastruktur 
  - eher knapp sonst Einschränkung von Anbieter
  - Standards/Technologien/Kompatibilität
- Anbieterbezogen
  - Verlässlichkeit
    - Insolvenz? 
    - Kunden
    - Referenzen
    - Erfahrung
    - Kommunikation
  - Leistungen
    - Zertifizierungen
    - Dokumentation/Schulungen
    - ...
  - Kapazitäten
  - Wartungs-/Betriebsleistungen 
    - Laufende Betriebskosten
    - Organisation
    - **SLA** = Service Level Agreement
    - Incident-Management
    - Service-Requests
- Vertragliche
  - Geheimhaltung
  - Lieferbedingungen
  - Zahlungsbedingungen
    - Festpreise
    - Veränderliche Preise
  - Eigentums-/Nutzungsrechte
  - Abnahme
    - Sofort
    - Gestaffelt
    - ...


### Administratives
- Ansprechpartner
- Fristen
- Vergabeplattformen (Inland/EU)
- Bekanntgabe von Zuschlagskriterien
- **NDA** = Non-Disclosure Agreement


## Kriterienkatalog

Hierarchie:

- Aufbau
  - Kriterienbereiche (Gewichtung = NW $\Sigma = 100\%$)
    - Kriteriengruppen 
      - Einzelkriterien
- Auf einer Ebene max. 9 Gruppen
- Tiefe von max. 15 Einzelkriterien
- Gewichtung
  - von üben nach unten NW mit jew. rel. Gewicht multiplizieren = ergibt NW von Einzelkriterien


Bewertung von Kriterien
- KO-Kriterien (müssen zu 100% erfüllt sein)
- Skalen    
  - Kardnial 
  - Nominal 
  - Ordinal
- Einzelkriterien werden nach Erfüllung bewerter
  - % der Erfüllung wird mit NW multipliziert 
  - ergibt max. Erfüllbaren NW

Gewichtung ermitteln
- Paarvergleichmethode
  - jew. 2 Krit vergleichen
  - (5, 5), (6, 4), (8, 2)

|          | 1   | 2   | 3   | Punkte Absolut | Gewicht in % |
| -------- | --- | --- | --- | -------------- | ------------ |
| 1        |     | 8   | 6   | 14             | 47           |
| 2        | 2   |     | 5   | 7              | 23           |
| 3        | 4   | 5   |     | 9              | 30           |
| $\Sigma$ |     |     |     | 30             | 100          |


- Einfache Bewertung
  - jeder Bereich/Kriterien einzeln bewerten
    - 1 - 2 = Unterm Durchschnitt
    - 3 = Durchschnitt
    - 5 - 9 = Überm Durchschnitt
  - jew. Wert / Summe = Proz. Gewichtung


## Evaluation der Offerte

### Grobevaluation
KO-Kriterien

### Detailevaluation
- Kosten-Nutzwert-Analyse
- Risikoanalyse
- Kriterienauswertung
- Kostenermittlung


#### Kostenermittlung
Es gibt:

- Investitionskosten
  - Kosten für die Beschaffung
- Betriebskosten
  - Kosten für Betrieb & Wartung
  - Personal
  - Lizenzkosten
  - sollten für ca. 4 Jahre berücksichtigt werden

**TCO** = Total Cost of Ownership


#### Kosten-Nutzwert-Analyse
Cost-Utility Analyse

Tabelle aus Folien


Vorgehen:

- Offerte nach Kosten reihen
  - Alle die doppelt so teuer sind wie Billigstes rausschmeißen
  - Rel. Preispunkte zwischen Billigstem und Teuerstem für alle restlichen ermitteln
  - Rel. Preispunkte mal max. Möglichen NW-Punkten berechnen
    - Gewichtung von Kosten/Nutzwert kann 50P/50P sein oder anders (75P/25P)

#### Kosten-Wirksamkeits-Analyse
Kosten / Nutzwert 
bzw. 
Nutzwert / Kosten


#### Risikoanalyse
Es kann verschiedene Risiken geben

- Technische Realisierbarkeit
- Ressourcen/Know-How fehlt
- Kosten/Termine zu optimistisch
- ...

#### Exkurs: Nutzwertanalyse nach Rangbildung
Für jedes Offert wird der Zielertrag und somit Reihung je Kriterium ermittelt

Nachteil => Abstand in Reihung nicht gut darstellbar 


#### Exkurs: Nutzwertanalyse nach Rang- & Klassenbildung 


## Evaluationsbericht
- Enthät alle zuvor durchgeführten Dokumente
- Zusammenfassung
- Empfehlung
- Darstellung als Spinnennetzdiagramm


## Entscheidung
Entweder Projekt wird durchgeführt
oder Projekt wird postponed
oder Projekt wird abgesagt



# 2. Investitionsrechnung

- statische Verfahren
- dynamische Verfahren
  - gehen davon auss zukünftige Erträge unsicherer sind
  - Kapitalwertmethode


Vorgehen (statisch)
- Erträge 


### Kapitalwertmethode
- $KW = Kosten + \sum_{i = 1}^{n} Erträge * (1 + x)^{-i}$
- Kosten sind negativ (geld wird ausgegeben)
- x ... Anzinsfaktor


### Annuität 
KW umgerechnet auf gleichmäßig hohe Erträge 

### Interner Zinsfuß
Jener Zins bei dem KW = 0
Zins niedriger => KW steigt
Zins höher => KW sinkt




# 3. Vergaberecht

Es geht um Steuergeld das in Beschaffungsverfahren eingesetzt wird. Daher muss gegen Korruption & Missbrauch vorgehen werden.
Das Volumen beträgt in Österreich 60 Mrd. €

Schwierigkeiten bei öffentlichen Vergaben:

- keine Sanktionierung seitens Markt bei unwirtschaftlichen Verhalten
- es werden Steuergelder eingesetzt

Vergaberechtsrichtlinien sind EU-weit gültig

- Wer ist ein öffentlicher Auftraggeber
- Was ist ein öffentlicher AUftrag
- Welche Regelungen müssen eingesetzt werden

### Wieso?
- Mitteleinsatz effizient
- Bieter nicht benachteiligt/diskriminiert
- Bieterkartelle verbieten 
- Transparenz 
  - öffentliche Ausschreibung
  - Dokumentation
  - Verfahren 
  - Informationspflichten


## Persönlicher Geltungsbereich
- Was betrifft es?
- Gelockert für Sektorenauftraggeber

### Auftraggeber
- öffentliche 
  - klassische
    - Bund, Länder, Gemeinden
  - Einrichtungen öffentlichen Rechts 
    - keine Gewinnabsicht
    - besonderer Zweck
    - öffentlich finanziert
- sektoren 
  - Betreiben Netze (ÖBB, ...)
  - Verkehrsendeinrichtungen
  - Energieversorger
  - Öl & Gas-Förderer
  - stehen im Vergleich zu öffentlichen Auftraggebern mehr im Wettbewerb


## Sachlicher Geltungsbereich
- Was betrifft es?
- Was unterliegt dem BVergG


## BVergG 2018
- Umsetzung der EU-Vergaberechtsrichtlinie 2014 (sekundärrechtlich)
- Unterliegen primär den EU-Grundsätzen & Grundfreiheiten
  - keine Diskriminierung von anderen EU-Ländern 

### Grundfreiheiten
- Dienstleistungsverkehrsfreiheit
- Warenverkehrsfreiheit
- Personenverkehrsfreiheit
- Kapitalverkehrsfreiheit

### Auftragsarten
- Bauaufträge
- Dienstleistungsaufträge
- Lieferaufträge

#### Konzessionen
Bei normalen Aufträgen wird ein Produkt/Leistung gegen Geld erworben.
Konzessionen sind Aufträge bei denen der Anbieter/Konzessionär ein Nutzungsrecht behält.
Konzessionär enthält Entgeld von Bürgern (direkt oder über Auftraggeber)

Vorteile:

- kein Budget für Auftraggeber
- weniger Risiko bei Auftraggeber


### Ausnahmen
- Arbeitsverträge
- Verteidigung & Sicherheit
- Kredite & Darlehen
- Inhouse-Beschaffungen

### Schwellenwerte

Klassisch
- Bauaufträge = 5.350.000
- Dienstleistungs- & Lieferaufträge = 214.000
  - spezielle = 139.000

Sektoren
  - Bauaufträge = 5.350.000
  - Dienstleistungs- & Lieferaufträge = 428.000
    - spezielle = 1.000.000


### Vorschriften 
- EU-weite Ausschreibung bei OSB
- Nachweis schätznung des Auftragswerts im OSB
  - bei Lieferungen für ersten 48 Monate 
- keine Aufteilung in kleinere Aufträge
  - möglich ist eine Aufteilung in Lose => Losregelungen

## Grundsätze der Vergabe
- Grundfreiheiten einhalten
- Gleichbehandlungsgebot
  - Leistungsbeschreibung neutral 
  - keine spezifischen Produkte
- Transparenzgebot
  - öffentlich Ausschreiben
  - allen Chance geben
  - Protokollieren (Öffnung/Zuschlag/...)
- Freie, Faire, Lautere Wettbewerb
  - Frei = alle haben Chance
  - Fair = nichts unnötiges/spezifisches Ausschreiben => besondere Bieter nicht diskriminieren
  - Laut = Auftragnehmer dürfen sich nicht absprechen & Preise erhöhen => 
- Vorarbeitenproblematik
  - wenn Auftraggeber und Bieter selbe Person sind
  - Insiderinformationen könnten Vorteil bieten 
- Interessenskonflikt
  - wenn Entscheidungsträger von Erfolg eines Bieters profitiert
  - nicht mehr unparteiisch
- Vergabe an geeignete Unternehmen
  - muss Befugnis haben
  - Leistungsfähig
  - muss Zuverlässig sein
    - keine Insolvenz/Gerichtsverfahren
    - ...
- Vergabe zu angemessenen Preisen
  - Guter Schätzer
  - wenn Angebotspreise zu hoch => neu erfassen
- Tatsächliche Absicht
  - wenn man Ausschreibung macht muss diese zwangsläufig durchgeführt werden
- Vertraulichkeit
- Sekundärzwecke
  - in gewissem Ausmaß andere Aspekte berücksichtigen 
    - PESTLE


## Ausschreibungsunterlage

### Technische Spez
- Leistungsbeschreibung
  - eindeutig
  - vollständig
  - neutral
  - funktional oder konstruktiv
    - Features, Ergebnis = funktional 
    - detailierte Leistungsbeschreibung und Ergbringung beschreiben = konstruktiv

### Vertragliche Spez
- Kosten
- Bezahlung
  - Wann
  - Intervalle?
- Abnahme
- Fertigstellungen 
- Sicherstellungen


### KO-Kriterien
- Eignungskriterien
- Befugnis
- Leistungsfähigkeit
- Zuverlässigkeit

### Zuschlagskriterien
- Gereit & Gewichtet
- Früh bekannt geben
- nach Bekanntgabe nicht verändern
- keine Überschneidung
- Eindeutig/Klar

### Alternativangebote
- grundsätzlich Verboten
- Vorschlag über Alternative erwünscht?
- weicht signifikant von ursprünglicher Abschreibung ab
- nur neben konformer Ausschreibung gültig

### Abänderungsangebote
- grundsätzlich zugelassen
- anstelle ursprünglicher Ausschreibung
- geringfüge technische Änderung

### Variantenangebote 
- können eingefordert werden
- verschiedene Varianten anbieten lassen 

### Subunternehmer
- muss in Offert bekannt gemacht werden
- Verfügung und Wirtschaftlichkeit muss klar gemacht werden

### Fristen
- Teilnahmefrist = Frist bis Interessenbekentniss
- Angebotsfrist = Frist um Offerte einlegen zu dürfen
- Zuschlafsfrist = Frist um Zuschlag zu entscheidung
  - Stillhaltefrist = Nach Zuschlagsentscheidung
- Zuschlagserteilung

### Zuschlagsprinzip
- Bestbieterprinzip
- Billigstbieterprinzip
  - meist wenn Gestaltungsspielraum gering ist

### Preisverfahren
- Preisangebots
- Preisaufschlag/-nachlassverfahren

### Preisarten
- Einheitspreis
  - genau Was 
  - genau Wieviel
- Pauschalpreis
  - genau Was 
  - unklar Wieviel
- Regiepreis
  - unklar Was 
  - unklar Wieviel

### Preisarten
- Festpreise
- Veränderliche Preise
  - an Index gekoppelt

### Sicherstellungen
- Vadium = Betrag vom Offertsteller einfordern 
  - bei Rücktritt während Zuschlagsfrist fällt Vadium an Auftraggeber
- Kaution = wenn Vertrag gebrochen wird fällt Kaution an Vertragspartner
- Deckungsrücklass = von Endrechnung Betrag einbehalten
- Haftungsrücklass = von Endrechnung Betrag einbehalten

## Angebot
- Formvorschriften
  - Bieterlücken
  - Sprache
- innerhalb Angebotsfrist abänderbar
- keine Verfütung

## Widerruf
- fakultativ
  - Preise liegen über geschätztem Auftragwert
  - Überschreitung der Zuschlagsfrist
- zwingend
  - keine Angebote
  - Fehler in Ausschreibung



## Vergabeverfahren

### Offene 
- Einstufig = Kein Teilnahmewettbewerb
- Angebotsfrist
- Zuschlagsfrist
- Öffnung
  - Öffnung der Angebote ist öffentlich
- Stillhaltefrist
- Zuschlag

### Nicht-Offene

- Mit Bekanntmachung
  - Teilnahmefrist = Eignungskriterien veröffentlichen
    - OSB min 5 Bewerber, USB min 3 Bewerber
  - Angebotsfrist mit Bewerbern 
  - Öffnung
  - Zuschlagsfrist
  - Stillhaltefrist
  - Zuschlag
- Ohne Bekanntmachung (nur im USB)
  - Wertgrenzen 
    - Bau: 1.000.000€
    - Liefer- & Dienstleistungen: 100.000€
  - Angebotsfrist mit Bewerbern 
    - min. 3 Bewerber einladen
  - Öffnung
  - Zuschlagsfrist
  - Stillhaltefrist
  - Zuschlag

### Verhandlungsverfahren
- über Auftragsinhalt kann Verhandelt werden
- Verhandlungen getrennt
- keine öffentliche Öffnung der Offerte 
- Nach Verhandlung wird Ausschreibung finalisiert & Bieter müssen Letztofferte eintragen
- bis 100.000 €

- Mit Bekanntmachung
  - min. 5 bzw. 3 Bieter
- Ohne Bekanntmachung
  - min. 3 Bieter

### Direktvergabe
- bis 100.000 €
- Formfrei
- kleine Aufträge rasch & unkompliziert

- Mit Bekanntmachung
  - Bau: 500.000 €
  - Liefer- & Dienstleistungen: 130.000 €
- Ohne Bekanntmachung
  
### Weiter Verfahren  

#### Rahmenvereinbarung
- Offenes Verfahren
- Wiederholte Leistung erbringen (innerhlab 4 Jahre)
- Separate Ausschreibungen vermeiden

####  Dynamisches Beschaffungssystem
- wie Rahmenvereinbarung
- rein elektronisch
- während Laufzeit auch neue zusätzliche Bieter möglich

#### Innovationspartnerschaft
#### Wettbewerblicher Dialog


## Lostrennung/Losregelung
- Aufträge in Lose aufteilen
- Regelungen um Auftragssplitting vermeiden

  



# 4. Cloud-Computing

Definition = Ressourcen werden über ein Netzwerk bereitgestellt, stehen unbegrenzt zur Verfügung, können schnell und von überall zugegriffen werden

## Aufbau
- Essential Characteristics
  - Broad-Network-Access
    - Glasfaser & Breitband Verbindung
    - Bandbreitenverbrauch steigt exponentiell
    - zunehmend mobile Geräte (Smartphones/Laptops/...)
  - Ressource-Pooling
    - Virtualisierung
    - physische Server werden zu einem großen virtuellen Pool an Kapazitäten zusammengefasst
    - Server-/Hardware-/Anwendungsvirtualisierung
    - Multi-tennant models
  - Rapid Elasticity
    - durch virtualisierung können Ressourcen schnell und einfach erweitert werden
    - Ressourcen basierend auf Auslastung
  - Measured Service 
    - es wird genau das bezahlt was auch genutzt wird
  - On-Demand Self-Service
    - Kunden erweitern/managen Services selbst
- Service Models
  - **SaaS** = Software as a Service
    - Ganze Applikation liegt bei Provider
    - Kunde nutzt nur Applikation
  - **PaaS** = Platform as a Service
    - Betriebssystem, Middleware, Runtimes, Datenbanksysteme liegen bei Provider
    - Kunde beginnt ab Daten
  - **IaaS** = Infrastructure as a Service
    - Infrastruktur, Rechner, Speicher liegt bei Provider
    - Kunde beginnt ab Virtualisierung
- Deployment Models
  - Public
    - öffentlich 
    - jeder kann sie Nutzen
    - flexibel/skalierbar
    - große Kapazitäten
    - off-premise = außerhalb von Unternehmen

  - Hybrid Cloud 
    - Daten on-premise
    - Apps off-premise

  - Community Cloud
    - private clouds zusammenschließen
    - nur Partner zugänglich

  - Private
    - on-premise = nur innerhalb Unternehmen
    - nur Mitarbeiter/Partner zugänglich
    - eigene Service levels
    - eigene Security/Privatsphäre
    - keine Abhängigkeit


## SWOT Cloud Computing

### Strengths
- Skalierbarkeit
  - keine Kapazitätslücken
- Performance
- ...

### Weaknesses
- Abhängigkeit
- Netzzugang notwendig

### Opportunities
- **Economies of Scale** = Provider hat große Kapazitäten und somit geringere Stückkosten
- TCO ist kleiner
- Sicherheit
- Risikotransfer
- Geringere Kosten 

### Threats
- Kompetenzverlust
- Datenschutz


## Total Cost of Ownership
- wieviel der Betrieb von Cloud kostet
- Beinhaltet Investitionskosten + Betriebskosten aber auch Schulungen, Lizenzen, Wartung, etc.
- Viele Kosten bei Selbsterstellung sind nicht direkt ersichtlich