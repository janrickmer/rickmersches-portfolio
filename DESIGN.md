---
name: Das Rickmersche Portfolio
description: Klare deutsche Finanzdokumentation im Branchenstandard – weiß, ein Finanzblau, Inter, echte Archivbilder.
colors:
  paper: "#FFFFFF"
  cool-surface: "#F2F5F9"
  cool-surface-deep: "#E6ECF4"
  ink: "#0E1726"
  slate-muted: "#4A5568"
  finance-blue: "#1458D6"
  finance-blue-deep: "#0E46AE"
  field-stroke: "#7A8699"
  track-grey: "#DCE3EC"
  map-absent: "#E2E6EC"
  map-q1: "#AFC9F3"
  map-q2: "#76A1EC"
  map-q3: "#3A6FDB"
  map-q4: "#0D3D9C"
  series-north-america: "#1458D6"
  series-europe: "#5AA3F2"
  series-asia-pacific: "#008C80"
  series-latin-america: "#4CC3D9"
  series-middle-east: "#2B50B5"
  series-africa: "#77A6EE"
  series-gold: "#B38A22"
  blue-page-soft: "#DCE7FB"
  blue-page-bar: "#A9C6F5"
  navy-page-ink: "#F3F6FA"
  navy-page-soft: "#B4C0D2"
  gold-page: "#E6CF98"
  gold-page-soft: "#3B3420"
  state-ok: "#2F7A3A"
  state-warn: "#B4471B"
  night-paper: "#0B111C"
  night-surface: "#141D2C"
  night-ink: "#E9EEF6"
  night-blue: "#6C9FF6"
  night-bronze: "#372C15"
  night-bronze-ink: "#F3EBD3"
typography:
  display:
    fontFamily: "Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif"
    fontSize: "clamp(2.6rem, 1.15rem + 4.6vw, 5.5rem)"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(1.875rem, 1.35rem + 1.45vw, 2.75rem)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-0.028em"
  title:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 1.12rem + .42vw, 1.5rem)"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.015em"
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
    fontFeature: "\"cv11\" 1"
  label:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 500
    lineHeight: 1.5
rounded:
  bar: "8px"
  row: "10px"
  field: "12px"
  panel: "20px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 2.2vw, 32px)"
  margin: "clamp(20px, 4.45vw, 64px)"
  section: "clamp(80px, 8.5vw, 128px)"
  container: "1680px"
components:
  button-primary:
    backgroundColor: "{colors.finance-blue}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "48px"
  button-primary-hover:
    backgroundColor: "{colors.finance-blue-deep}"
    textColor: "{colors.paper}"
  button-quiet:
    backgroundColor: "{colors.cool-surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "48px"
  button-on-blue:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.finance-blue}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "48px"
  chip:
    backgroundColor: "{colors.cool-surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
  input-amount:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "0 34px 0 14px"
    height: "44px"
  panel:
    backgroundColor: "{colors.cool-surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "clamp(22px, 2.4vw, 36px)"
  nav-link-current:
    backgroundColor: "{colors.cool-surface}"
    textColor: "{colors.finance-blue}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
---

# Design System: Das Rickmersche Portfolio

## Overview

**Creative North Star: "Das offene Datenblatt"**

Die Seite ist ein Datenblatt, das man gern liest: der Branchenstandard deutscher Finanzerklärseiten, ohne Ironie und ohne Privatbank-Pathos gespielt. Vorbilder sind die Klarheit von Finanztip und die Zurückhaltung von Trade Republic, also große Schrift, wenige Elemente und starke Bilder. Jede Zahl ist eine echte Zahl aus dem Sparplan. Was gezeigt wird, lässt sich nachrechnen.

Gebaut ist die Seite auf weißem Grund mit einer einzigen kühlen Flächenstufe, Tinte statt Schwarz und einem Finanzblau, das Handlung und Leitreihe zugleich ist. Den Rhythmus geben Textseiten mit fester Achse und vollflächige Farbseiten in Blau, Nachtblau und Gold. Abgegrenzt wird über Flächen, nie über Linien. Die Bildwelt besteht aus sachlichen, gemeinfreien Archivaufnahmen (NASA, The Met) und einem stummen Video, alles selbst ausgeliefert und nachgewiesen.

Abgelehnt sind zwei Gegenbilder: die cremefarbene Privatbank-Broschüre mit Goldschrift, die diese Seite ersetzt, und das Dashboard aus Kennzahlkacheln und Icon-Karten.

**Key Characteristics:**
- Weißer Grund, eine Flächenstufe, ein Blau; Gold nur, wo Gold gemeint ist
- Inter als einzige Familie, Zahlen immer tabellarisch
- Textseiten auf fester Achse, dazwischen vollflächige Farbseiten
- Flache Felder statt Linien, runde Schaltflächen, eckige Fotos
- Ein einziger Bewegungsmoment im Einstieg, danach steht die Seite still
- Hell und dunkel, Druck, reduzierte Bewegung und Kontrastmodus sind gleichwertig gestaltet

## Colors

Eine kühle, nüchterne Palette: Papierweiß, ein Hauch Blaugrau als Fläche, tiefe Tinte und ein einziges kräftiges Finanzblau. Dazu kommt eine abgestufte Familie aus Blau- und Petroltönen für Regionen und Kartenstufen.

### Primary
- **Finanzblau** (finance-blue): Primäre Schaltflächen, Textlinks, Fokusring, der aktive Navigationspunkt, die Leitreihe Nordamerika und alle Anteilsbalken. Als Fläche trägt es die blauen Farbseiten (Allokation, Rechner). Beim Hover wird es zu **Tiefblau** (finance-blue-deep).

### Secondary
- **Regionsreihe** (series-europe, series-asia-pacific, series-latin-america, series-middle-east, series-africa): Ruhige Blau- und Petroltöne, die die Regionen im gestapelten Balken und in der Legende unterscheiden. Sie werden immer zusammen mit Wert und Beschriftung gezeigt, nie allein über die Farbe.
- **Kartenstufen** (map-q1 bis map-q4): Eine vierstufige, sequenzielle Blauskala für den Anteil je Land. Nicht enthaltene Länder stehen in **Kartengrau** (map-absent).

### Tertiary
- **Goldreihe** (series-gold) und **Goldseite** (gold-page): Ausschließlich für die Goldposition, also den Goldbalken, das Legendenfeld und die Goldfarbseite. Die Goldseite ist ein gedämpftes, blasses Gold. Die Fließtextfarbe darauf ist **Goldbraun** (gold-page-soft). Im Dunkelmodus wird die Seite zu **Bronze** (night-bronze) mit heller Schrift (night-bronze-ink), damit sie nie die hellste Fläche ist. Das Goldfoto ist auf die Seitenfarbe freigestellt, es gibt keinen fremden Hintergrund.

### Neutral
- **Papier** (paper): Seitengrund und Schrift auf blauen Flächen.
- **Kühle Fläche** (cool-surface): Panels, Tabellenzeilen im Wechsel, Chips und Hover-Flächen. Für Hover und gedrückte Zustände gibt es eine zweite Stufe **Tiefe Fläche** (cool-surface-deep).
- **Tinte** (ink): Text, ausgewählte Chips, Nachtblau-Farbseite und Fußzeile.
- **Schiefer** (slate-muted): Sekundärtext wie Beschriftungen, ISINs und Bildunterschriften. Auf Weiß erreicht er AA.
- **Feldrand** (field-stroke): Der einzige sichtbare Rand der Seite, an Eingabefeldern.
- **Spurgrau** (track-grey): Die Hintergrundspur der Anteilsbalken.
- **Nachtfarben** (night-paper, night-surface, night-ink, night-blue): Der Dunkelmodus. Gleiche Rollen, hellere Akzente.

### Named Rules
**Die Ein-Blau-Regel.** Finanzblau ist die einzige Handlungsfarbe und die Leitreihe der Diagramme. Es schmückt nie, und kein zweiter Akzent tritt neben es.

**Die Gold-heißt-Gold-Regel.** Goldtöne erscheinen nur dort, wo physisches Gold gemeint ist. Nie als Auszeichnung, Rahmen oder „Premium“-Signal.

**Die Wert-neben-Farbe-Regel.** Eine Farbe in einem Diagramm steht nie allein. Wert und Name stehen daneben, damit Kontrastmodus, Druck und Farbsehschwäche nichts verlieren.

## Typography

**Display Font:** Inter (mit system-ui)
**Body Font:** Inter (mit system-ui)

**Character:** Eine einzige Familie, eingebettet und mit optischer Größe. Große Überschriften sind halbfett und eng gesetzt, der Fließtext ist ruhig und großzügig. Hierarchie entsteht über Größe und Gewicht, nie über eine zweite Schrift.

### Hierarchy
- **Display** (600, clamp 2,6–5,5 rem, 1,0): Nur der Seitentitel im Einstieg, zweizeilig.
- **Headline** (600, clamp 1,875–2,75 rem, 1,08): Abschnittsüberschriften, höchstens zwei Zeilen, auf breiten Bildschirmen haftend in der linken Spalte.
- **Title** (600, clamp 1,25–1,5 rem, 1,25): Unterüberschriften, Gruppenzeilen der Tabelle, Regionsnamen an der Karte. Als Lead-Text (500, 1,38) für Leitsätze.
- **Body** (400, 1,125 rem, 1,6): Fließtext mit einem Satzspiegel von 52ch (rund 65–70 Zeichen je Zeile), Silbentrennung an, `text-wrap: pretty`.
- **Label** (500/600, 0,9375 rem, 1,5): Beschriftungen, Legenden, Tabellenköpfe, Bildunterschriften, Fußzeile.

### Named Rules
**Die Eine-Familie-Regel.** Inter in 400, 500 und 600, sonst nichts. Keine Monospace, keine Kapitälchen, keine gesperrten Großbuchstaben.

**Die Tabellenziffern-Regel.** Jede Zahl, ob Prozent, Euro oder ISIN, steht in tabellarischen Ziffern, damit Spalten und Live-Werte nicht springen.

## Layout

Zwölfspaltiges Raster in einem Container von höchstens 1680 px, mit fließendem Seitenrand und Spaltenabstand (siehe spacing). Textseiten setzen die Überschrift in die Spalten 1–5 und den Text auf die feste Achse ab Spalte 6 (rund 42 %). Diese Achse hält über alle Textseiten. Farbseiten laufen vollflächig. Abschnitte atmen mit großzügigem vertikalem Abstand (section).

Der Einstieg teilt sich etwa 55/45: links Titel, Leitsatz, Handlung und fünf Kennzahlen, rechts ein Flächenpanel mit dem live gerechneten Regionsbalken. Unter 1000 px stapelt sich alles einspaltig: Das Live-Panel rückt direkt hinter die Handlung und vor die Kennzahlen, die auf dem Handy 3 + 2 stehen. Unter 820 px wird die Navigation zu einem überlagernden Menüblatt. Unter 980 px bzw. 480 px werden die Tabellen zu Zeilenkarten. Bis 900 px werden die Säulen der Weltregionen zu einer Liste aus Beschriftung und darunterliegendem Balken. Text steht nie im Balken. Auf dem Handy steht die Länderliste zweispaltig aus Name und Wert, unter 390 px einspaltig. Die Punkt-Balken entfallen dort, weil sie bei Anteilen unter 1 % keine Information tragen. Sprungziele landen genau unter der 76 px hohen Kopfleiste.

**Die Feste-Achse-Regel.** Fließtext beginnt auf Textseiten immer an derselben Achse. Ausnahmen sind vollbreite Diagramme, Tabellen und Fotos sowie Text, der direkt unter einem Foto in dessen Spalte weiterläuft. Ein Beispiel ist der deutsche Anker: Foto und Begründung stehen links, die Deutschlandkarte rechts daneben.

**Die Ein-Moment-Regel.** Bewegung gibt es auf der Seite genau einmal: Titel, Leitsatz, Panel und Balken des Einstiegs bauen sich beim Laden auf. Danach wachsen nur die Regionsbalken der Allokation einmal an Ort und Stelle. Sprünge zu Kapiteln und der Tastaturfokus scrollen sofort, ohne Gleiten. Bedienelemente reagieren mit kurzen Zustandswechseln (unter 300 ms), sonst steht alles still.

## Elevation & Depth

Das System ist flach. Tiefe entsteht aus Flächenstufen (Papier → kühle Fläche → tiefe Fläche) und aus dem Wechsel zu vollflächigen Farbseiten, nicht aus Schatten. Schatten gibt es nur für Elemente, die tatsächlich über dem Inhalt schweben, und auch dann erst im Zustand.

### Shadow Vocabulary
- **Haftende Kopfleiste** (`box-shadow: 0 10px 28px -18px rgba(14,23,38,.45)`): Erst sichtbar, sobald gescrollt wird. Wird über die Deckkraft eingeblendet.
- **Menüblatt** (`box-shadow: 0 18px 40px -20px rgba(14,23,38,.5)`): Nur das geöffnete Mobilmenü.
- **Tooltip** (`box-shadow: 0 14px 34px -16px rgba(0,0,0,.55)`): Die schwebende Länderinfo an der Karte.
- **Haftende Summenzeile** (`box-shadow: 0 -12px 18px -14px rgba(14,23,38,.35)`): Nur im Rechner, Modus „Eigene Gewichtung“.

### Named Rules
**Die Flach-in-Ruhe-Regel.** In Ruhe hat nichts einen Schatten. Ein Schatten zeigt an, dass etwas über dem Inhalt schwebt.

## Shapes

Zwei Formen tragen das System: **runde Pillen** für alles Bedienbare (Schaltflächen, Chips, Navigationspunkte, Modusschalter, 999 px) und **sanft gerundete Flächen** für Behälter (Panels 20 px, Felder 12 px, Tabellenzeilen 10 px, Balkenenden 4–8 px). Fotos und das Video bleiben eckig und laufen bis an die Kante ihrer Spalte oder der Seite. Linien als Gliederung gibt es nicht. Der einzige sichtbare Rand gehört zu Eingabefeldern. Unsichtbare 1-px-Ränder an Bedienelementen werden erst im Kontrastmodus zur Kontur.

## Components

### Buttons
Klar, rund und satt, mit einem kleinen Nachgeben beim Drücken.
- **Shape:** Pille (999 px), mindestens 48 px hoch, Beschriftung 600 in Label-Größe.
- **Primary:** Finanzblau mit weißer Schrift, Polsterung 0 24 px.
- **Hover / Focus:** Hover nur bei Maus (`hover:hover and pointer:fine`) wird Tiefblau. Fokus ist ein 2-px-Ring in Finanzblau mit 3 px Abstand; auf Farbseiten nimmt er die Seitenschrift an. Beim Drücken skaliert der Button auf 0,97 (140 ms, ease-out).
- **Quiet:** Kühle Fläche mit Tintenschrift, für Nebenhandlungen wie „Rickmersche Vorgabe“.
- **Auf Blau:** Papier mit blauer Schrift.

### Chips
- **Style:** Kühle Fläche, Tintenschrift, Pille, 44 px hoch, Beträge in tabellarischen Ziffern.
- **State:** Ausgewählt wird zur Tintenfläche mit Papierschrift (`aria-pressed`). Regionsknöpfe an der Karte verhalten sich auf schmalen Bildschirmen genauso.

### Cards / Containers
- **Corner Style:** 20 px (Panel), 10–12 px (Zeilen).
- **Background:** Kühle Fläche auf Papier. Der Rechner liegt als Papierfläche auf der blauen Seite.
- **Shadow Strategy:** Keiner (siehe Elevation & Depth).
- **Border:** Keiner.
- **Internal Padding:** clamp 22–36 px.

### Inputs / Fields
- **Style:** Papierfläche, 1 px Feldrand, 12 px Radius, 44 px hoch (im Rechner 52 px), rechtsbündige Zahl mit nachgestelltem „€“.
- **Focus:** 2-px-Ring in Finanzblau, der Rand wird blau.
- **Error / Disabled:** Bei unlesbarer Eingabe färbt sich der Rand in Warnrot, darunter steht ein kurzer Satz in Warnrot (`aria-invalid`, `aria-describedby`). Deaktivierte Schaltflächen haben 45 % Deckkraft.

### Navigation
- **Style:** Haftende Kopfleiste auf Papier: Wortmarke links, fünf Kapitel als Textpillen, rechts die blaue Handlung. Das aktuelle Kapitel bekommt eine kühle Fläche mit blauer Schrift (`aria-current`). Unter 820 px gibt es die Schaltfläche „Menü“ mit einem überlagernden Blatt, das bei Escape und bei Klick daneben schließt.

### Anteilsbalken (Signature)
Die Sprache aller Diagramme: ein gerundeter Balken auf grauer Spur oder freistehend, immer mit Wert in tabellarischen Ziffern daneben. Es gibt den gestapelten Regionsbalken im Einstieg, die Spaltenbalken der Weltregionen, den Marktreife-Balken, die Spuren in Tabelle und Länderliste und die Choroplethen-Karte mit vierstufiger Legende. Alle Längen sind maßstabsgetreu.

## Do's and Don'ts

### Do:
- **Do** Finanzblau (#1458D6) als einzige Handlungs- und Leitfarbe einsetzen und Diagrammfarben immer mit Wert und Namen zeigen.
- **Do** Fließtext auf der festen Achse ab Spalte 6 von 12 setzen und Überschriften in Spalte 1–5 haften lassen.
- **Do** Bewegung auf einen Moment beschränken: Der Einstieg baut sich auf, die Regionsbalken wachsen einmal an Ort und Stelle, alles andere steht still. UI-Übergänge bleiben unter 300 ms mit `cubic-bezier(.23,1,.32,1)`, Hover gibt es nur bei feinem Zeiger.
- **Do** echte, gemeinfreie oder frei lizenzierte Archivbilder verwenden, selbst ausliefern, mit `srcset` anbieten und in der Fußzeile nachweisen. Jede Bearbeitung wie Ausschnitt oder Freistellung gehört in den Nachweis.
- **Do** jede neue Fläche auch in Dunkelmodus, Druck, reduzierter Bewegung und Kontrastmodus prüfen.

### Don't:
- **Don't** Kennzahlen als große Zahl über einer Beschriftung außerhalb der fünf Einstiegsfakten wiederholen. Keine Stat-Kacheln, keine Zahlen-Kicker über Überschriften.
- **Don't** Eyebrows, Trennlinien, Verläufe, Glas-Effekte oder Schatten in Ruhe einsetzen.
- **Don't** eine zweite Schriftfamilie, Monospace oder gesperrte Großbuchstaben verwenden.
- **Don't** Gold als Schmuckfarbe einsetzen oder die cremefarbene Privatbank-Anmutung zurückholen.
- **Don't** Abschnitte, Überschriften, Texte oder Fotos beim Scrollen einblenden. Keine wiederkehrenden Einblendeffekte, keine Vorhänge über Bildern, keine Inhalte mit `opacity: 0` hinter einem Beobachter.
- **Don't** Motive aus Herkunft oder Bedeutung des Namens aufgreifen, und keine Bilder, die als eigene Aufnahmen erscheinen.
