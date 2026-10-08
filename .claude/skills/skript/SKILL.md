---
name: skript
description: Schreibt Reel-, TikTok- und Shorts-Skripte im Ton des Nutzers, aus einer Zeile des Content-Plans oder zu einem freien Thema. Laden bei "/skript", "schreib das Skript für Zeile 3", "schreib mir ein Reel über X", "drei Hooks", "Test-Versionen", oder wenn ein Sprechtext, Hook, CTA oder eine Drehvorlage geschrieben oder überarbeitet wird.
---

# Skripte für Kurzvideos

Diese Regeln stammen aus vielen eigenen Reels, ihren Insights und fünf Methoden-Videos anderer Creator. Was davon gemessen ist und was nur Empfehlung, steht jeweils dabei.

## Bevor du schreibst

**Die wichtigste Regel: Jede Aussage über den Nutzer, seine Kunden oder seine Methode muss wörtlich aus `mein-content/profil.md` oder aus dem Chat stammen.** Verboten sind:
- Häufigkeiten, die niemand gezählt hat: "fast alle", "die meisten meiner Kunden", "das höre ich ständig am Telefon"
- erfundene Szenen und Details: Uhrzeiten, Anrufe, Küchenschränke, Gespräche, Zitate von Kunden
- erfundene Tipps oder Methoden: Die Lösung im Video kommt aus dem Abschnitt "Methode" im Profil. Steht dort nichts Passendes, schreib keine eigene Lösung, sondern frag den Nutzer: "Was rätst du deinen Kunden an dieser Stelle?"

Das gilt genauso für die Spalten Bild und Einblendung: auch dort keine Häufigkeiten oder Szenen, die nicht im Profil stehen.

Allgemeine Fakten aus der Recherche sind erlaubt, wenn die Quelle dabeisteht.

1. **`mein-content/profil.md` lesen:** Zielgruppe, ihre Wörter, Belege, Grenzen, CTA-Ziel. Fehlt das Profil, kurz auf `/interview` hinweisen und mit dem arbeiten, was der Nutzer im Chat sagt.
2. **`mein-content/stimme.md` lesen:** Jeder Satz im Skript klingt danach. Fehlt sie, einmal anbieten, sie mit `/interview` (Teil 2) aufzubauen, und bis dahin die Regeln in `.claude/skills/interview/references/stimme-aufbauen.md` unter "Gilt für jede Stimme" nutzen. (Bei globaler Installation liegen die Skills unter `~/.claude/skills/` statt `.claude/skills/`.)
3. **Plan-Zeile lesen:** Sagt der Nutzer "Zeile 3", ist die Zeile mit Nr 3 in `mein-content/plan.md` gemeint. Nimm Thema, Hook-Idee, Aufbau, Beleg und CTA von dort. Die Quellen findest du in der Recherche-Datei aus dem Plan-Kopf, beim Kandidaten mit der Nummer aus der Spalte Recherche-Nr.
4. **Für Hooks** zusätzlich `.claude/skills/skript/references/hook-check.md` lesen, **für den CTA** `.claude/skills/skript/references/cta-und-lead-magnet.md`.

## Speichern

Jedes Skript landet in `mein-content/skripte/<JJJJ-MM-TT>-<kurzer-titel>.md`. Kam es aus dem Plan, setz dort den Status der Zeile auf "Skript" und trag den Dateinamen in die Spalte Skript ein. Danach als nächsten Schritt nennen: drehen, dann `/edit`.

## Die fünf Grundregeln

1. **Ein Zuschauer, eine Situation, ein Gedanke.** Wer zwei Gedanken in ein Reel packt, verliert beide. Der zweite Gedanke ist das nächste Video.
2. **Jeder Satz fügt etwas hinzu.** Lies jeden Satz einzeln und frag: Was weiß der Zuschauer danach, was er vorher nicht wusste? Nichts? Streichen.
3. **Das Video löst seine eigene Frage.** Wer mit einer Frage einsteigt, beantwortet sie auch. Eine Antwort, die man nur per Kommentar oder im nächsten Teil bekommt, fühlt sich wie ein Trick an.
4. **Nur behaupten, was belegt ist.** Eigene Zahlen, eigene Erlebnisse, echte Screenshots. Ein Ziel ist kein Ergebnis. Eine Hoffnung ist keine Beobachtung. Keine erfundenen Geschichten, auch keine kleinen.
5. **Geschrieben zum Sprechen.** Kurze Sätze, konkrete Verben, Du-Form. Laut vorlesen. Wo du stolperst, ist der Satz falsch.

## Der Hook: die ersten zwei Sekunden

Ein Hook ist kein starker Satz. Er ist der Satz, der jemanden beim Scrollen anhält. Der stärkste Satz eines Videos ist fast nie der beste Einstieg, weil er meistens auf dem aufbaut, was davor kam. Ein fremder Zuschauer hat diesen Kontext nicht.

Ein guter Hook erfüllt vier Aufgaben gleichzeitig:

1. **Sofort verständlich.** Kein „es" oder „das" ohne Bezug, kein Konjunktiv, kein Satz, der mitten im Gedanken beginnt. Ausnahme: eine Frage, die ihren Bezug im selben Satz auflöst („Heißt das jetzt, dass man Texte nicht mehr mit KI schreiben sollte?").
2. **Benennt, was der Zuschauer glaubt oder will.** Seinen Wunsch, seinen Zweifel, seine Angst.
3. **Reißt eine Lücke auf.** Durch einen Widerspruch, eine Zahl oder etwas, das auf dem Spiel steht.
4. **Setzt das Thema.** Damit alles danach trägt.

**Was bei Pascals Reels gemessen besser lief:** Hooks, die einen Fehler oder ein Risiko ansprechen, das jeden in der Zielgruppe betrifft („du machst gerade einen Fehler"), hatten deutlich weniger Wischer als Nischen-Versprechen („dein eigener Video-Editor"). Bestes Reel: 40 % Skip-Rate, dreimal so viele Views wie üblich. Schwächste: 69 bis 77 % Skip-Rate.

**Ein Hook besteht aus drei Teilen,** die sich ergänzen und nicht wiederholen:

| Teil | Aufgabe | Beispiel |
|---|---|---|
| Bild | Daumen stoppen | Du hältst das Handy mit dem Beweis in die Kamera |
| Gesprochener Satz | Lücke öffnen | „Die großen KI-Anbieter spielen mit unserem Leben." |
| Texteinblendung | Für Leute ohne Ton | „Ex-Entwickler packt aus" |

Steht im Text dasselbe wie im Satz, verschenkst du einen der drei Plätze.

### Drei Hook-Methoden

**Triple Hook** (Methode eines anderen Creators, nicht von uns gemessen):
1. *Kontext:* Worum geht es? Sofort klar, über Satz, Bild und Text.
2. *Richtung:* Neugier in eine Richtung lenken: eine Zahl, ein Problem, ein Wunsch.
3. *Wendung:* Die Erwartung, die du gerade aufgebaut hast, umdrehen. Der Zuschauer erwartet A und bekommt einen Grund, B verstehen zu wollen.

Beispiel:
> Mein KI-Agent soll Kunden für mich finden.
> Seine erste Empfehlung klang richtig gut.
> Bis ich gefragt habe, warum er ausgerechnet die ausgewählt hat.

Ein beliebiges „aber" ist noch keine Wendung. Die Erwartung muss sich wirklich ändern.

**Desire Hook** (Methode eines anderen Creators): Mit dem Ergebnis anfangen, das der Zuschauer will, nicht mit einer Info. „3 Tipps zum Algorithmus" verliert gegen „So bin ich von 0 auf 1.000 Follower gekommen". Das Ergebnis an eine greifbare Person binden: dich, den Zuschauer oder einen Dritten.

**Die rhetorische Frage:** Stell genau die Frage, die der Zuschauer sich selbst stellt. Beantworte sie im nächsten Satz nur halb („Auch nicht ganz richtig.").

### Was einen Hook kaputt macht

- Begrüßung, Vorstellung, „In diesem Video zeige ich dir"
- Verweis auf etwas, das der Zuschauer nicht kennt („wie im letzten Call besprochen")
- Die Lösung schon im ersten Satz oder in der ersten Einblendung verraten
- Große Worte ohne Beleg („geheime Methode", „geleakt", „niemand redet darüber")

Findest du in einer Aufnahme keinen Satz, der alle vier Aufgaben schafft, verbieg nicht den nächstbesten. Sprich zwei Sätze neu ein oder setz eine Texttafel davor.

## Nach dem Hook: die Anschluss-Zone

Die zwei bis drei Sätze direkt nach dem Hook entscheiden, ob jemand bleibt. Hier nicht in Details, Branchenbeispiele oder ein Tutorial springen. Erst die persönliche Bedeutung weiterdrehen: Warum betrifft mich das? Was habe ich davon? Dann erst der Mechanismus.

## Spannung halten

Aus den Methoden-Videos, von uns als Werkzeug genutzt, nicht als bewiesenes Gesetz:

- **Etwas steht auf dem Spiel.** Eine Person, etwas persönlich Wichtiges, ein Zeitdruck. Es muss nicht dramatisch sein, nur echt.
- **Eine große offene Frage** trägt das ganze Video.
- **Mitten in die Geschichte einsteigen,** nicht am Anfang. Der erste Spannungsmoment kommt früh.
- **Mehrere kleine Höhepunkte statt einem großen.** Frage stellen, auflösen, neue Frage öffnen (Re-Hook). Nicht alles bis zur letzten Sekunde verstecken: einen ersten Teil der Antwort früh zeigen, den Rest am Ende.
- **Vor dem Reveal Spannung aufbauen:** erst Nutzen, dann Hinweise, dann die Lösung. Das trägt aber nur, wenn jeder Satz auf dem Weg etwas hinzufügt.

## Fünf Aufbauten, die funktionieren

Die Beispiele zeigen nur die Form. Ihren Inhalt (Gesetze, Zahlen, Zeiträume) nie übernehmen, der stammt aus Pascals Reels. Die Kurznamen in Klammern stehen so in der Spalte Aufbau von `mein-content/plan.md`.

**1. Frage → Kontext → Mechanik → Regel → eigene Praxis** (Frage→Praxis; erstes gepostetes Reel dieser Art)
> Heißt das jetzt, dass man Texte nicht mehr mit KI erstellen sollte? Auch nicht ganz richtig.
> Seit ein paar Wochen gilt der EU AI Act.
> Einige Anbieter bauen versteckte Muster in ihre Texte ein, an denen man erkennt, welche KI sie geschrieben hat.
> Plattformen erlauben KI-Inhalte, aber man muss sie kennzeichnen.
> Deshalb schreibe ich meine Captions selber und lasse mir nur von der KI helfen.

**2. Wunsch oder Beleg → Warum betrifft es mich → Mechanismus → eigener Bezug → Material → CTA** (Lead-Magnet; Details in `.claude/skills/skript/references/cta-und-lead-magnet.md`)

**3. Kontext → Richtung → Wendung → Auflösung mit Beleg** (Wendung; Triple Hook als ganzes Video, gut für Serien)

**4. Listicle (Liste):** Hook → Anschluss-Zone → stärkster Punkt zuerst → Re-Hook → weitere Punkte → CTA. Drei bis sechs Punkte. Bei jedem Punkt sagen, warum er dem Ziel aus dem Hook dient. Nicht jedes Thema ist ein Listicle; eine Entwicklung als „3 Hacks" zu verkaufen wirkt billig.

**5. Aufreger → Beleg zeigen → Übertragung auf den Zuschauer → eigene Praxis → CTA** (Aufreger)
> Die großen KI-Anbieter spielen mit unserem Leben.
> [echter Screenshot eines öffentlichen Posts]
> Wenn du so was liest und merkst, dass aus deinem „damit beschäftige ich mich später" langsam „davon hab ich keine Ahnung" wird, wirst du genau so zum Technik-Boomer wie deine Eltern, als WhatsApp rauskam.
> Ich beschäftige mich selbst erst seit ungefähr sechs Monaten damit und …
> Kommentier einfach AGENT, dann schick ich dir die Anleitung.

## Länge

- **Standard: ein Gedanke, etwa 15 Sekunden.** Ein 42-Sekunden-Reel hatte am Ende nur noch 10 % Zuschauer. 15 bis 16 Sekunden liefen deutlich besser.
- **Vollständigkeit schlägt Kürze.** Fehlt sonst die Auflösung, lieber 23 Sekunden. Länge ist verhandelbar, ein kaputter Einstieg nicht.
- **Lead-Magnet-Videos:** 30 bis 50 Sekunden als Startpunkt, weil der Spannungsbogen Platz braucht.
- Faustregel beim Schreiben: etwa 2,5 bis 3 gesprochene Wörter pro Sekunde. 15 Sekunden sind also 40 bis 45 Wörter.

## Der CTA

- **Genau eine Handlung.** Ein Keyword für ein genau benanntes Material. Nicht zusätzlich folgen, liken, teilen.
- **Das Ende sieht kaum jemand.** Bei Pascals Reels erreichten rund 15 % den Schluss. Den CTA deshalb zusätzlich früh einblenden (ab etwa Sekunde 3) und in die Caption schreiben.
- Im Imperativ, locker: „Kommentier einfach AGENT, dann schick ich dir die Anleitung komplett kostenlos."

## Ablauf für ein neues Skript

1. **Den echten Moment wählen:** Was hast du wirklich erlebt, gebaut, herausgefunden? Welchen Beleg kannst du zeigen?
2. **In je einem Satz notieren:** Kontext, Erwartung, Wendung. Beantwortet der Hauptteil die aufgeworfene Frage?
3. **Drei Hooks schreiben,** mit unterschiedlichem Motiv: direkter Nutzen, echter Widerspruch, persönliche Beobachtung. Mit `.claude/skills/skript/references/hook-check.md` prüfen.
4. **Hauptteil gemeinsam für alle drei.** Nur der Einstieg und ggf. der erste Übergang ändern sich.
5. **Pro Hook Bild und Einblendung mitplanen,** nicht erst im Schnitt.
6. **Laut vorlesen, Zeit stoppen, kürzen.** Dann gegen `mein-content/stimme.md` die Wortwahl prüfen.
7. **Alle drei Versionen drehen und posten.** Welche Hook besser läuft, entscheidet das Publikum, nicht dein Bauch. Die Zahlen trägst du mit `/content-plan` ein, Details zur Auswertung stehen in `.claude/skills/edit/references/schnitt-und-auswertung.md`.

## Ausgabeformat für Claude

Wenn du ein Skript schreibst, liefere es so:

```
## Version A: [Motiv des Hooks, z. B. "Fehler-Framing"]
Länge: ca. [x] s ([y] Wörter)

| # | Sprechtext | Bild | Einblendung |
|---|---|---|---|
| 1 | [Hook] | [was man sieht] | [kurzer Text, ergänzt den Satz] |
| 2 | ... | ... | ... |

Beleg, der gezeigt wird: [echter Screenshot/Demo/Zahl, oder "fehlt noch"]
Offene Frage aus dem Hook: [...] → aufgelöst in Zeile [n]
```

Bei mehreren Versionen: Hauptteil einmal ausschreiben, dann nur die abweichenden Zeilen pro Version. Stilfragen (Hook-Motiv, Einblendung ja oder nein) nicht zurückfragen, sondern bewusst über die Versionen verteilen.

## Checkliste vor dem Dreh

- [ ] Versteht ein Fremder den ersten Satz ohne Vorwissen?
- [ ] Ist der Gedanke konkret, nicht allgemein?
- [ ] Gibt es Neugier oder etwas, das auf dem Spiel steht?
- [ ] Ist jede Behauptung belegt oder als Ziel/Meinung markiert? Geh dafür Satz für Satz durch und nenn zu jeder Aussage über den Nutzer die Zeile im Profil. Findest du keine, streich den Satz oder frag nach. Erst dann abhaken.
- [ ] Löst das Video die Frage aus dem Hook?
- [ ] Genau ein CTA, früh eingeblendet und in der Caption?
- [ ] Unter 20 Sekunden, oder gibt es einen guten Grund für mehr?
- [ ] Laut vorgelesen, ohne zu stolpern?
