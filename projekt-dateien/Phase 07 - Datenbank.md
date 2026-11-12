## Ziel

<ziel>

In diesem Chat finden wir heraus, welche Daten meine App dauerhaft speichern muss, und bereiten die Datenbank mit Supabase in Lovable vor. Am Ende stehen:

1. „DATENMODELL – [App-Name]“: kurzes Markdown-Artefakt mit allen Datenbereichen, Tabellen, Feldern, Dateiablagen und Zugriffsregeln
2. „PROMPT – Daten [Kurzname] · Stufe [Nummer]“: fertige Prompts für Lovable, je Stufe einer
3. die Anleitung, wie ich Supabase in Lovable aktiviere und prüfe, ob alles ankommt

Ich will dabei lernen, wann eine App eine Datenbank braucht, welche Arten von Daten es gibt und wer welche Daten sehen darf.

</ziel>

## Kontext

<kontext>

Lies zuerst die Übergaben der vorherigen Phasen aus dem Projektwissen. Findest du sie dort nicht, such in den früheren Chats dieses Projekts:

- „STECKBRIEF – [App-Name]“ aus Phase 1: Persona, MVP-Features, Abschnitt „Daten“ (welche, woher, was sensibel), was die App bewusst nicht macht
- „ÜBERGABE WIREFRAMES – [App-Name]“ aus Phase 2: Screens und Notizspalten, besonders die Zeilen „Daten“ und „Zustände“
- „STYLE GUIDE – [App-Name]“ aus Phase 3, mit dem Abschnitt „Stand nach Design“: Tonalität für Meldungen
- „PROJEKTBUCH – [App-Name]“: was in Lovable schon umgesetzt ist (Phase 5 und 6)

Fasse mir danach in drei Zeilen zusammen, was meine App heute kann und wo heute Beispieldaten stehen, und zeig in derselben Antwort den Bestand aus Schritt 1. Ich bestätige beides gemeinsam.

Du siehst meine App in Lovable nicht. Frag mich deshalb nach dem Stand und bitte bei Bedarf um einen Screenshot aus der Lovable-Vorschau.

</kontext>

## Gesprächsführung

<gespraechsfuehrung>

Du führst mich wie ein Wizard durch diese Phase. Ich kenne mich mit Datenbanken nicht aus. Begriffe wie Tabelle, Feld, Storage, Login, Zugriffsregel (RLS) oder Edge Function erklärst du in einem Halbsatz mit einem Bild aus dem Alltag (z. B. Tabelle = Karteikasten, Feld = Spalte auf der Karteikarte, Storage = Ordner für Dateien).

Grundprinzip: Zeigen statt fragen. Zeig mir Datenbereiche und Tabellen als Karten oder Diagramm im Artefakt und lass mich auswählen oder reagieren.

Es gilt das Antwortformat der Projektanweisung. Kopfzeile in dieser Phase z. B. „Phase 7 · Datenbank · Schritt 3 von 8: Datenbereiche wählen“.

Zusätzlich in dieser Phase:

- Zeig nach jeder Änderung das aktualisierte Artefakt.
- So klein wie möglich: Speichere nur, was ein MVP-Feature wirklich braucht. Alles Weitere parkst du unter „Ideen für später“ und sagst mir kurz Bescheid.
- „Stand“ zeigt den Zwischenstand des Datenmodells.

</gespraechsfuehrung>

## Leitgedanke

<leitgedanke>

Eine App braucht eine Datenbank, sobald etwas nach dem Neuladen noch da sein soll, mehrere Menschen dieselben Daten sehen oder ich Inhalte ändern will, ohne Code anzufassen. Braucht meine App das nicht, ist „keine Datenbank“ ein gutes Ergebnis. Jede gespeicherte Information hat einen Grund, einen Besitzer und eine Regel, wer sie sehen darf.

</leitgedanke>

## Datenbereiche

<datenbereiche>

Nutze diese Bereiche als Landkarte. Prüfe jeden gegen meine App; nicht jede App braucht alle.

|Bereich|Was gespeichert wird|Supabase-Baustein|Beispiel|
|---|---|---|---|
|Inhalte der App|Texte, Listen, Einträge, die ich pflege|Tabelle|Projekte, Rezepte, Angebote|
|Bilder und Dateien|Fotos, Logos, PDFs, Uploads|Storage (Datei-Ablage) mit Bucket (Ordner)|Projektbilder, Profilfoto|
|Nutzerkonten|Anmeldung, Profil|Auth (Login) + Tabelle „profiles“|Name, Rolle|
|Daten der Nutzer|was Nutzer selbst eingeben|Tabelle mit Besitzer-Feld|Einträge im Haushaltsbuch|
|Anfragen und Formulare|Kontakt, Bestellung, Anmeldung|Tabelle, ggf. Mail per Edge Function|CV-Anfrage, Terminwunsch|
|Nutzung|was Besucher tun|Tabelle „events“ oder Analytics-Tool|Seitenaufrufe, Klicks auf Buttons|
|Einstellungen|Vorlieben je Nutzer oder App|Tabelle|Sprache, Benachrichtigungen|
|KI-Ergebnisse (für Phase 8)|Fragen und Antworten der KI|Tabelle|gespeicherte Zusammenfassungen|

</datenbereiche>

## Schritte

<schritte>

1. Bestand: Zeig mir im Artefakt meine Screens als Liste. Markiere je Screen, welche Daten dort angezeigt, eingegeben oder geändert werden, und ob sie heute fest im Code oder als Beispieldaten stehen. Frag, ob das zum Stand in Lovable passt.
2. Brauche ich eine Datenbank? Prüfe mit mir drei Fragen: Soll etwas nach dem Neuladen bleiben? Geben Nutzer etwas ein, das ich später sehen will? Will ich Inhalte ändern, ohne Lovable zu prompten? Zeig mir das Ergebnis als Ampel. Ist alles rot, empfiehl mir, ohne Datenbank weiterzumachen; die Entscheidung treffe ich.
3. Datenbereiche wählen: Zeig mir die Bereiche aus der Landkarte als Karten, vorausgewählt nach meinem Steckbrief und meinen Screens. Pro Karte: Bereich, betroffene Screens, ein Satz Nutzen, Beispiel mit echten Inhalten meiner App, Empfehlung „MVP“ oder „später“. Frag mich zusätzlich, ob ich einen eigenen Grund für eine Datenbank habe. Ich wähle aus.
4. Tabellen und Felder: Leite je gewähltem Bereich die Tabellen ab. Zeig sie als Karteikarten im Artefakt: Tabellenname, Felder mit Beispielwert und Art (Text, Zahl, Datum, Ja/Nein, Bild-Link, Verweis auf andere Tabelle), Pflichtfelder markiert. Zeig dazu ein einfaches Diagramm, wie die Tabellen zusammenhängen (z. B. ein Projekt hat viele Bilder). Höchstens fünf Tabellen im MVP.
5. Bilder und Dateien: Lege mit mir fest, welche Dateien in den Storage gehören, in welchen Bucket (Ordner), wer hochladen darf und ob sie öffentlich sichtbar sind. Grenzen: Dateitypen und maximale Größe.
6. Zugriff und Datenschutz: Zeig mir eine Matrix „Wer darf was?“ je Tabelle und Bucket: Besucher ohne Login, angemeldete Nutzer (nur eigene Daten), ich als Admin. Je Zelle: sehen, anlegen, ändern, löschen. Markiere personenbezogene und sensible Felder und frag, ob ich sie wirklich speichern will. Weise auf Datenschutzerklärung und Löschfristen hin.
7. Pflege und Nutzung: Lege mit mir fest, wie Inhalte reinkommen (ich trage im Supabase-Dashboard ein, Formular in der App, kleiner Admin-Bereich mit Login) und ob ich Nutzung messen will. Für reine Besucherzahlen empfiehl ein Analytics-Tool statt eigener Tabelle; eigene Tabelle nur für gezielte Ereignisse (z. B. Klick auf „Termin buchen“).
8. Prompts für Lovable: Teile den Einbau in Stufen, jede Stufe ein eigener Prompt nach der Vorlage unten:
    1. Supabase aktivieren, Tabellen und Buckets anlegen, Zugriffsregeln setzen
    2. Erste Screens lesen ihre Inhalte aus der Datenbank statt aus Beispieldaten
    3. Formulare und Uploads speichern in die Datenbank bzw. den Storage
    4. Optional: Login und Admin-Bereich
    5. Optional: Nutzung messen

    Zeig mir die Stufen als Liste und frag, ob Reihenfolge und Umfang passen.

</schritte>

## Regeln für Datenbank und Sicherheit

<sicherheit>

- Nutze Supabase über Lovable Cloud oder die Supabase-Verbindung in Lovable, je nachdem, was mein Dozent vorgibt.
- Zugriffsregeln (Row Level Security, also Regeln je Zeile, wer sie sehen darf) sind auf jeder Tabelle aktiv. Akzeptanzkriterium in jeder Stufe: Besucher sehen nur öffentliche Inhalte, Nutzer nur ihre eigenen Daten.
- Geheime Schlüssel (Service-Role-Key, Mail-Dienst, API-Keys) gehören in die Secrets von Lovable und nie in den Frontend-Code oder einen Chat.
- Personenbezogene Daten nur speichern, wenn ein Feature sie braucht. Sensible Daten (Gesundheit, Finanzen) mit Beispieldaten testen.
- Formulare prüfen Eingaben vor dem Speichern (Pflichtfelder, gültige E-Mail, Länge) und zeigen verständliche Fehlermeldungen.
- Gespeicherte Daten bleiben nach dem Neuladen erhalten; das ist in jeder Stufe ein Akzeptanzkriterium.
- Empfiehl für Stufe 1 und für Login den Plan-Modus in Lovable.
- Erinnere mich vor größeren Änderungen an der Datenbank, in Lovable eine Version als Lesezeichen zu sichern.

</sicherheit>

## So aktivierst du Supabase in Lovable

<anleitung_supabase>

Gib mir vor Stufe 1 genau diese Anleitung:

1. Projekt in Lovable öffnen und eine Version als Lesezeichen sichern.
2. Prompt für Stufe 1 im Plan-Modus senden. Lovable schlägt vor, die Datenbank (Cloud bzw. Supabase) zu aktivieren; Plan prüfen und freigeben.
3. Falls Lovable nicht fragt: in den Projekt-Einstellungen den Bereich „Cloud“ bzw. „Integrations → Supabase“ öffnen und verbinden.
4. Nach der Umsetzung in der Datenbank-Ansicht von Lovable bzw. im Supabase-Dashboard prüfen: Sind alle Tabellen und Buckets da?
5. Einen Testeintrag anlegen, App neu laden, prüfen, ob er angezeigt wird.
6. Als Besucher ohne Login testen (privates Browserfenster): Sehe ich nur, was öffentlich sein soll?

</anleitung_supabase>

## Prompt-Vorlage

<prompt_vorlage>

Jeder Prompt „PROMPT – Daten [Kurzname] · Stufe [Nummer]“ steht als Code-Block im Chat und hat genau diesen Aufbau. Abweichend von der Projektanweisung legst du dafür kein Artefakt an. Abschnitte ohne Inhalt lässt du weg.

```markdown
## User Story
Als [Rolle] möchte ich [Funktion], damit [Nutzen].

## Kontext
- Betroffene Bereiche: [Screen-Nummern und Namen]
- Heutiger Stand: [z. B. Inhalte stehen als Beispieldaten im Code]
- Stufe: [1 Struktur · 2 Lesen · 3 Speichern · 4 Login/Admin · 5 Nutzung]

## Datenmodell (nur die Teile dieser Stufe)
- Tabelle [name]: [Feld] ([Art], Pflicht ja/nein), …
- Verknüpfung: [z. B. ein Projekt hat viele Bilder]
- Storage-Bucket [name]: [Dateitypen], max. [Größe], öffentlich ja/nein

## Zugriffsregeln
- Besucher: [sehen …]
- Angemeldete Nutzer: [nur eigene Daten …]
- Admin: [alles]

## Verhalten
- [Screen] lädt [Daten] aus [Tabelle]
- [Formular] speichert [Felder] in [Tabelle]

## Akzeptanzkriterien
- [ ] Wenn …, dann …
- [ ] Wenn ich die Seite neu lade, dann sind gespeicherte Daten noch da.
- [ ] Wenn ich ohne Login darauf zugreife, dann sehe ich nur öffentliche Inhalte.
- [ ] Wenn Daten laden, dann erscheint [Ladezustand]; wenn keine da sind, [leerer Zustand]; bei Fehler „[Fehlertext]“.

## Gestaltung
- Bestehender Stil der App; Meldungen in der Tonalität aus dem Style Guide

## Nicht verändern
- Navigation, Layout, Styling, Texte der Screens, die diese Stufe nicht betrifft

## Hinweise für Lovable
- Setze nur diese Stufe um.
- Stell mir vorher alle Fragen, die du brauchst.
- Aktiviere Row Level Security auf jeder neuen Tabelle.
- Prüfe nach der Umsetzung jedes Akzeptanzkriterium in der Vorschau.
- Merke dir: [dauerhafte Datenregel, z. B. „Projektbilder liegen im Bucket project-images“]
```

</prompt_vorlage>

## Prüfung

<pruefung>

Prüfe vor dem Abschluss und zeig mir das Ergebnis in sechs Zeilen:

- Hat jede Tabelle und jeder Bucket ein MVP-Feature, das ihn braucht?
- Ist jedes Feld mit Daten aus den Wireframe-Notizen abgedeckt, und gibt es keine überflüssigen Felder?
- Ist für jede Tabelle und jeden Bucket geregelt, wer sehen, anlegen, ändern und löschen darf?
- Sind personenbezogene und sensible Daten markiert und begründet?
- Sind lädt, leer, Fehler und Erfolg für Screens mit Daten definiert?
- Liegen alle geheimen Schlüssel nur in den Secrets?

</pruefung>

## Ergebnis

<ergebnis>

Erstelle zum Abschluss ein Markdown-Artefakt „DATENMODELL – [App-Name]“ mit höchstens 2.000 Zeichen und genau diesen Abschnitten:

1. Warum die App eine Datenbank braucht (ein, zwei Sätze)
2. Datenbereiche: gewählt für MVP, geparkt für später
3. Tabellen mit Feldern und Verknüpfungen
4. Storage: Buckets, Dateitypen, Sichtbarkeit
5. Zugriffsregeln als kurze Matrix
6. Pflege und Nutzung: wie Inhalte reinkommen, was gemessen wird
7. Datenschutz: welche personenbezogenen Daten, wozu
8. Ideen für später

Dazu die Prompts „PROMPT – Daten [Kurzname] · Stufe 1–n“ und die Anleitung „So aktivierst du Supabase in Lovable“.

Speichere das Datenmodell selbst im Projektwissen dieses Projekts, wenn du das kannst, und sag mir in einem Satz, dass ich nichts hochladen muss. Kannst du es nicht, erinnere mich, es hochzuladen. Aktualisiere danach das Projektbuch.

Gib mir danach die Abschlussantwort nach der Projektanweisung. Sie enthält alle Prompts noch einmal als Code-Blöcke, in der Reihenfolge der Stufen, und die Anleitung „So aktivierst du Supabase in Lovable“. Startsatz der nächsten Phase: „Phase 8: KI-Funktion“. Für Korrekturen nach dem Einbau: „Phase 6: Iterieren“.

</ergebnis>