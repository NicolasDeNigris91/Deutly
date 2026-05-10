---
module: 06-C3-3
title: Technisches Deutsch III — Technische Dokumentation
stage: spezialisierung-track-c3-technik
prereqs: [06-C3-2]
gates:
  konzeptuell:  { status: pending, date: null, attempts: 0, notes: null }
  praktisch:    { status: pending, date: null, attempts: 0, notes: null }
  verbindungen: { status: pending, date: null, attempts: 0, notes: null }
status: locked
---

# 06-C3-3 — Technische Dokumentation

## 1. Sprachliches Problem

Technische Dokumentation umfasst:
- **Bedienungsanleitungen** (Anwender-orientiert; Verbraucher).
- **Wartungs-Handbücher** (Service-Personal).
- **Service-Manuale** (Hersteller-intern).
- **Softwareversionen-Dokumentation** + API-Dokumentation.
- **Produktdatenblätter** (technische Spezifikationen).
- **Sicherheitsdatenblätter** (chemische / physikalische Risiken).

Stilistisch: hyper-präzise + benutzerorientiert + visualisiert. Standardisiert nach DIN EN 82079 (Bedienungsanleitungen).

---

## 2. Harte Theorie

### 2.1 DIN EN 82079 — Bedienungsanleitungen

Standard für Bedienungsanleitungen Hauptanforderungen:
- **Vollständigkeit** — alle nötigen Informationen für sichere Verwendung.
- **Verständlichkeit** — Adressat-Niveau angemessen (Verbraucher vs. Profi).
- **Korrektheit** — kein Widerspruch zu Produkt-Realität.
- **Strukturierung** — Inhaltsverzeichnis + Sektionen + Stichwortverzeichnis.
- **Mehrsprachigkeit** — bei Verkauf in mehreren Ländern.

### 2.2 Standard-Sektionen Bedienungsanleitung

1. **Sicherheitshinweise** (oft zu Beginn, kategorisiert: Gefahr / Warnung / Vorsicht / Hinweis).
2. **Bestimmungsgemäße Verwendung**.
3. **Produktbeschreibung** + Lieferumfang.
4. **Inbetriebnahme**.
5. **Bedienung**.
6. **Wartung + Reinigung**.
7. **Fehlerbehebung**.
8. **Technische Daten**.
9. **Entsorgung**.
10. **Garantie + Kundendienst**.

### 2.3 Sprachlich: Anweisungs-Stil

- **Imperative + Inf.-Konstruktionen**: *"Lesen Sie diese Anleitung vor Inbetriebnahme."*; *"Vor Reinigung Stecker ziehen."*
- **Konditional-Konstruktionen**: *"Falls / wenn / sollte ... auftreten, dann ..."*
- **Sicherheitshinweis-Formeln**: 
  - **Gefahr**: *"Lebensgefahr durch Stromschlag. Vor Wartung Hauptschalter abschalten."*
  - **Warnung**: *"Verbrennungsgefahr. Heiße Oberflächen nicht berühren."*
  - **Vorsicht**: *"Sturz-Gefahr. Standfestigkeit vor Verwendung prüfen."*

### 2.4 Software- + API-Dokumentation

Distinkte Konvention für IT/Software:
- **API-Dokumentation** (Funktions-Signatur + Parameter + Rückgabe + Beispiel + Fehler-Codes).
- **Tutorials + Quick-Start-Guides**.
- **Reference-Dokumentation** (vollständig + alphabetisch).
- **Changelogs / Release Notes** (chronologisch).

DE-Software-Doku oft Mischung aus DE + EN-Lehnwörtern (*Backend*, *Frontend*, *Endpoint*, *Token*).

### 2.5 Sicherheitsdatenblätter (SDB)

EU-Verordnung (REACH; CLP) reglementiert Sicherheitsdatenblätter chemischer Produkte. 16 obligatorische Sektionen:
1. Bezeichnung des Stoffs.
2. Mögliche Gefahren.
3. Zusammensetzung.
4. Erste-Hilfe-Maßnahmen.
5. Brandbekämpfung.
6. Maßnahmen bei unbeabsichtigter Freisetzung.
7. Handhabung + Lagerung.
8. Begrenzung + Überwachung der Exposition / Persönliche Schutzausrüstung.
9. Physikalische + chemische Eigenschaften.
10. Stabilität + Reaktivität.
11. Toxikologische Angaben.
12. Umweltbezogene Angaben.
13. Hinweise zur Entsorgung.
14. Angaben zum Transport.
15. Rechtsvorschriften.
16. Sonstige Angaben.

---

## 3. Texto-âncora

**3-5 Bedienungsanleitungen + 2-3 API-Dokus + 1 Sicherheitsdatenblatt** systematisch lesen + analysieren.

Beispiel-Quellen:
- Bedienungsanleitungen: jedes Konsumgut hat eine; oft online auf Hersteller-Webseite.
- API-Dokus: GitHub-Projekte (z.B. Django-DE-Doku; Vue.js-DE; SAP-Doku).
- SDB: jedes industrielle Chemieprodukt hat eines.

---

## 4. Sprachliche Aufgabe

(a) **Bedienungsanleitung verfassen** (~3000W) für hypothetisches Produkt — alle 10 Standard-Sektionen.

(b) **API-Dokumentation** (~2000W) für hypothetische Software-Funktion (z.B. eine Authentifizierungs-API).

(c) **Sicherheitsdatenblatt-Skizze** (~2000W) für hypothetisches chemisches Produkt — alle 16 Sektionen.

---

## 5. Verbindungen

- **Prereq**: 06-C3-2 Patentschriften.
- **Ergänzt durch**: CAPSTONE-6-C3.
- **Cross-Reference**: 06-C3-1 DIN-Normen-Sprache; 02-07 Modalverben (Sicherheit-Stufen via Modal-Verben).

---

## 6. Konzeptuelles Tor (Beispielfragen)

1. DIN EN 82079 Hauptanforderungen für Bedienungsanleitungen.
2. Standard-Sektionen Bedienungsanleitung.
3. Differenzieren Sie Sicherheitshinweis-Stufen (Gefahr / Warnung / Vorsicht / Hinweis).
4. Was sind die 16 SDB-Sektionen? (Auswahl 5-10.)
5. Welche distinkten Konventionen hat Software-/API-Dokumentation?

---

## 7. Praktisches Tor

Vorlage Bedienungsanleitung + API-Doku + SDB-Skizze. Loop der Verfeinerung. 5 Begründungsfragen.

---

## 8. Literaturverzeichnis

- DIN EN 82079 — Bedienungsanleitungen.
- REACH-Verordnung (EU 1907/2006).
- CLP-Verordnung (EU 1272/2008).
- tekom — Gesellschaft für technische Kommunikation (tekom.de).

---

## Cross-references

- [06-C3-1 DIN-Normen-Sprache](06-C3-1-din-normen-sprache.md) + [06-C3-2 Patentschriften](06-C3-2-patentschriften.md).
- [02-07 Modalverben](../02-struktur/02-07-modalverben.md).
- Nächste: [CAPSTONE-6-C3](CAPSTONE-6-C3.md).
