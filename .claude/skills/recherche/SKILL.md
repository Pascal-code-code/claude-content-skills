---
name: recherche
description: Recherchiert im Netz, was die Zielgruppe des Nutzers fragt, was in seiner Nische läuft und was neu ist, und schreibt daraus Themen-Kandidaten mit Quellen. Laden bei "/recherche", "recherchier für mich", "Themen finden", "was ist gerade aktuell in meiner Nische" und vor /content-plan.
---

# Recherche: Themen finden, die belegt sind

Du gehst für den Nutzer los und suchst im Netz. Am Ende liegt eine Datei mit Themen-Kandidaten da, jeder mit Quelle und Punktzahl. `/content-plan` baut daraus den Plan.

Dauer: ca. 10 bis 15 Minuten Maschinenzeit. Sag das dem Nutzer vor dem Start, damit er nicht denkt, es hänge.

## Schritt 1: Profil lesen

Lies `mein-content/profil.md`. Du brauchst daraus: Themen-Säulen, Zielgruppe (Situation, Problem, ihre Wörter), Belege des Nutzers, Meinungen, Grenzen, Ziel und CTA-Ziel.

Fehlt die Datei, schick den Nutzer zu `/interview`. Will er trotzdem sofort loslegen, stell drei Kurzfragen: Worüber machst du Videos? Wer soll zuschauen? Was soll danach passieren (Ziel)? Schreib dann in den Kopf der Recherche-Datei: "Profil: vorläufig, ohne /interview". Belege des Nutzers gibt es dann nicht, trag "unbekannt" ein.

## Schritt 2: Wie du suchst

Du hast WebSearch und WebFetch. Schick pro Säule mehrere Suchen gleichzeitig los, nicht eine nach der anderen.

Sei ehrlich, was nicht geht: Instagram und TikTok lassen sich ohne Login kaum durchsuchen, und Aufrufzahlen dort siehst du meist nicht. Nutze deshalb, was offen erreichbar ist:

- Google-Suche und die Fragen unter "Nutzer fragen auch"
- YouTube: Titel, Beschreibungen und Aufrufe sind sichtbar
- Reddit und Foren: echte Fragen der Zielgruppe, in ihren Worten
- Branchen-News, Blogs, Produkt-Changelogs
- Google Trends, falls die Seite lädt

Der Nutzer kann zusätzlich Links zu Accounts oder Videos oder Screenshots in den Chat legen. Frag ihn einmal am Anfang danach, warte aber nicht darauf. Was er schickt, wertest du mit aus.

## Schritt 3: Pro Säule vier Fragen

1. **Was fragt die Zielgruppe?** Sammle Fragen und Sätze wörtlich. Je näher an ihrer Sprache, desto besser der Hook später.
2. **Was ist neu?** Prüf bei jeder Meldung das Datum. Nur die letzten 30 Tage zählen als "aktuell". Älteres darfst du nennen, aber nicht so bezeichnen.
3. **Was läuft bei anderen?** YouTube-Titel und Hooks mit Aufrufen, wenn sichtbar. Notier Kanal und Datum, damit der Nutzer einen Ausreißer von einem Dauerbrenner unterscheiden kann.
4. **Welche Mythen und Gegenpositionen gibt es?** Wo behauptet jemand etwas, das der Nutzer mit eigenem Wissen oder Beleg geraderücken kann?

Danach bildest du Kandidaten. Ein Kandidat ist ein Thema, das in ein einzelnes Reel passt, kein ganzes Fachgebiet.

## Schritt 4: Bewerten

Gib jedem Kandidaten 1 bis 3 Punkte pro Frage (1 schwach, 2 ok, 3 stark):

| Frage | Quelle für die Antwort |
|---|---|
| Passt es zur Zielgruppe? | Profil, Fragen aus Schritt 3 |
| Hat der Nutzer einen eigenen Beleg oder kann etwas zeigen? | Belege in `profil.md` |
| Ist es aktuell oder zeitlos gefragt? | Datum, wiederkehrende Fragen |
| Führt es zum CTA-Ziel? | Ziel und CTA in `profil.md` |

Höchstens 12 Punkte. Kandidaten ohne Bezug zu Säulen, Zielgruppe oder Grenzen aus dem Profil wirfst du raus, auch wenn sie im Netz gerade laufen. Ziel: mindestens 10, höchstens etwa 20 Kandidaten in der Tabelle.

## Regeln, die nie brechen

- Jede Aussage hat einen Link. Ohne Link steht sie nicht in der Datei.
- Keine Zahl ohne Quelle.
- Fremde Ergebnisse sind nie die des Nutzers. Die Spalte "Beleg des Nutzers" füllst du nur aus `profil.md`. Gibt es keinen, schreib "fehlt".
- Lässt sich eine Quelle nicht laden, schreib das hin ("nicht ladbar") und nutz sie nicht als Beleg.
- Jede News trägt ihr Datum.
- Verkauf nichts aus deiner Erinnerung als aktuell. Was du nicht in dieser Sitzung gefunden hast, ist nicht aktuell.
- Halte dich an die Grenzen aus dem Profil (Themen, die der Nutzer nicht anfasst).

## Vorlage für die Datei

Speichere unter `mein-content/recherche/<JJJJ-MM-TT>.md` mit dem heutigen Datum. Gibt es die Datei schon, häng `-2` an, überschreib nichts.

```markdown
# Recherche vom <TT.MM.JJJJ>

- Profil-Stand: <Datum der profil.md, oder "vorläufig, ohne /interview">
- Säulen: <Säule 1, Säule 2, ...>
- Nicht ladbar: <Quellen, die nicht gingen, oder "keine">

## Was deine Zielgruppe fragt
- "<Frage oder Zitat in ihren Worten>" (<Säule>) [Quelle](<Link>)

## Was gerade neu ist
- <Fakt in einem Satz> (<TT.MM.JJJJ>) [Quelle](<Link>)

## Was bei anderen läuft
- "<Titel oder Hook>", <Kanal>, <Aufrufe, falls sichtbar>, <Datum> [Video](<Link>)

## Mythen und Gegenpositionen
- <Behauptung>: <was dagegen spricht> [Quelle](<Link>)

## Themen-Kandidaten

| Nr | Säule | Thema | Hook-Ansatz | Beleg des Nutzers | Quelle(n) | Punkte |
|---|---|---|---|---|---|---|
| 1 | <Säule> | <Thema> | <erster Satz oder Richtung> | <aus profil.md oder "fehlt"> | [1](<Link>), [2](<Link>) | <Summe> (<a>/<b>/<c>/<d>) |

Punkte: Zielgruppe / eigener Beleg / aktuell oder zeitlos / CTA-Ziel, je 1 bis 3.
```

Sortiere die Tabelle nach Punkten, höchste zuerst. Der Hook-Ansatz ist eine Richtung, noch kein fertiger Satz. Fertige Hooks entstehen in `/skript`.

## Abschluss im Chat

Zeig dem Nutzer die fünf stärksten Kandidaten: Nummer, Thema, Punkte, ein Satz warum. Sag, wo die Datei liegt. Nenn Lücken offen: Säulen mit wenig Funden, Quellen, die nicht luden, Kandidaten ohne eigenen Beleg.

Nächster Schritt: `/content-plan`.
