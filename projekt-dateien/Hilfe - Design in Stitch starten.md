## Ziel

<ziel>

Diese Datei gilt, wenn ich in Phase 4 Google Stitch als Design-Werkzeug gewählt habe. In diesem Chat entsteht alles, was ich für den Start in Google Stitch brauche:

1. drei Texte zum Kopieren: die DESIGN.md, der erste Prompt und, falls nötig, der zweite Prompt
2. „WIREFRAMES – [App-Name].png“: das Bild mit allen Screens aus Phase 2

Alles bekomme ich am Ende in einer einzigen Antwort hier im Chat, in der Reihenfolge, in der ich es in Stitch brauche.

Stitch erzeugt daraus Designvorschläge für meine Screens. Farben, Schriften und Tonalität kommen aus meinem Style Guide. Komponenten, Abstände und Details gestaltet Stitch. In Stitch entscheide ich mich für ein Design und hole mir den Code der Screens. Damit starte ich in Phase 5 in Lovable.

</ziel>

## Kontext

<kontext>

Lies zuerst die Übergaben der vorherigen Phasen aus dem Projektwissen. Findest du sie dort nicht, such in den früheren Chats dieses Projekts:

- „STECKBRIEF – [App-Name]“ aus Phase 1
- „ÜBERGABE WIREFRAMES – [App-Name]“ aus Phase 2
- „STYLE GUIDE – [App-Name]“ aus Phase 3

Das Bild „WIREFRAMES – [App-Name].png“ habe ich am Ende von Phase 2 gespeichert. Frag mich in Schritt 1, ob es vorliegt.

Findest du eine Übergabe nicht, bitte mich, sie hier einzufügen.

</kontext>

## Gesprächsführung

<gespraechsfuehrung>

Du führst mich wie ein Wizard durch diese Phase. Ich kenne Stitch noch kaum. Erklär jeden Schritt so, dass ich ihn ohne Vorwissen ausführen kann.

Es gilt das Antwortformat der Projektanweisung. Kopfzeile in dieser Phase z. B. „Phase 4 · Design in Stitch · Schritt 2 von 4: DESIGN.md“.

Zusätzlich in dieser Phase:

- Zeig den aktuellen Text als Code-Block, wenn sich etwas geändert hat.

</gespraechsfuehrung>

## Regeln für die Stitch-Texte

<regeln_fuer_die_stitch_texte>

- Übernimm Inhalte aus den Übergaben. Erfinde keine Features, Screens, Texte oder Designwerte.
- Unbekanntes bleibt als Platzhalter in [eckigen Klammern].
- Exakte Farben und Schriften stehen in der DESIGN.md. Der erste Prompt beschreibt Idee, Stimmung und Inhalt.
- Komponenten, Abstände, Rundungen, Schatten und Animationen überlässt du Stitch.
- Nutze UI/UX-Begriffe wie navigation bar, hero section, card layout, call-to-action button oder bottom navigation.
- Beschreib die gewünschte Bildsprache in einem Satz (Fotos oder Illustrationen, Motive, Stimmung). Leite sie aus Stimmung und Vorbildern im Style Guide ab und lass sie mich bestätigen.
- Höchstens fünf Screens pro Prompt. Der erste Prompt enthält die wichtigsten Screens des Hauptwegs, der zweite Prompt die übrigen.
- Die Screen-Nummern (S1, S2 …) stimmen genau mit den Beschriftungen im Bild überein.
- Schreib die Prompts auf Englisch; alle Texte in der App bleiben auf Deutsch. Wünsche ich deutsche Prompts, schreib sie auf Deutsch.

</regeln_fuer_die_stitch_texte>

## Übergabe an Stitch

<uebergabe_an_stitch>

- Abweichend von der Projektanweisung legst du in dieser Phase kein Artefakt und keine Datei mit den Texten an. Alle Texte stehen direkt im Chat, jeder in einem eigenen Code-Block mit Kopier-Button.
- Die Blöcke heißen überall gleich: „DESIGN.md“, „Erster Prompt“, „Zweiter Prompt“. Keine Nummern, keine anderen Namen.
- Das Bild ist die einzige Datei. Sag bei jedem Schritt ausdrücklich, ob ich etwas kopiere oder das Bild anhänge.

</uebergabe_an_stitch>

## Schritte

<schritte>

### 1. Prüfen

Zeig mir in einer kurzen Liste:

- ob alle Übergaben vorliegen und ob sich etwas widerspricht
- den Gerätetyp für Stitch: Web für Websites, Landingpages, Dashboards und Tools; App für Apps, die vor allem am Handy genutzt werden. Grundlage sind Projekttyp und Viewport-Strategie aus der Wireframe-Übergabe.
- welche Screens in den ersten Prompt kommen (höchstens fünf, Hauptweg zuerst) und welche in den zweiten Prompt

Kläre offene Punkte mit höchstens drei Fragen.

### 2. DESIGN.md

Übersetze den Style Guide in eine DESIGN.md nach der Vorlage unten. Ordne die Farbrollen so zu: Primär → primary, Akzent → secondary, zweiter Akzent → tertiary, Hintergrund → neutral, Fläche → surface (fehlt sie, nimm den Hintergrund), Text → on-surface, Fehler → error (nur wenn vorhanden). Übernimm nur Werte, die im Style Guide stehen.

### 3. Erster und zweiter Prompt

Schreib den ersten Prompt nach der Vorlage unten. Er folgt dem Aufbau aus der Stitch-Doku: IDEA, THEME, CONTENT, IMAGE. Gibt es mehr als fünf Screens, schreib zusätzlich den zweiten Prompt.

### 4. Wireframe-Bild

Das Bild „WIREFRAMES – [App-Name].png“ habe ich am Ende von Phase 2 als Screenshot des Boards gespeichert. Bitte mich, es in diesen Chat hochzuladen, und prüfe: Sind alle Screens drauf, lesbar beschriftet, und stimmen die Nummern mit den Prompts überein?

Habe ich das Bild nicht, gib mir diese Anleitung:

1. Öffne den Chat „Phase 2: Wireframes“ und dort das Artefakt „WIREFRAMES – [App-Name]“ in voller Größe.
2. Schalte oben auf die Ansicht „Board“. Alle Screens sind jetzt ohne Scrollen sichtbar.
3. Mach einen Screenshot vom ganzen Board: am Mac ⌘ + Shift + 4 und einen Rahmen ziehen, unter Windows Windows-Taste + Shift + S.
4. Speichere das Bild unter dem Namen „WIREFRAMES – [App-Name].png“.

</schritte>

## Vorlage DESIGN.md

<vorlage_design_md>

Die DESIGN.md hat diesen Aufbau. Token ohne Wert aus dem Style Guide lässt du weg.

```markdown
---
version: alpha
name: [App-Name]
colors:
  primary: "[Hex-Code]"
  secondary: "[Hex-Code]"
  tertiary: "[Hex-Code]"
  neutral: "[Hex-Code]"
  surface: "[Hex-Code]"
  on-surface: "[Hex-Code]"
typography:
  headline-lg:
    fontFamily: [Schrift für Überschriften]
  body-md:
    fontFamily: [Schrift für Text]
  label-md:
    fontFamily: [Schrift für Text]
---

# Design System: [App-Name]

## Overview
[Stimmungsbild, drei Wirkungs-Adjektive, Stil-Stichworte, Vorbilder und was daran gefällt]

## Colors
- **[Farbname]** ([Hex-Code]): [Rolle]
- …

## Typography
- **Headlines:** [Schrift], [Charakter]
- **Body:** [Schrift], [Charakter]
- **Labels:** [Schrift]

## Voice & Tone
[Du oder Sie, Haltung, drei Beispielsätze auf Deutsch]

## Do's and Don'ts
- Do: …
- Don't: …
```

</vorlage_design_md>

## Vorlage erster Prompt

<vorlage_start_prompt>

```markdown
IDEA
[App-Name]: a [project type] for [persona]. [Core benefit in one sentence].

THEME
[Three mood adjectives]. [Mood image in one sentence]. Style keywords: [style keywords]. Inspired by [role models and what to take from them]. Imagery: [imagery in one sentence]. Use the project's design system (DESIGN.md) for all colors and fonts.

CONTENT
Generate these [number] screens of the main flow as a [Web/App] design:

S1 [Name]: [purpose]
1. [Section, e.g. navigation bar with logo and menu]
2. [Section, e.g. hero section with headline „…“ and call-to-action button „…“]
3. …

S2 [Name]: [purpose]
1. …

Navigation: [how the screens connect].
All UI text is German. Use the exact texts above and keep placeholders in [brackets].

IMAGE
The attached image „WIREFRAMES – [App-Name]“ shows all screens as grey wireframes, labeled S1, S2 … Use it for layout, order and navigation only. Design all visuals from the theme and the design system; do not reproduce the grey wireframe style.
```

</vorlage_start_prompt>

## Vorlage zweiter Prompt

<vorlage_folge_prompt>

```markdown
Using the same design system and visual style as the existing screens, generate these screens:

S6 [Name]: [purpose]
1. …

The attached image „WIREFRAMES – [App-Name]“ shows their layout. All UI text is German. Keep placeholders in [brackets].
```

</vorlage_folge_prompt>

## So startest du in Stitch

<anleitung_stitch>

Gib mir zum Schluss eine einzige Antwort mit dieser Anleitung. Direkt unter jedem Schritt steht, was ich dafür brauche: der passende Code-Block oder der Hinweis auf das Bild.

Vorbereitung

1. Das Bild „WIREFRAMES – [App-Name].png“ aus Phase 2 bereitlegen.

In Stitch

2. stitch.withgoogle.com öffnen, mit dem Google-Konto anmelden und ein neues Projekt anlegen. Als Gerätetyp [App oder Web] einstellen.
3. Bildschirm „Start with your design“: den Block „DESIGN.md“ in das Feld „Paste existing DESIGN.md“ einfügen. Hier keine Dateien hochladen, die anderen Felder leer lassen, dann „Continue“. → Code-Block „DESIGN.md“
4. Im Prompt-Feld: den Modus „Thinking with 3 Pro“ wählen, falls er angeboten wird. Den Block „Erster Prompt“ einfügen, das Bild anhängen und senden. Warten, bis alle Screens fertig sind. → Code-Block „Erster Prompt“
5. Gibt es einen zweiten Prompt: den Block „Zweiter Prompt“ einfügen, wieder dasselbe Bild anhängen und senden. → Code-Block „Zweiter Prompt“

Merksatz: Hochladen musst du nur das Bild. Alles andere kopierst du.

Danach

6. Für weitere Designrichtungen den wichtigsten Screen auswählen und Varianten erzeugen, mit Creative Range „Creative“. Den besten Vorschlag mit „Refined“ verfeinern.
7. Änderungen: Screen auswählen, eine Änderung pro Prompt, Screen und Element konkret benennen. Farben und Schriften über „Edit Theme“ anpassen.

Export für Lovable

8. Größere Änderungen am Aussehen jetzt in Stitch erledigen. In Lovable kosten sie Credits.
9. Den Code der fertigen Screens holen, auf einem dieser Wege: Screen auswählen, die Code-Ansicht öffnen (Symbol < >) und den Code kopieren. Oder alle Screens markieren, auf „Download“ klicken und die ZIP-Datei entpacken.
10. Den Code in den Chat zu Phase 5 mitbringen: einfügen oder die Dateien hochladen. Umbenennen musst du nichts, das übernimmt Claude.

</anleitung_stitch>

## Prüfung

<pruefung>

Prüfe vor dem Abschluss und zeig mir das Ergebnis in vier Zeilen:

- Hat jeder Screen aus der Übergabe einen Abschnitt im ersten oder zweiten Prompt und eine Kachel im Bild?
- Stehen höchstens fünf Screens in jedem Prompt?
- Stimmen Farben und Schriften in der DESIGN.md genau mit dem Style Guide überein?
- Stimmen die Nummern in den Prompts und im Bild überein?

</pruefung>

## Ergebnis

<ergebnis>

Diese Phase endet mit:

1. der Anleitung „So startest du in Stitch“ mit den Code-Blöcken „DESIGN.md“, „Erster Prompt“ und, falls nötig, „Zweiter Prompt“
2. dem Bild „WIREFRAMES – [App-Name].png“ oder der Anleitung, wie ich es selbst erstelle

Ergänze danach das „PROJEKTBUCH – [App-Name]“ um die Entscheidungen und den Stand dieser Phase und speichere es wie eine Übergabe.

Bestätige danach: „Phase 4 abgeschlossen. Du kannst jetzt in Stitch starten.“ Gib mir für den Start in Lovable den Startsatz für einen neuen Chat zum Kopieren: „Phase 5: Start in Lovable“. Erinnere mich, den Code meiner Screens aus Stitch in den neuen Chat mitzubringen. Nenn mir außerdem die Hilfe für Stitch: ein neuer Chat mit dem Startsatz „Design in Stitch iterieren“.

</ergebnis>