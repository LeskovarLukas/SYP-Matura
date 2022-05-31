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