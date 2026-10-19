# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Interessierte Privatanleger (Bekannte, Kolleginnen und Kollegen, andere Sparer), die eine
ETF-Sparplan-Strategie verstehen und sie anschließend mit ihrer eigenen Sparsumme nachbauen wollen.
Sie kommen meist über einen geteilten Link, lesen auf dem Smartphone wie am Desktop und vergleichen
das Gelesene mit dem Sparplan-Angebot ihres eigenen Brokers.

## Product Purpose

Die Seite dokumentiert das Rickmersche Portfolio: einen global diversifizierten ETF-Sparplan aus
sechzehn Positionen mit bewusst gesteuerter Länder- und Regionenallokation, deutschen Anbietern und
physischem Gold, festgeschrieben als dauerhaftes Regelwerk. Erfolg heißt: Wer die Seite verlässt, hat
**die Idee verstanden** (Regionen gezielt steuern statt einen einzelnen Welt-Index der
Marktkapitalisierung zu überlassen; deutscher Anker bei den Emittenten; Gold ohne Länderbezug; kein
Rebalancing, unveränderte Raten). Der Rechner ist das Werkzeug, um das Verstandene auf die eigene
Sparsumme zu übertragen; er folgt dem Verstehen und ersetzt es nicht.

## Positioning

Anders als ein einzelner Welt-ETF wird die Länderallokation nicht der Marktkapitalisierung überlassen:
USA bewusst auf 30 % dosiert, World ex USA mit 36 % dagegengestellt, Schwellenländer in Regionalblöcke
und Einzelländer zerlegt. Vierzehn der sechzehn Bausteine stammen von Xtrackers (DWS, Frankfurt), das
Gold (EUWAX Gold II) wird in Deutschland verwahrt. Keine Umschichtung, keine Ratenanpassung: nur die
Märkte verschieben die Gewichte.

## Operating Context

- Eine öffentliche, deutschsprachige Einzelseite (`index.html`) plus `impressum.html`, ausgeliefert über
  GitHub Pages unter `rickmersches-portfolio.janrickmer.de`.
- Ansprache der Besucher in der Sie-Form.
- Typischer Ablauf: Leitgedanke lesen → sehen, wohin das Geld weltweit fließt (Karte, Länderliste,
  Allokation) → die sechzehn Bausteine und ihre Begründung prüfen → Gold und Rebalancing-Regel
  verstehen → im Rechner die eigene Sparsumme (oder eigene Gewichtung) in Raten je Position umrechnen
  und beim eigenen Broker anlegen.
- Alte Sprungmarken `#tool1` (eigene Gewichtung) und `#tool2` (Original) sind im Umlauf und müssen
  weiter funktionieren.

## Capabilities and Constraints

- Interaktive Weltkarte (Länderanteile an der Sparrate, Tooltip mit Herkunft je Baustein), sortierte
  Länderliste, Allokation nach Weltregionen und Marktreife, gruppierte Positionstabelle, Rechner mit
  zwei Modi (Rickmersche / eigene Gewichtung; centgenau und ganze Euro per Largest-Remainder-Verfahren).
- Alle Zahlen werden im Skript aus einem Datenmodell abgeleitet (Sparraten je ETF, genäherte
  Index-Ländergewichte, Stand Juni 2026). Fakten, Zahlen, ISINs, Produktangaben und Hinweise sind fix;
  Überschriften und Bezeichnungen dürfen für die Gestaltung umformuliert werden.
- Datenschutzversprechen laut Impressum: keine Cookies, keine Analyse, keine Werbung, keine
  Verbindungen zu anderen Anbietern; Schriften und alle Medien werden selbst ausgeliefert, Eingaben
  verlassen den Browser nicht und werden nicht gespeichert.
- Statische Auslieferung ohne Build-Schritt und ohne Server-Logik.
- Hell- und Dunkelmodus, Druckansicht, reduzierte Bewegung und Forced-Colors werden heute unterstützt.

## Brand Commitments

- Name: „Das Rickmersche Portfolio“. Der Name ist reiner Titel und wird gestalterisch **nicht**
  thematisiert (keine Motive aus Herkunft oder Bedeutung des Namens).
- Bewusste Entscheidung für den Branchenstandard (Oktober 2026): eine klare, vertraute,
  vertrauenswürdige Finanz-Dokumentation, ohne Ironie und ohne eingeschmuggelte Eigenheiten, auf dem
  Handwerksniveau von **Finanztip** (gut lesbare Erklärtexte, klare Struktur, Vertrauen) und
  **Trade Republic** (große Typografie, wenige Elemente, starke Bilder).
- Bildwelt: sachliche, frei lizenzierte Fotos aus der Welt des Portfolios und höchstens ein stummer
  Video-Loop, selbst gehostet und mit Bildnachweis; nie als eigene Aufnahmen ausgegeben.
- Haltung: private, nicht kommerzielle Dokumentation; ausdrücklich keine Anlage-, Rechts- oder
  Steuerberatung.

## Evidence on Hand

- Datenmodell der sechzehn Positionen mit Sparraten, ISINs, Emittenten und genäherten
  Index-Ländergewichten (im Skript von `index.html`).
- Weltkarten-SVG mit Ländergrenzen (in `index.html`).
- Keine eigenen Fotos, keine Wertentwicklungsdaten, keine Testimonials, keine Presse. Renditen,
  Kursverläufe, Nutzerzahlen oder Empfehlungen Dritter dürfen nicht erfunden werden.

## Product Principles

1. Verstehen vor Rechnen: jede Darstellung erklärt zuerst die Idee, das Werkzeug folgt.
2. Jede Zahl stammt aus dem Datenmodell; Näherungen und Stichtag werden offen ausgewiesen.
3. Ehrlichkeit vor Überzeugung: keine Renditeversprechen, Risiken und Hinweise gut sichtbar.
4. Nichts verlässt den Browser: keine fremden Dienste, keine Speicherung von Eingaben.
5. Für alle lesbar und bedienbar, auf dem Smartphone genauso wie am Schreibtisch.

## Accessibility & Inclusion

Bestehender Standard bleibt erhalten: Sprunglink, vollständige Tastaturbedienung, sichtbarer Fokus,
Screenreader-Beschriftungen für Karte und Tabellen, Kontraste mindestens WCAG AA, Unterstützung von
`prefers-reduced-motion` und Forced-Colors.
