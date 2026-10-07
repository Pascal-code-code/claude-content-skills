---
name: edit
description: Bringt eine fertige Aufnahme zum geschnittenen Reel. Entweder schneidet Claude selbst (Versprecher und Pausen raus, optional Split-Screen mit Effekten, über den Claude Video Editor), oder der Nutzer schneidet in CapCut oder Premiere nach festen Schnitt-Regeln. Laden bei "/edit", "schneide mein Video", "Aufnahme ist fertig", "Rohschnitt", "wie schneide ich das", "Video kürzen".
---

# Edit: von der Aufnahme zum fertigen Reel

Der Nutzer hat ein Skript aus `/skript` gedreht. Jetzt soll daraus ein Reel werden, bei dem die Zuschauer bis zum Ende dranbleiben. Es gibt zwei Wege. Frag einmal, welcher es sein soll, und empfiehl Weg A, wenn der Nutzer einen Mac hat und nicht selbst schneiden will.

## Bevor du anfängst

1. Welches Skript gehört zur Aufnahme? Neueste Datei in `mein-content/skripte/` nehmen oder nachfragen. Das Skript ist die Messlatte: Jeder Satz daraus muss am Ende im Video sein.
2. Wo liegt die Aufnahme? Pfad erfragen. Die Originaldatei nie verändern oder löschen.
3. Regeln für den Schnitt stehen in `references/schnitt-und-auswertung.md`, Teil A. Lies sie, egal welcher Weg.

## Weg A: Claude schneidet (Claude Video Editor)

Das ist ein eigenes, kostenloses Repo von Pascal: github.com/Pascal-code-code/claude-video-editor. Es transkribiert die Aufnahme, nimmt pro Satz den besten Anlauf, schneidet Versprecher und Pausen raus und macht das Tempo etwas schneller. Wer will, bekommt danach den Split-Screen-Look mit Effekten (oben bearbeitet, unten Original).

Ehrlich vorab sagen:
- Läuft auf dem Mac. Windows ist nicht getestet.
- Einrichten dauert einmal 10 bis 20 Minuten, schneiden 30 bis 60 Minuten Maschinenzeit für 30 Sekunden Reel.
- Den **Rohschnitt** (Versprecher und Pausen raus) bekommt man mit jedem Skript. Die **Effekte** hängen an der Skript-Vorlage im Editor-Repo. Bei einem anderen Skript liefert der Editor den Rohschnitt, und die Effekte passt Claude dort im Gespräch an.

Ablauf:
1. Repo neben diesen Ordner holen. Mit git: `git clone https://github.com/Pascal-code-code/claude-video-editor.git` im Ordner über diesem Repo. Ohne git: auf GitHub "Code", "Download ZIP", entpacken.
2. Skript übergeben: die Skript-Datei aus `mein-content/skripte/` als `skript.md` in den Editor-Ordner kopieren. Nur den Sprechtext, Zeile für Zeile, ohne Tabelle.
3. Aufnahme (.mov oder .mp4) in den Ordner `input/` des Editors legen.
4. Dem Nutzer sagen: "Öffne jetzt den Ordner claude-video-editor in Claude Code (neues Fenster) und tipp einmal `/claude-video-editor setup`, danach `/claude-video-editor`." Ab da führt der Editor-Skill selbst durch.
5. Der Editor zeigt zuerst den Rohschnitt und wartet auf ein Okay. Dem Nutzer raten, dort genau zu prüfen: Ist jeder Satz aus dem Skript drin, und hängt nirgends ein halbes Wort?

## Weg B: selbst schneiden (CapCut, Premiere, egal welches Programm)

Gib dem Nutzer eine Schnittliste, mit der er in 15 bis 30 Minuten fertig ist:

1. **Bester Anlauf pro Satz.** Geh das Skript Satz für Satz durch. Ist ein Transkript da (Nutzer kann die Aufnahme in CapCut automatisch untertiteln lassen und den Text hier reinkopieren), markier pro Satz den letzten vollständigen Anlauf.
2. **Schnitte nur an Satzgrenzen.** Nie mitten im Satz, nie mitten im Wort. Ganze Sätze vor Kürze.
3. **Pausen kürzen.** Jede Pause über etwa 0,25 Sekunden auf etwa 0,15 Sekunden. Auch Pausen, die beim Sprechen bewusst waren, wirken im Video zu lang.
4. **Tempo 1,1x.** Ein kleines bisschen schneller klingt noch natürlich und hält die Leute länger.
5. **Jumpcuts kaschieren.** Bei jedem Schnitt im selben Bild leicht reinzoomen (etwa 5 %) oder wieder raus.
6. **Untertitel** oben oder mittig, 1 bis 3 Wörter auf einmal, Schlüsselwörter farbig. Nicht über das Gesicht.
7. **CTA früh einblenden** und bis zum letzten Bild stehen lassen. Das letzte Bild knapp 1 Sekunde halten.
8. **Ton:** Stimme etwa -14 LUFS (in CapCut reicht "Lautstärke normalisieren"), Soundeffekte leise und nur auf sichtbare Aktionen.

Liefere das als nummerierte Liste mit Zeitangaben aus dem Transkript, wenn eins da ist: "Satz 3: nimm 1:12 bis 1:16, nicht den Anlauf bei 0:58".

## Vor dem Posten prüfen

- [ ] Jeder Satz aus dem Skript ist drin, keiner doppelt.
- [ ] Kein Schnitt mitten im Wort. Einmal mit Ton und geschlossenen Augen anhören.
- [ ] Der erste Satz startet in der ersten halben Sekunde, ohne Stille davor.
- [ ] CTA ist sichtbar und steht auch in der Caption.
- [ ] Nichts liegt über dem Gesicht oder über zeigenden Händen.

## Danach

Status in `mein-content/plan.md` auf "gedreht" bzw. "gepostet" setzen. Nach 48 Stunden die Zahlen mit `/content-plan` auswerten, damit der nächste Plan besser wird.
