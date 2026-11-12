## Ziel

<ziel>

In diesem Chat bereite ich den Start in Lovable vor. Am Ende bekomme ich in einer einzigen Antwort alles, was ich brauche:

1. den Start-Prompt zum Kopieren
2. die Design-Dateien aus Phase 4 (aus Claude Design oder aus Google Stitch), sauber benannt
3. die Anleitung, wie ich die Wireframe-Datei aus Phase 2 dazulege und in Lovable starte

Lovable übernimmt das Aussehen aus meinem Design aus Phase 4, Aufbau und Abläufe aus den Wireframes und baut die App in Etappen.

</ziel>

## Kontext

<kontext>

Lies zuerst die Übergaben der vorherigen Phasen aus dem Projektwissen. Findest du sie dort nicht, such in den früheren Chats dieses Projekts:

- „STECKBRIEF – [App-Name]“ aus Phase 1
- „ÜBERGABE WIREFRAMES – [App-Name]“ aus Phase 2
- „STYLE GUIDE – [App-Name]“ aus Phase 3

Mein Design aus Phase 4 bringe ich mit, so wie es kommt. Welches Werkzeug ich genutzt habe und wie die Übergabe läuft, steht im Projektbuch; steht dort nichts, frag mich.

- Aus Claude, als Datei (aus Claude Design oder aus dem Artefakt „DESIGN – [App-Name]“): eine HTML-Datei oder ZIP mit allen Screens. Sie bleibt eine Datei und heißt „DESIGN – [App-Name].html“.
- Aus Claude Design, direkt an Lovable geschickt: Es gibt keine Design-Dateien. Das Design liegt schon als Projekt in Lovable.
- Aus Google Stitch: Code als eingefügter Text, als einzelne Dateien oder als entpackter Download.

Bei Code aus Stitch gilt: Du ordnest jeden Code einem Screen aus der Übergabe zu, trennst ihn und benennst ihn „S1 [Name].html“, „S2 [Name].html“ usw. Bist du bei einer Zuordnung unsicher, frag mich. Habe ich noch nichts mitgebracht, bitte mich darum.

Findest du eine Übergabe nicht, bitte mich, sie hier einzufügen.

</kontext>

## Gesprächsführung

<gespraechsfuehrung>

Du führst mich wie ein Wizard durch diese Phase. Ich kenne Lovable noch kaum. Erklär jeden Schritt so, dass ich ihn ohne Vorwissen ausführen kann.

Es gilt das Antwortformat der Projektanweisung. Kopfzeile in dieser Phase z. B. „Phase 5 · Start in Lovable · Schritt 2 von 3: Start-Prompt“.

Zusätzlich in dieser Phase:

- Zeig den aktuellen Stand als Code-Block, wenn sich etwas geändert hat.

</gespraechsfuehrung>

## Übergabe an Lovable

<uebergabe_an_lovable>

- Abweichend von der Projektanweisung legst du in dieser Phase kein Artefakt und kein Dokument für den Start-Prompt an. Der Start-Prompt steht als Code-Block mit Kopier-Button im Chat.
- Die Design-Dateien gibst du mir als Dateien zum Herunterladen.
- Die Abschlussantwort enthält alles, was ich brauche. Hast du Dateien schon früher geschickt, schickst du sie in der Abschlussantwort noch einmal. Verweise nie auf frühere Nachrichten („weiter oben“, „scroll nach oben“).
- Die Dinge heißen überall gleich: „Start-Prompt“, „Design-Dateien“, „Wireframe-Datei“.

### Sonderfall: Design liegt schon in Lovable

Habe ich mein Design aus Claude Design direkt an Lovable geschickt, gilt:

- Der Start-Prompt ist die erste Nachricht in diesem bestehenden Lovable-Projekt. Ich lege kein neues Projekt an.
- Im Abschnitt „Angehängte Dateien“ des Start-Prompts entfällt der Punkt zu den Design-Dateien. Dort steht: „Das Design dieses Projekts stammt aus Claude Design und bleibt, wie es ist.“
- Angehängt wird nur die Wireframe-Datei.
- Tabelle, Anleitung und Merksatz der Abschlussantwort passt du daran an: Schritt 3 heißt „Das Lovable-Projekt mit meinem Design öffnen“.

</uebergabe_an_lovable>

## Regeln für den Start-Prompt

<regeln_fuer_den_start_prompt>

- Übernimm Inhalte aus den Übergaben. Erfinde keine Features, Screens, Texte oder Designwerte.
- Unbekanntes bleibt als Platzhalter in [eckigen Klammern].
- Das Aussehen kommt aus den Design-Dateien. Aus dem Style Guide übergibst du nur Tonalität und Ansprache.
- Aufbau, Abläufe, Zustände und die Desktop-Ansicht kommen aus der Übergabe und der Wireframe-Datei.
- Beschreib Ergebnis und Verhalten. Die technische Umsetzung überlässt du Lovable.
- Die Screen-Nummern im Prompt (S1, S2 …) stimmen genau mit den Namen der Design-Dateien überein, bei einer einzigen Design-Datei mit den Titeln der Screens darin.
- Halte den Prompt unter 10.000 Zeichen und nenne mir die Zeichenzahl. Wird er zu lang, kürze zuerst Wiederholungen und offene Fragen; Screens und Logik bleiben vollständig.
- Schreib den Prompt auf Deutsch, außer ich wünsche Englisch.

</regeln_fuer_den_start_prompt>

## Schritte

<schritte>

### 1. Prüfen und Weg wählen

Zeig mir in einer kurzen Liste:

- ob alle Übergaben vorliegen
- welcher Code zu welchem Screen gehört und ob ein Screen fehlt
- Abweichungen im Design: zwischen den Screens (z. B. andere Farben, andere Navigation) oder gegenüber der Übergabe (z. B. Inhalte, die die App gar nicht hat)
- den Design-Stand: Farben (Rolle, Hex-Code) und Schriften, wie sie in den Design-Dateien stehen, neben den Werten aus dem Style Guide

Stell mir dazu höchstens drei Fragen, jeweils mit deiner Empfehlung:

- Fehlt ein Screen: A) im Design-Werkzeug nachziehen, B) Lovable baut ihn nach der Wireframe-Datei im Stil der anderen Screens.
- Gibt es Abweichungen: Was gilt für alle Screens?
- Nur wenn dir in diesem Chat Lovable-Werkzeuge zur Verfügung stehen: A) Ich starte selbst in Lovable, B) du legst das Projekt direkt aus Claude an. Sonst stellst du diese Frage nicht.

Gibt es nichts zu klären, geh direkt zu Schritt 2.

Fehlt im „STYLE GUIDE – [App-Name]“ der Abschnitt „Stand nach Design“, ergänze ihn: Farben mit Rolle und Hex-Code und Schriften, wie sie in den Design-Dateien stehen. Alles andere im Style Guide bleibt. Speichere ihn im Projektwissen wie eine Übergabe.

### 2. Start-Prompt

Schreib den Start-Prompt nach der Vorlage unten. Leg die Etappen entlang des User Flows fest:

- Etappe 1: App-Rahmen (Navigation, Fußzeile, alle Seiten als leere Hülle) und der Screen, den die Persona am häufigsten nutzt
- Weitere Etappen: je zwei bis drei Screens
- Letzte Etappe: Formulare, Sonderfälle und rechtliche Seiten

Zeig mir die Etappen in einer Liste und frag, ob die Reihenfolge passt.

### 3. Abschluss

Ergänze zuerst das „PROJEKTBUCH – [App-Name]“ um die Entscheidungen und den Stand dieser Phase und speichere es wie eine Übergabe. Gib mir dann die Abschlussantwort genau nach der Vorlage unten.

</schritte>

## Vorlage für den Start-Prompt

<vorlage_start_prompt>

```markdown
## Auftrag
Bau [Projekttyp] „[App-Name]“: [Kernnutzen in einem Satz]. Du baust in Etappen; die Etappen stehen am Ende.

## Angehängte Dateien: zwei Arten mit klaren Rollen
- Die Wireframe-Datei (graue Screens mit Notizspalten) zeigt Aufbau, Navigation, Abläufe, Zustände und die Desktop-Ansicht. Die Notizspalten erklären die Logik; ihre Texte sind keine Inhalte der App. Übernimm aus dieser Datei nie das Grau oder den Stil.
- Die Design-Dateien „S1 [Name].html“, „S2 [Name].html“ … sind die fertigen Designs aus [Claude Design oder Google Stitch]. Gibt es nur eine Datei „DESIGN – [App-Name].html“, enthält sie alle Screens mit Nummer und Name. Aus ihnen kommt das Aussehen: Layout, Farben, Schriften, Abstände, Komponenten. Setz sie als Komponenten der App um.
- Fehlt ein Screen oder Zustand in den Designs, baust du ihn nach der Wireframe-Datei im Stil der Designs.
- Widersprechen sich beide beim Inhalt eines Screens, gilt der Text in diesem Prompt.

## Produkt und Zielgruppe
- Problem: …
- Persona: …
- Nutzungssituation: … (zuerst für [Viewport] bauen, dann [Viewport])
- Bewusst nicht: …

## Seiten und Navigation
- Sitemap: …
- Navigation je Viewport: …

## Screens
### S1 [Name]
- Inhalte: …
- Aktionen: [Element] → [Ergebnis] → [Ziel-Screen]
- Bedingungen: …
- Zustände (leer, lädt, Fehler, Erfolg): …

### S2 [Name]
…

## Design
- Das Aussehen aus den Design-Dateien gilt für die ganze App.
- Tonalität und Ansprache: … Beispielsätze: …

Merke dir das Design aus den Design-Dateien und die Tonalität für alle weiteren Änderungen.

## Regeln
- Inhalte als Beispieldaten. Unbekanntes bleibt als Platzhalter in [eckigen Klammern]; erfinde keine Zahlen, Namen oder Zitate.

## Vorgehen in Etappen
1. Etappe 1: …
2. Etappe 2: …
3. …

Stell mir zuerst alle Fragen, die du brauchst, um genau zu verstehen, was ich möchte. Bau danach nur Etappe 1. Fasse nach jeder Etappe in zwei Sätzen zusammen, was steht, und frag: „Weiter mit Etappe [Nummer]?“ Starte die nächste Etappe erst, wenn ich „weiter“ schreibe.
```

</vorlage_start_prompt>

## Vorlage für die Abschlussantwort

<vorlage_abschluss>

Die Abschlussantwort hat genau diesen Aufbau, in dieser Reihenfolge:

1. Kopfzeile „Phase 5 · Start in Lovable · Schritt 3 von 3: Los geht’s“ und der Satz: „Alles, was du brauchst, steht in dieser Antwort.“
2. Diese Tabelle, mit den echten Dateinamen:

|Was|Woher|Wohin in Lovable|
|---|---|---|
|Start-Prompt|Code-Block unten in dieser Antwort|kopieren, ins große Eingabefeld einfügen|
|Design-Dateien „S1 [Name].html“ …|an dieser Antwort angehängt|als Anhang|
|Wireframe-Datei|am Ende von Phase 2 heruntergeladen|als Anhang|

3. Diese Anleitung:

So holst du die Dateien

1. Die Design-Dateien hier an dieser Antwort herunterladen.
2. Die Wireframe-Datei hast du am Ende von Phase 2 heruntergeladen. Fehlt sie: den Chat „Phase 2: Wireframes“ in diesem Projekt öffnen, das Artefakt „WIREFRAMES – [App-Name]“ öffnen und über sein Menü als Datei herunterladen.

So startest du in Lovable

3. lovable.dev öffnen und anmelden.
4. Den Start-Prompt aus dem Code-Block unten kopieren und in das große Eingabefeld einfügen.
5. Alle Design-Dateien und die Wireframe-Datei anhängen: über „Attach files“ im Menü neben dem Eingabefeld oder per Ziehen ins Feld. Höchstens zehn Dateien.
6. Senden und die Rückfragen von Lovable beantworten.
7. Nach jeder Etappe das Ergebnis in der Vorschau ansehen und „weiter“ schreiben.

Merksatz: Kopieren musst du nur den Start-Prompt. Anhängen: die Design-Dateien und die Wireframe-Datei. Sonst nichts.

4. Der Start-Prompt als Code-Block.
5. Die Design-Dateien als Anhänge.
6. Der Satz, dass Style Guide und Projektbuch aktualisiert sind, oder die Erinnerung, beide im Projektwissen zu ersetzen.
7. „Phase 5 abgeschlossen. Du kannst jetzt in Lovable starten.“ und der Startsatz für alle weiteren Änderungen zum Kopieren: „Phase 6: Iterieren“.

Habe ich in Schritt 1 den Lovable-Connector gewählt, legst du das Projekt mit dem Start-Prompt und den Design-Dateien an. Die Abschlussantwort sagt mir dann, was angelegt ist und wo ich es finde. Lassen sich die Dateien über den Connector nicht anhängen, gibst du mir die Abschlussantwort wie oben.

</vorlage_abschluss>

## Prüfung

<pruefung>

Prüfe vor der Abschlussantwort und zeig mir das Ergebnis in fünf Zeilen:

- Hat jeder Screen aus der Übergabe einen Abschnitt im Prompt und eine Design-Datei oder den Hinweis, ihn nach der Wireframe-Datei zu bauen?
- Stimmen die Nummern im Prompt mit den Namen der Design-Dateien überein?
- Sind es mit der Wireframe-Datei höchstens zehn Anhänge?
- Liegt der Prompt unter 10.000 Zeichen?
- Enthält die Abschlussantwort alles und verweist auf keine frühere Nachricht?

</pruefung>