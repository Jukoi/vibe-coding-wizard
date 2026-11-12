## Ziel

<ziel>

In diesem Chat bekommt mein GitHub-Repository aus Phase 10 eine Startseite, die aussieht wie bei den besten Repos auf GitHub. Am Ende liegen im Repo:

1. eine aufwendig gestaltete `README.md` als Startseite
2. der Ordner `docs/` mit der Dokumentation aller Phasen, ergänzt um das, was seit Phase 10 dazugekommen ist
3. ein Ordner `assets/` mit Banner, Screenshots und Grafiken
4. eine gepflegte About-Box mit Beschreibung, Link und Topics

Ich will dabei lernen, wie man ein Projekt so präsentiert, dass andere es in einer Minute verstehen und ernst nehmen.

</ziel>

## Kontext

<kontext>

Lies zuerst das Projektbuch und alle Übergaben aus dem Projektwissen. Findest du sie dort nicht, such in den früheren Chats dieses Projekts:

- „STECKBRIEF – [App-Name]“ aus Phase 1: Name, Kernnutzen, Problem, Persona, MVP, Ideen für später
- „ÜBERGABE WIREFRAMES – [App-Name]“ aus Phase 2: Sitemap, User Flow, Screens
- „STYLE GUIDE – [App-Name]“ aus Phase 3, mit dem Abschnitt „Stand nach Design“: Farben mit Hex-Codes, Schriften, Tonalität
- „DATENMODELL – [App-Name]“ aus Phase 7 und „KI-STECKBRIEF – [App-Name]“ aus Phase 8, falls vorhanden
- „PROJEKTBUCH – [App-Name]“: Repo-Link, Sichtbarkeit, „GitHub-Verbindung in Lovable“, Entscheidungen, Prompt-Protokoll

Zeig mir im Einstieg eine Tabelle: welche Unterlagen du gefunden hast und welche fehlen. Fehlende Teile lässt du in der README weg.

</kontext>

## Voraussetzungen

<voraussetzungen>

Prüfe mit mir vor Schritt 1 diese drei Punkte und erklär jeden in einem Satz:

1. Mein Repo aus Phase 10 existiert. Den Link liest du im Projektbuch; fehlt er, frag mich danach. Gibt es noch kein Repo, schick mich zuerst in einen neuen Chat mit dem Startsatz „Phase 10: Code auf GitHub“.
2. Du kommst an den Inhalt des Repos: über einen GitHub-Zugriff in diesem Chat, oder ich lade die `package.json` und eine Liste der Ordner hoch.
3. Ich habe zwei, drei Screenshots meiner App aus der Lovable-Vorschau (Handy und Desktop) und hänge sie hier an. Nur mit Beispieldaten.

Fehlt etwas, gib mir die Schritte dazu und warte, bis ich „erledigt“ schreibe.

Fasse mir danach in drei Zeilen zusammen, was die App technisch ist (Technik aus `package.json`, Seiten, Datenbank ja oder nein).

</voraussetzungen>

## Gesprächsführung

<gespraechsfuehrung>

Es gilt das Antwortformat der Projektanweisung. Kopfzeile in dieser Phase z. B. „Phase 11 · GitHub-Auftritt · Schritt 3 von 6: Banner und Grafiken“.

Ich kenne mich mit GitHub kaum aus. Begriffe wie Repository, Commit, Badge (kleines Etikett mit Status oder Technik), Markdown oder Mermaid (Diagramme aus Text) erklärst du in einem Halbsatz.

Zusätzlich in dieser Phase:

- Erfinde keine Zahlen, Nutzer, Sterne, Downloads oder Zitate.
- „Stand“ zeigt den aktuellen Entwurf der README.

</gespraechsfuehrung>

## Sicherheit

<sicherheit>

Prüfe vor jedem Schreiben ins Repo:

- Keine API-Keys, Passwörter, Tokens oder `.env`-Inhalte in README, Docs oder Bildern. Findest du solche Werte im Code, warne mich sofort und erklär, wie ich sie in die Secrets von Lovable verschiebe.
- Keine echten personenbezogenen Daten (Gesundheit, Finanzen, Kontaktdaten Dritter). Screenshots nur mit Beispieldaten.
- Ist das Repo öffentlich, weise mich darauf hin, dass alles darin für jeden sichtbar ist.
- Schreib erst ins Repo, wenn ich die Vorschau freigegeben habe.

</sicherheit>

## Bausteine der README

<bausteine>

Nutze alles, was GitHub darstellen kann, im Design meines Style Guides:

| Baustein | Umsetzung |
|---|---|
| Banner | SVG in `assets/banner.svg` mit App-Name, Kernsatz und den Farben aus dem Style Guide; Hell- und Dunkel-Variante über `<picture>` |
| Badges | shields.io in den Style-Guide-Farben: Status, Technik (z. B. React, Tailwind, Supabase), „Built with Lovable“, Lizenz |
| Kernsatz | ein Satz direkt unter dem Banner, zentriert |
| Navigation | Inhaltsverzeichnis mit Sprungmarken |
| Screenshots | Handy und Desktop nebeneinander in einer Tabelle; ohne Screenshot ein beschrifteter Platzhalter |
| Demo-GIF | optional, wenn ich eins liefere |
| Problem & Lösung | aus dem Steckbrief, kurz |
| Features | Tabelle oder Liste mit Emoji-Icons aus den MVP-Features |
| User Flow | Mermaid-Diagramm aus der Wireframe-Übergabe |
| Sitemap | Mermaid-Diagramm (Baum) |
| Architektur | Mermaid-Diagramm: Frontend, Supabase, KI-Funktion, externe Dienste; nur was es in meiner App gibt |
| Datenmodell | Mermaid-ER-Diagramm, falls Phase 7 vorliegt |
| Design System | Farbfelder (kleine SVG-Quadrate je Hex-Code), Schriften, Stil-Stichworte |
| Hinweisboxen | `> [!NOTE]`, `> [!TIP]`, `> [!IMPORTANT]` für Wichtiges |
| Aufklapp-Bereiche | `<details>` für lange Teile (Prompt-Protokoll, alle Screens) |
| Entstehung | „So ist das Projekt entstanden“: Zeitleiste meiner Phasen als Mermaid-Timeline, nur die Phasen, die ich durchlaufen habe |
| Roadmap | Checkliste aus „Ideen für später“ |
| Schnellstart | lokal starten in drei Schritten (`npm install`, `npm run dev`), Link zur Live-Version |
| Credits & Lizenz | Lovable, Claude, Schulung, Lizenz (Vorschlag MIT, ich entscheide) |

Gestaltung:

- Farben aus dem Style Guide in Banner, Badges und Diagrammen, exakt nach Hex-Code.
- Schrift im Banner: GitHub lädt in SVG-Bildern keine Google Fonts. Wandle den Text in Pfade um oder nimm eine Systemschrift, die dem Charakter meiner Überschrift-Schrift nahekommt, und sag mir, welche.
- Tonalität aus dem Style Guide (Du oder Sie).
- Viel Luft: Trennlinien zwischen Abschnitten, kurze Absätze, auf einen Blick zu erfassen.
- Die README muss auf dem Handy und im Dark Mode gut aussehen.

</bausteine>

## Schritte

<schritte>

1. Bestand: Übergaben und Repo prüfen, Ergebnis als Tabelle (siehe Kontext und Voraussetzungen).
2. Aufbau: Zeig mir die geplante Gliederung der README und was in `docs/` und `assets/` dazukommt. Ich bestätige oder passe an.
3. Banner und Grafiken: Zeig mir zwei Banner-Varianten als Karten zur Auswahl und die Mermaid-Diagramme als Vorschau-Artefakt.
4. README-Entwurf: Zeig mir die komplette README als Vorschau, so wie GitHub sie darstellt. Danach eine Feedback-Runde mit drei typischen Änderungen als Optionen.
5. Docs: Vergleiche `docs/` im Repo mit meinen Übergaben. Ergänze nur, was fehlt oder sich geändert hat (Namensschema `01-steckbrief.md`, `02-wireframes.md` …), und verlinke alles in der README.
6. Veröffentlichen: Nach meiner Freigabe schreibst du alles als einen Commit ins Repo („docs: README und Projektdokumentation“). Die bestehende README wird ersetzt; sag mir das vorher. Kannst du nicht schreiben, gib mir alle Dateien als ZIP zum Herunterladen und diese Anleitung:
   1. Das Repo auf github.com öffnen, „Add file“ → „Upload files“.
   2. ZIP entpacken, `README.md`, `docs` und `assets` ins Fenster ziehen.
   3. Unten auf „Commit changes“ klicken.

Danach gibst du mir diese Anleitung für die Feinheiten auf github.com:

1. Repo öffnen, Zahnrad neben „About“: Beschreibung (Kernsatz), Website (Link zur Live-Version), Topics (z. B. `lovable`, `vibe-coding`, `react`, `supabase`, [Thema der App]).
2. Settings → General → Social preview: das Banner als PNG hochladen. Gib mir dafür das Banner zusätzlich als PNG; kannst du keins erzeugen, sag mir, wie ich einen Screenshot vom Banner mache.
3. Optional: Profil-README anlegen (ein Repo mit dem eigenen Benutzernamen) und das Projekt dort verlinken.

</schritte>

## Prüfung

<pruefung>

Prüfe vor dem Abschluss und zeig mir das Ergebnis in sechs Zeilen:

- Versteht jemand in einer Minute, was die App macht und für wen?
- Stammen alle Inhalte aus den Übergaben, ohne erfundene Zahlen?
- Rendern alle Mermaid-Diagramme fehlerfrei?
- Passen die Farben zum Style Guide, in Hell und Dunkel?
- Sind keine Secrets und keine echten personenbezogenen Daten im Repo?
- Funktionieren alle Links und Bilder?

</pruefung>

## Ergebnis

<ergebnis>

Ergänze das „PROJEKTBUCH – [App-Name]“ um den Stand „GitHub-Auftritt fertig“ und speichere es wie eine Übergabe.

Gib mir danach die Abschlussantwort nach der Projektanweisung. Sie beginnt mit „Phase 11 abgeschlossen. Dein Projekt ist jetzt vorzeigbar.“ und enthält zusätzlich:

- den Link zum Repo
- die Anleitung für About-Box und Social Preview
- steht im Projektbuch „GitHub-Verbindung in Lovable: nein“: die Erinnerung, nach größeren Änderungen in Lovable den neuen Stand mit „Phase 10: Code auf GitHub“ erneut hochzuladen

Startsätze für danach: „Phase 6: Iterieren“ für Änderungen an der App, „Phase 11: GitHub-Auftritt“, um die README später zu aktualisieren.

</ergebnis>
