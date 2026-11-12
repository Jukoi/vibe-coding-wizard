
## Ziel

<ziel>

Schreibe ich „UX-Leitfaden erstellen“, baust du meinen „UX-LEITFADEN“: ein Artefakt mit den wichtigsten Regeln für gute Bedienbarkeit (User Experience, kurz UX). Ich bin Einsteiger. Ich nutze den Leitfaden, um meine Wireframes und meine App zu prüfen und bessere Prompts für Stitch und Lovable zu schreiben.

</ziel>

## Vorgehen

<vorgehen>

- Bau das Artefakt sofort, ohne Rückfragen.
- Antworte mit der Kopfzeile „UX-Leitfaden · Nachschlagen“.
- Übernimm nur die Inhalte unten. Erfinde keine weiteren Regeln, Zahlen oder Studien.
- Danach biete mir an: „Soll ich deine Wireframes oder einen Screen deiner App mit dem Selbstcheck prüfen?“ Liegen Übergaben im Projektwissen, nutz sie dafür.

</vorgehen>

## Sprache

<sprache>

- Schreib für Menschen ohne Design-Vorwissen: kurze Sätze, Alltagswörter, Du-Form.
- Erklär jeden Fachbegriff beim ersten Vorkommen in einem Halbsatz.
- Jedes Beispiel kommt aus Apps, die alle kennen: Online-Shop, Banking-App, Wetter-App, Messenger.
- Keine Fachliteratur, keine Formeln.

</sprache>

## Aufbau des Artefakts

<aufbau>

- Ein einziges HTML-Artefakt „UX-LEITFADEN“, gut lesbar auf Handy und Laptop, schlichtes, freundliches Design.
- Ganz oben „Das Wichtigste in 5 Punkten“.
- Darunter Sprunglinks zu den fünf Teilen.
- Pro Regel eine Karte mit:
  - Titel in einfachen Worten
  - einem Satz: was die Regel bedeutet
  - einem Satz: warum sie wichtig ist
  - einem Alltagsbeispiel, gern mit einer kleinen Skizze „so besser / so schlechter“
  - einer Zeile „So sagst du es im Prompt“ mit einem konkreten Satz für Stitch oder Lovable
- Teil 5 als Checkliste zum Abhaken.

</aufbau>

## Inhalte

<inhalte>

### Das Wichtigste in 5 Punkten

1. Jeder Screen hat ein klares Ziel und einen Hauptknopf.
2. Die App zeigt immer, was gerade passiert.
3. Man kann immer zurück oder abbrechen.
4. Die App spricht die Sprache der Nutzer.
5. Alles ist gut lesbar und gut zu treffen, auch mit dem Daumen.

### Teil 1: Die 10 Grundregeln für gute Bedienung (Usability-Heuristiken der Nielsen Norman Group)

1. Zeig, was passiert: z. B. ein Ladebalken beim Hochladen.
2. Sprich wie deine Nutzer: „Warenkorb“ statt „Bestellobjekt-Liste“.
3. Lass Nutzer zurück: Abbrechen, Zurück und Rückgängig sind immer möglich.
4. Bleib einheitlich: Gleiches sieht überall gleich aus und funktioniert gleich.
5. Verhindere Fehler: gute Voreinstellungen und eine Rückfrage vor dem Löschen.
6. Zeig Möglichkeiten, statt sie merken zu lassen: z. B. zuletzt gesuchte Begriffe.
7. Mach es Geübten leicht: Abkürzungen, ohne Neue zu überfordern.
8. Lass Unwichtiges weg: Je weniger auf dem Screen steht, desto mehr fällt das Wichtige auf.
9. Erklär Fehler verständlich: was passiert ist und wie man es behebt.
10. Hilf genau dort, wo es hakt: kurze Hinweise direkt am Feld.

### Teil 2: Wie Menschen Apps wahrnehmen (Laws of UX, Auswahl)

- Bekanntes funktioniert (Jakobs Gesetz): Nutzer erwarten, dass deine App so funktioniert wie Apps, die sie kennen.
- Weniger Auswahl, schnellere Entscheidung (Hicks Gesetz): Zu viele Optionen bremsen.
- Groß und nah ist leicht zu treffen (Fitts' Gesetz): Wichtige Knöpfe groß und gut erreichbar.
- Kleine Häppchen (Chunking): Lange Infos in kleine Gruppen teilen, z. B. eine Telefonnummer in Blöcken.
- Was nah beieinander steht, gehört zusammen (Gesetz der Nähe).
- Was in einem gemeinsamen Rahmen steht, gehört zusammen (Gesetz der gemeinsamen Region), z. B. eine Karte.
- Was heraussticht, wird gesehen (Von-Restorff-Effekt): Nur den Hauptknopf hervorheben.
- Das Ende zählt (Peak-End-Regel): Eine schöne Erfolgsmeldung prägt den Eindruck.
- Fortschritt motiviert (Ziel-Gradient-Effekt): z. B. „Schritt 2 von 3“.
- Schnell fühlt sich gut an (Doherty-Schwelle): Dauert etwas länger als etwa eine halbe Sekunde, zeig eine Ladeanzeige.
- Die App trägt die Arbeit (Teslers Gesetz): Was kompliziert ist, löst die App, nicht der Nutzer.
- Schön wirkt einfach (Ästhetik-Usability-Effekt): Ordentlich gestaltete Apps wirken leichter bedienbar.

### Teil 3: Regeln für jeden Screen

- Ein Screen, ein Ziel, ein Hauptknopf.
- Jeder Screen mit Daten braucht vier Zustände: lädt, leer, Fehler, Erfolg.
- Ein leerer Screen erklärt, was hier hinkommt, und bietet den ersten Schritt an.
- Formulare: so wenige Felder wie möglich, Beschriftung über dem Feld, Fehlermeldung direkt am Feld.
- Hauptmenü: höchstens fünf Punkte; der Punkt, auf dem man gerade ist, ist markiert.
- Knöpfe sagen, was passiert: „Eintrag speichern“ statt „OK“.
- Vor dem Löschen nachfragen oder „Rückgängig“ anbieten.

### Teil 4: Für alle bedienbar (Barrierefreiheit)

- WCAG ist das internationale Regelwerk für barrierefreie Websites und Apps.
- Knöpfe groß genug zum Tippen: Apple empfiehlt mindestens 44 × 44 Punkt, Google 48 × 48; WCAG verlangt mindestens 24 × 24 Pixel.
- Wichtige Knöpfe unten auf dem Screen, dort erreicht sie der Daumen.
- Kontrast, also der Helligkeitsunterschied zwischen Schrift und Hintergrund: mindestens 4,5 : 1, bei großer Schrift 3 : 1. Zum Prüfen gibt es kostenlose Kontrast-Checker.
- Informationen nie nur über Farbe zeigen, z. B. Fehler zusätzlich mit Text oder Symbol.
- Bilder bekommen einen Alt-Text, eine kurze Beschreibung für Menschen, die nicht sehen können.
- Alles muss auch mit der Tastatur bedienbar sein, und man sieht, wo man gerade ist.

### Teil 5: Selbstcheck für meine App

- Weiß ich auf jedem Screen sofort, wo ich bin und was ich tun kann?
- Gibt es pro Screen genau einen hervorgehobenen Hauptknopf?
- Komme ich auf dem wichtigsten Weg in wenigen Schritten ans Ziel?
- Kann ich überall zurück oder abbrechen?
- Sind lädt, leer, Fehler und Erfolg für jeden Screen mit Daten gestaltet?
- Verstehen Nutzer alle Texte und Knöpfe ohne Erklärung?
- Sind Knöpfe groß genug und gut mit dem Daumen erreichbar?
- Ist Text überall gut lesbar?
- Sieht Gleiches überall gleich aus?
- Würde jemand, der die App zum ersten Mal sieht, ohne Hilfe zurechtkommen?

</inhalte>