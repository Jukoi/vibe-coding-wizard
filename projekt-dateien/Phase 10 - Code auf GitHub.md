## Ziel

<ziel>

In diesem Chat bringen wir mein Lovable-Projekt sicher in ein eigenes GitHub-Repository. Am Ende liegen dort:

1. der komplette Code meiner App, eins zu eins wie in Lovable
2. meine Projektunterlagen aus allen Phasen im Ordner `docs/`
3. eine einfache `README.md` als Startseite (die gestaltete Version folgt in Phase 11)

Ich will dabei verstehen, was GitHub ist, wofür ich es brauche und wie ich meinen Code damit sichere.

</ziel>

## Kontext

<kontext>

Lies zuerst das Projektbuch und alle Übergaben aus dem Projektwissen. Findest du sie dort nicht, such in den früheren Chats dieses Projekts:

- „STECKBRIEF – [App-Name]“ aus Phase 1
- „ÜBERGABE WIREFRAMES – [App-Name]“ aus Phase 2
- „STYLE GUIDE – [App-Name]“ aus Phase 3, mit dem Abschnitt „Stand nach Design“
- „DATENMODELL – [App-Name]“ aus Phase 7 und „KI-STECKBRIEF – [App-Name]“ aus Phase 8, falls vorhanden
- „PROJEKTBUCH – [App-Name]“

Prüfe selbst, ob mein Code schon erreichbar ist: als hochgeladene Dateien oder ZIP in diesem Chat oder im Projekt, oder über Lovable-Werkzeuge in diesem Chat. Frag mich nur, wenn du nichts findest.

Zeig mir im Einstieg eine Tabelle: welche Unterlagen du gefunden hast, welche fehlen und ob der Code vorliegt.

</kontext>

## Gesprächsführung

<gespraechsfuehrung>

Es gilt das Antwortformat der Projektanweisung. Kopfzeile in dieser Phase z. B. „Phase 10 · Code auf GitHub · Schritt 4 von 8: Verbindung prüfen“.

Ich bin Einsteiger. Erklär jeden Begriff beim ersten Mal mit einem Bild aus dem Alltag, z. B.:

- Repository (Repo): ein Projektordner im Internet, der sich jede Version merkt
- Commit: ein gespeicherter Zwischenstand mit kurzer Notiz, wie ein Speicherpunkt im Spiel
- Branch: eine Parallelversion zum Ausprobieren
- `.gitignore`: eine Liste, was nie hochgeladen werden darf
- README: die Startseite des Repos

Zusätzlich in dieser Phase:

- Jede Option erklärst du in einem Satz: was sie für mich bedeutet.
- Schreib erst ins Repo, wenn ich die Vorschau freigegeben habe.

</gespraechsfuehrung>

## Schritte

<schritte>

### 1. GitHub-Konto

Frag mich, ob ich schon ein GitHub-Konto habe (Sachfrage, keine Empfehlung):

- 1A) Ja, ich habe ein Konto
- 1B) Nein, noch keins

Bei 1B gib mir diese Anleitung und warte auf „erledigt“:

1. github.com öffnen, „Sign up“, mit einer E-Mail-Adresse, die ich dauerhaft nutze.
2. Benutzername wählen: Er steht später in jeder Repo-Adresse (github.com/benutzername/…), also lieber seriös.

### 2. Sichtbarkeit

- 1A) Privat (Empfehlung: zum Lernen und solange die App unfertig ist): Nur ich und Leute, die ich einlade, sehen das Repo.
- 1B) Öffentlich: Jeder im Internet sieht Code und Unterlagen. Gut als Portfolio, aber alles darin bleibt auffindbar.

Sag mir, dass ich die Sichtbarkeit später unter Settings → General → „Change visibility“ umstellen kann.

### 3. Name und Beschreibung

Schlag mir drei Repo-Namen vor, abgeleitet aus dem App-Namen: klein geschrieben, mit Bindestrichen, ohne Umlaute und Leerzeichen (z. B. `mein-haushaltsbuch`). Dazu eine Kurzbeschreibung in einem Satz aus dem Kernnutzen.

### 4. GitHub-Verbindung in Lovable prüfen

Frag mich, ob ich in Lovable meinen GitHub-Account verbinden kann. Das ist eine Sachfrage, hier gibt es keine Empfehlung:

- 1A) Ja: In Lovable gibt es bei mir „GitHub“ → „Connect“, und die Verbindung klappt.
- 1B) Nein: Die Verbindung ist bei mir gesperrt oder ausgegraut, z. B. im Workspace meiner Schulung oder meiner Firma.
- 1C) Weiß ich nicht: Du zeigst mir, wie ich es in einer Minute prüfe.

Bei 1C gib mir diese Anleitung und warte auf meine Antwort:

1. Projekt in Lovable öffnen, oben rechts auf „GitHub“ klicken.
2. Erscheint „Connect“ und lässt sich mein GitHub-Konto auswählen: Antwort 1A.
3. Fehlt der Button, ist er ausgegraut oder kommt eine Fehlermeldung: Antwort 1B.

Daraus ergibt sich der Weg:

| Antwort | Weg | Was das bedeutet |
|---|---|---|
| 1A | Verbunden | Lovable legt das Repo an und schreibt ab dann jede Änderung automatisch hinein |
| 1B | Momentaufnahme | Du baust das Repo aus dem aktuellen Stand meines Codes. Spätere Änderungen in Lovable landen erst im Repo, wenn ich den neuen Stand wieder hochlade |

Halte die Antwort im Projektbuch fest: „GitHub-Verbindung in Lovable: ja“ oder „nein“.

### 5. Code ins Repo

Weg „Verbunden“: Führ mich Schritt für Schritt durch die Verbindung in Lovable („GitHub“ → „Connect“ → Konto wählen → Repository anlegen, mit Name und Sichtbarkeit aus Schritt 2 und 3). Warte auf „erledigt“ und den Link zum Repo.

Weg „Momentaufnahme“: Du brauchst den Code als Dateien.

- Liegt er schon vor, nimm ihn.
- Fehlt er, bitte mich, ihn aus Lovable herunterzuladen und die ZIP-Datei hier hochzuladen. Stehen dir in diesem Chat Lovable-Werkzeuge zur Verfügung, darfst du den Code stattdessen dort lesen.
- Übernimm alle Dateien und Ordner eins zu eins: gleiche Namen, gleiche Struktur, gleicher Inhalt. Ändere, formatiere oder „verbessere“ nichts.
- Kopiere Dateien als Dateien, per Skript. Tippe keinen Code ab. Kannst du Dateien nur lesen und nicht kopieren, sag es mir und bitte mich um die ZIP-Datei.
- Lass weg, was nicht ins Repo gehört: `node_modules/`, `dist/`, `.env` und andere Dateien mit Schlüsseln. Leg dafür eine `.gitignore` an, falls keine da ist.

### 6. Inhalt prüfen

Zeig mir die geplante Ordnerstruktur:

```
[repo-name]/
├── README.md
├── .gitignore
├── docs/
│   ├── 01-steckbrief.md
│   ├── 02-wireframes.md
│   ├── 03-style-guide.md
│   ├── …
│   └── projektbuch.md
└── [Code aus Lovable, eins zu eins: src/, public/, package.json, …]
```

Docs: je vorhandener Übergabe eine Datei in `docs/`, Inhalt unverändert.

Sicherheits-Check, Ergebnis als Tabelle mit Ampel:

- Suche im Code nach API-Keys, Passwörtern, Tokens und `.env`-Inhalten. Findest du etwas, warne mich, nimm es nicht ins Repo und erklär, wie ich den Wert in Lovable unter Secrets ablege.
- Suche in den Unterlagen nach echten persönlichen Daten (Gesundheit, Finanzen, Adressen, Telefonnummern). Ist das Repo öffentlich, frag mich, ob sie wirklich hinein sollen.
- Der öffentliche Supabase-„anon key“ darf im Code stehen; erklär mir in einem Satz, warum.

### 7. README (einfach)

Erstelle eine schlichte `README.md` und zeig sie mir als Vorschau:

- App-Name und Kernsatz
- Problem und Lösung in zwei, drei Sätzen
- Link zur Live-Version, falls vorhanden, sonst Platzhalter
- Technik (aus `package.json`), Hinweis „gebaut mit Lovable“
- Lokal starten: `npm install`, `npm run dev`
- Liste der Unterlagen in `docs/` mit Links

Beim Weg „Verbunden“ liegt schon eine README von Lovable im Repo. Sag mir, dass deine Version sie ersetzt, und warte auf mein Okay.

### 8. Hochladen

Nach meiner Freigabe:

- Kannst du ins Repo schreiben: Beim Weg „Momentaufnahme“ legst du das Repo mit Name, Beschreibung und Sichtbarkeit an und lädst alles in einem Commit hoch („Erster Stand aus Lovable inkl. Projektunterlagen“). Beim Weg „Verbunden“ ergänzt du nur `docs/` und die README („docs: Projektunterlagen und README“).
- Kannst du es nicht: Gib mir die Dateien als ZIP zum Herunterladen und die passende Anleitung.

Anleitung Weg „Momentaufnahme“:

1. github.com öffnen, oben rechts „+“ → „New repository“.
2. Name, Beschreibung und Sichtbarkeit wie besprochen eintragen. Den Haken bei „Add a README“ weglassen.
3. „Create repository“ anklicken, dann den Link „uploading an existing file“.
4. ZIP entpacken, den Ordner öffnen, alles darin markieren und ins Fenster ziehen.
5. Unten auf „Commit changes“ klicken.
6. Nimmt GitHub nicht alle Dateien auf einmal an: in mehreren Portionen hochladen, Ordner für Ordner.

Anleitung Weg „Verbunden“:

1. Das Repo auf github.com öffnen, „Add file“ → „Upload files“.
2. ZIP entpacken, den Ordner `docs` und die `README.md` ins Fenster ziehen.
3. Unten auf „Commit changes“ klicken.

Prüfe danach mit mir: Ist der Code drin, sind `docs/` und README zu sehen, fehlt `.env`?

</schritte>

## Grundwissen zum Abschluss

<grundwissen>

Erklär mir zum Schluss in je einem Satz:

- wie ich auf github.com eine ältere Version einer Datei ansehe („History“)
- was passiert, wenn ich in Lovable weiterbaue (Weg „Verbunden“: das Repo aktualisiert sich von selbst; Weg „Momentaufnahme“: neuen Stand mit dem Startsatz „Phase 10: Code auf GitHub“ erneut hochladen)
- wie ich jemanden einlade (Settings → Collaborators), z. B. meinen Dozenten
- dass ich nie Passwörter oder Keys ins Repo lege

Gib mir danach als letzten Punkt diese Empfehlung für nach der Schulung:

- Zwei-Faktor-Anmeldung einschalten: github.com → Settings → Password and authentication. Damit kommt niemand allein mit meinem Passwort an meinen Code. Fordert GitHub sie schon vorher von selbst ein, folge ich der Aufforderung.

</grundwissen>

## Prüfung

<pruefung>

Prüfe vor dem Abschluss und zeig mir das Ergebnis in fünf Zeilen:

- Ist der Code vollständig und unverändert im Repo?
- Sind alle vorhandenen Unterlagen in `docs/`?
- Sind keine Secrets und keine `.env` im Repo?
- Stimmt die Sichtbarkeit mit meiner Wahl überein?
- Weiß ich, wie das Repo in Zukunft aktuell bleibt?

</pruefung>

## Ergebnis

<ergebnis>

Ergänze das „PROJEKTBUCH – [App-Name]“ um Repo-Link, Sichtbarkeit und Weg („Verbunden“ oder „Momentaufnahme“) und speichere es wie eine Übergabe.

Gib mir danach die Abschlussantwort nach der Projektanweisung. Sie beginnt mit „Phase 10 abgeschlossen. Dein Code ist auf GitHub gesichert.“ und enthält zusätzlich:

- den Repo-Link
- die Ordnerstruktur in Kurzform
- das Grundwissen und die Empfehlung zur Zwei-Faktor-Anmeldung

Startsatz der nächsten Phase: „Phase 11: GitHub-Auftritt“. Für Änderungen an der App: „Phase 6: Iterieren“.

</ergebnis>
