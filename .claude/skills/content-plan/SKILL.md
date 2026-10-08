---
name: content-plan
description: Erstellt aus Profil und Recherche einen Content-Plan für Reels (welches Video an welchem Tag, mit Hook-Idee, Aufbau, Beleg und CTA) und wertet danach die Zahlen aus. Laden bei "/content-plan", "erstell mir einen Plan", "Redaktionsplan", "was poste ich nächste Woche", "Plan anpassen" oder "Zahlen auswerten".
---

# Content-Plan: was du wann postest

Dieser Skill macht aus deinem Profil und der Recherche einen Plan, den du in der Zeit schaffst, die du hast. Danach hilft er dir, die Zahlen zu lesen und den Plan anzupassen. Er schreibt `mein-content/plan.md`.

## Voraussetzungen prüfen

1. **`mein-content/profil.md` lesen.** Fehlt die Datei, sag: "Dir fehlt noch das Profil. Starte mit `/interview`." Dann stopp.
2. **Neueste Datei in `mein-content/recherche/` lesen.** Fehlt sie oder ist sie älter als etwa 14 Tage, schlag `/recherche` vor, aber blockier nicht. Ohne frische Recherche plan mit zeitlosen Themen aus dem Profil und sag das offen.
3. **`mein-content/stimme.md` lesen,** falls sie da ist. Sie prägt nur die Hook-Ideen, nicht die Struktur.
4. **`mein-content/plan.md` lesen,** falls sie da ist. Schreib den Plan fort und überschreib nichts: erledigte Zeilen (Status gedreht oder gepostet) bleiben samt Ergebnis stehen, neue Zeilen kommen darunter.

## Zwei kurze Fragen

Frag nur, was nicht im Profil steht. Stell beide Fragen in einer Nachricht.

- **Zeitraum?** Standard: 2 Wochen.
- **Wie viele Videos pro Woche?** Nimm die Zeit pro Woche aus dem Profil und rechne ehrlich: Ein Reel braucht von Skript bis Schnitt oft 2 bis 3 Stunden, wenn du es zum ersten Mal machst. Rechne: Stunden pro Woche geteilt durch 2,5 ergibt die Videos pro Woche, abgerundet. Will der Nutzer mehr, sag ihm die Rechnung und frag, ob er wirklich so viel Zeit hat. Plane erst nach seiner Antwort, nie einfach mehr mit einem Hinweis daneben.

## Planungsregeln

1. **Säulen abwechseln.** Nie zweimal dieselbe Säule hintereinander.
2. **Aktuell und zeitlos mischen.** Aktuelle Themen kommen aus der Recherche und bekommen ein Datum, bis wann sie noch zünden. Zeitlose Themen füllen den Rest.
3. **Pro Woche mindestens ein Video mit eigenem Beleg.** Etwas, das du zeigen kannst und das in `profil.md` steht: dein Ergebnis, dein Screenshot, deine Erfahrung. Steht dort nichts Zeigbares, sag es und frag, was du zeigen könntest.
4. **Jedes Video hat genau einen CTA.** Er kommt aus dem CTA-Ziel im Profil. Einen Keyword-Kommentar ("Kommentier ANLEITUNG") plane nur, wenn es das Material dafür wirklich gibt.
5. **Drehtage bündeln.** Wenn deine Drehbedingungen es hergeben, dreh drei bis fünf Videos an einem Tag. Gleiche Kleidung, gleicher Ort, gleiches Licht.
6. **Test-Versionen: eine Variable pro Version.** Zum Beispiel nur der Hook. Alles andere bleibt gleich, sonst weißt du später nicht, was gewirkt hat.
7. **Drei Hook-Ideen pro Video sind erlaubt.** Markier die beste mit einem Stern.
8. **Nichts erfinden, auch nicht in Hook-Ideen.** Keine Zahlen, Kunden, Ergebnisse, Häufigkeiten ("fast alle sagen"), Szenen oder Methoden, die nicht im Profil stehen. Eine Hook-Idee darf nur versprechen, was die Methode im Profil auch einlöst. Ein Ziel ist kein Ergebnis.

## Vorlage für mein-content/plan.md

Leg die Datei in genau diesem Format an:

````markdown
# Content-Plan

Stand: JJJJ-MM-TT
Zeitraum: JJJJ-MM-TT bis JJJJ-MM-TT
Rhythmus: X Videos pro Woche auf [Plattformen]
Quelle: mein-content/recherche/JJJJ-MM-TT.md

| Nr | Datum | Säule | Thema | Recherche-Nr | Hook-Idee | Aufbau | Beleg / was du zeigst | CTA | Status | Skript | Ergebnis |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Mo 12.10. | Säule A | Thema in einem Satz | 4 | * "Hook A" / "Hook B" / "Hook C" | Frage→Praxis | Dein Screenshot, deine Zahl | Kommentier ANLEITUNG | geplant | | |
| 2 | Do 15.10. | Säule B | ... | 7 | ... | Liste | ... | ... | geplant | | |

Status: geplant / Skript / gedreht / gepostet
Recherche-Nr: Nummer des Kandidaten in der Recherche-Datei (leer bei Themen ohne Recherche). Skript: Dateiname in `mein-content/skripte/`, trägt `/skript` ein.

## Drehtage

- Sa 10.10.: Zeilen 1, 2, 3 (Ort, Kleidung, was du mitbringst)

## Ideen-Speicher

- Kandidat aus der Recherche, der nicht reingepasst hat (Säule, warum nicht jetzt)

## Regeln aus den Zahlen

(Bleibt leer, bis du ausgewertet hast. Siehe "Auswerten und anpassen".)
````

Für die Spalte Aufbau gibt es fünf Kurznamen, dieselben wie im Skill skript (Abschnitt "Fünf Aufbauten, die funktionieren"): Frage→Praxis, Lead-Magnet, Wendung, Liste, Aufreger. Wähl pro Video den, der zum Thema passt, und wechsle ab.

## Übergabe an /skript

Jede Zeile mit Status "geplant" kannst du an `/skript` geben: "Schreib das Skript für Zeile 3." Zeile 3 heißt: die Zeile mit Nr 3. `/skript` setzt den Status dann auf "Skript". Ändere den Status danach selbst auf "gedreht" und "gepostet", oder sag Claude Bescheid, er trägt es ein.

## Auswerten und anpassen (ca. 10 Minuten)

Mach das 48 Stunden nach dem Posten eines Videos oder einmal pro Woche für alle Videos auf einmal.

1. **Frag nach den Zahlen** aus den Insights, pro Video: Aufrufe, durchschnittliche Wiedergabedauer, Skip-Rate (Wischrate in den ersten 3 Sekunden), Saves, Shares, Kommentare mit Keyword, neue Follower. Fehlt eine Zahl, trag sie nicht ein und rate nicht.
2. **Trag die Zahlen in die Spalte Ergebnis ein,** in einer Zeile, zum Beispiel: "1.800 Aufrufe, Skip 52 %, 9 Saves, 4 Keyword". Setz den Status auf "gepostet".
3. **Leite Regeln ab:** Welche Säule läuft? Welcher Hook-Typ hält Leute länger? Welche Länge? Schreib sie unter "Regeln aus den Zahlen".
4. **Pass die nächsten Zeilen an.** Mehr von dem, was läuft, weniger von dem, was nicht läuft. Sag dazu, was du geändert hast und warum.

Die Skip-Rate zählt am meisten, weil sie über die Reichweite entscheidet. Zu Skip-Rate, Saves und dem Testen von Versionen steht Genaueres in Teil B von `.claude/skills/edit/references/schnitt-und-auswertung.md`. (Bei globaler Installation liegen die Skills unter `~/.claude/skills/` statt `.claude/skills/`.) Lies dort nach, bevor du eine Regel ableitest.

**Ehrlich bleiben:** Ein einzelnes Video ist kein Muster. Es kann am Thema, am Tag oder am Zufall liegen. Zieh erst Schlüsse, wenn du etwa 3 Videos derselben Art hast (gleiche Säule, gleicher Hook-Typ). Bis dahin schreib "Hinweis" statt "Regel". Ein organischer Post ohne festen Traffic ist kein sauberer Test, die Zahlen sind Indizien, kein Beweis.

## Feste Regeln

- Nichts erfinden: keine Ergebnisse, Zahlen, Kunden, Zitate.
- Ein Ziel ist kein Ergebnis. Schreib "Ziel: 1.000 Follower" nie in die Spalte Ergebnis.
- Der Plan passt zur Zeit, die du wirklich hast. Lieber zwei Videos pro Woche, die du schaffst, als vier, die du nach einer Woche aufgibst.
- Pro Video genau ein CTA.
- Schreib in Du-Form, kurz, ohne Fachwörter, wo ein Alltagswort reicht.

## Abschluss

1. Zeig den Plan als Tabelle im Chat (Nr, Datum, Säule, Thema, Hook-Idee, CTA, Status).
2. Sag in einem Satz, was du bewusst weggelassen hast und warum (zum Beispiel ein Thema im Ideen-Speicher).
3. Nenn den nächsten Schritt: "Als Nächstes: `/skript` für Zeile 1."
