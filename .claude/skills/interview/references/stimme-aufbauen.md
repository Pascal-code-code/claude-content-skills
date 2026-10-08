# Eigene Stimme

> **Für Claude:** Du führst die Schritte unten zusammen mit dem Nutzer aus. Die Ergebnisse schreibst du nach `mein-content/stimme.md` (Abschnitte wie in der Vorlage unten), nicht in diese Datei. Die Beispiele aus Pascals Stimme dienen nur zur Orientierung, übernimm sie nie in die Stimme des Nutzers.

## Warum das wichtig ist

Leser merken KI-Text sofort. Gleiche Satzlänge, gleiche Übergänge, gleiche Wörter wie tausend andere Accounts. Das Ziel hier ist das Gegenteil: ein Text soll klingen, als hättest du ihn selbst gesagt. Nicht "professionell", nicht "glatt". So wie du wirklich redest, nur ohne Verhaspler.

Dieser Skill ist eine Vorlage. Er zeigt dir, wie so ein Stimm-Skill aufgebaut ist, mit Beispielen aus Pascals eigenem Skill. Deine Aufgabe: einmal ~60 Minuten investieren, deine eigene Stimme analysieren lassen und den Abschnitt "Vorlage" unten mit deinen eigenen Ergebnissen füllen.

## Stimme einmalig aufbauen (~60 Minuten)

### Schritt 1: Sprachaufnahmen sammeln (~15 Min)

Du brauchst 5 bis 10 Aufnahmen von dir selbst, frei gesprochen, nicht abgelesen. Zum Beispiel:

- Sprachnachrichten, die du Freunden oder Kunden geschickt hast
- Ausschnitte aus Livestreams oder Calls
- Alte Reel- oder Video-Rohaufnahmen, auch die, die du nie gepostet hast
- Eine Sprachmemo, in der du dir selbst 5 Minuten lang etwas erklärst, das du gut kennst

Wichtig: frei gesprochen. Ein abgelesenes Skript zeigt dir nicht deine Stimme, nur deine Schreibe. Ziel sind zusammen mindestens 3.000 Wörter Rohmaterial. Das klingt nach viel, ist aber ungefähr 20 bis 30 Minuten gesprochener Sprache.

### Schritt 2: Transkribieren (~15 Min)

Jede Aufnahme in Text umwandeln. Ein paar Optionen:

- ElevenLabs Scribe oder ein anderer Transkriptions-Dienst
- WhisperX oder ein anderes lokales Whisper-Modell
- Notizen-Apps mit eingebauter Diktier-Funktion (schlechter, aber besser als nichts)

Alle Transkripte in eine Datei packen, zum Beispiel `stimme-korpus.md`. Am Ende hast du deinen persönlichen Korpus.

Achtung, Falle: Transkriptions-Tools erkennen Marken- und Produktnamen oft falsch ("Cloud" statt "Claude", "ChatGBT" statt "ChatGPT"). Das sind Hör-Fehler der Maschine, nicht deine Wortwahl. Beim Analysieren im nächsten Schritt korrigierst du diese Namen, aber übernimmst nie den falsch erkannten Begriff als "typisches Wort".

### Schritt 3: Claude den Korpus analysieren lassen (~20 Min)

Öffne Claude (Code oder Chat) mit deinem Korpus und gib genau diesen Prompt:

```
Hier ist ein Korpus mit Transkripten von mir selbst, frei gesprochen
(Sprachnachrichten/Calls/Videos). Analysiere meine Sprechweise und
gib mir folgendes zurück, jeweils mit Original-Zitaten aus dem
Korpus als Beleg:

1. Kurzprofil: wer ich bin, was ich mache, wie ich meine Zielgruppe
   anspreche (du/ihr/Sie).

2. 5-7 Ton-Prinzipien: wiederkehrende Denk- und Argumentationsmuster
   in meiner Sprache. Jedes Prinzip mit einem Original-Zitat belegen.

3. Typischer Wortschatz: Verbindungswörter, Füllwörter, Anglizismen,
   Lieblingsformulierungen, die ich auffällig oft benutze. Mit
   Häufigkeit oder Beispielsatz.

4. Verbotsliste: Wörter/Formulierungen, die NICHT nach mir klingen
   (zu formell, zu glatt, zu sehr nach KI), damit ich sie beim
   Schreiben vermeiden kann.

5. Register-Tabelle: wie sich mein Ton für Reel-Skript, Caption,
   E-Mail und Anleitung jeweils unterscheidet, was gleich bleibt
   und was sich ändert.

6. 3 Beispiel-Transformationen: ein generischer KI-Text (❌) und
   wie ich das selbst sagen würde (✅), pro Format eine.

7. Eine Abgabe-Checkliste mit 6-8 Punkten, mit der ich jeden
   fertigen Text vor Abgabe gegen meine eigene Stimme prüfe.

Wichtig: Wenn im Korpus Markennamen oder Produktnamen falsch
transkribiert wurden (z. B. Hör-Fehler des Transkriptions-Tools),
übernimm die korrekte Schreibweise, nicht den Fehler.
```

Claude gibt dir daraufhin die sieben Bausteine zurück, mit Belegen aus deinem eigenen Korpus. Das ist die Grundlage für den nächsten Schritt.

### Schritt 4: Vorlage füllen (~10 Min)

Trag die Ergebnisse aus Schritt 3 in den Abschnitt "Vorlage" unten ein. Ersetze jeden Platzhalter. Lösch die Hinweise in Klammern, wenn der Abschnitt fertig ist. Fertig ist dieser Skill, wenn kein Platzhalter mehr drinsteht.

Von jetzt an: diesen Skill laden, bevor du einen Text in deiner Stimme schreibst oder überarbeitest.

---

## Vorlage

### Kurzprofil

*(Wer bist du, was machst du, wen sprichst du an, duzt oder siezt du. 2-3 Sätze. Kommt direkt aus Schritt 3, Punkt 1.)*

[Platzhalter: Name, Rolle, Zielgruppe, Anrede]

### Ton-Prinzipien

*(5-7 wiederkehrende Denkmuster, jedes mit einem Original-Zitat aus deinem Korpus belegt. Kommt aus Schritt 3, Punkt 2.)*

Beispiel aus Pascals Skill, zur Orientierung, nicht zum Kopieren:

> **Eigene Erfahrung ist das Argument.** Pascal behauptet nicht, er berichtet. „Ich habe es aber auch in den letzten zwei Wochen sehr viel damit umprobiert und musste so ein bisschen meinen Weg finden." Jede Empfehlung hängt an einem Ich-Erlebnis.

> **Konkrete Zahlen statt Adjektive.** „um die 450 E-Mails am Tag", „es müssten jetzt im Schnitt 15 sein". Wo eine Zahl möglich ist, steht eine Zahl.

> **Ehrliches Hedging statt Allwissenheit.** „Ich bin mir nicht sicher, wie es mit Copilot ist, aber eigentlich müsste es auch funktionieren." Eine Wissenslücke wird benannt, nicht überspielt.

1. [Platzhalter: Prinzip 1 + Zitat]
2. [Platzhalter: Prinzip 2 + Zitat]
3. [Platzhalter: Prinzip 3 + Zitat]
4. [Platzhalter: Prinzip 4 + Zitat]
5. [Platzhalter: Prinzip 5 + Zitat]

### Wortschatz

#### Typisch (verwenden, aber dosiert)

*(Verbindungswörter, Füllwörter, Anglizismen, Lieblingsformulierungen aus Schritt 3, Punkt 3. In Schrift sparsamer einsetzen als im gesprochenen Original.)*

[Platzhalter: Liste deiner typischen Wörter und Wendungen]

#### Verbotsliste (klingt nicht nach dir)

*(Wörter, die zu formell, zu glatt oder zu sehr nach KI klingen, aus Schritt 3, Punkt 4.)*

[Platzhalter: deine eigene Verbotsliste, zusätzlich zur festen Liste unten unter "Gilt für jede Stimme"]

### Register-Tabelle

*(Wie sich dein Ton je nach Format ändert, aus Schritt 3, Punkt 5.)*

| Format | Anrede | Was bleibt | Was sich ändert |
|---|---|---|---|
| **Reel-Skript** | [Platzhalter] | [Platzhalter] | [Platzhalter] |
| **Caption** | [Platzhalter] | [Platzhalter] | [Platzhalter] |
| **E-Mail** | [Platzhalter] | [Platzhalter] | [Platzhalter] |
| **Anleitung** | [Platzhalter] | [Platzhalter] | [Platzhalter] |

### Beispiel-Transformationen

*(Ein generischer Satz und daneben, wie du das selbst sagen würdest. Mindestens 3, aus Schritt 3, Punkt 6.)*

Beispiel aus Pascals Skill, zur Orientierung:

> ❌ „Wusstest du, dass künstliche Intelligenz dein Video-Editing komplett automatisieren kann? Hier sind 3 Tipps!"
>
> ✅ „Wenn du jeden Tag den coolsten KI-Tools hinterherjagst und immer noch keinen Cent damit verdient hast, dann ist dieses Video genau richtig für dich."

**[Format 1, z. B. Caption]**
> ❌ [Platzhalter: generischer Satz]
>
> ✅ [Platzhalter: dein Satz]

**[Format 2, z. B. E-Mail]**
> ❌ [Platzhalter: generischer Satz]
>
> ✅ [Platzhalter: dein Satz]

**[Format 3, z. B. Reel-Hook]**
> ❌ [Platzhalter: generischer Satz]
>
> ✅ [Platzhalter: dein Satz]

### Abgabe-Checkliste (eigene Stimme)

*(6-8 Punkte aus Schritt 3, Punkt 7, zusätzlich zur festen Checkliste unten.)*

[Platzhalter: deine eigenen Prüfpunkte, z. B. "kommt mein Lieblingswort X vor, wenn es passt?"]

---

## Gilt für jede Stimme

Die folgenden Regeln sind fest, keine Platzhalter. Sie gelten unabhängig davon, wessen Stimme du gerade schreibst.

### Verbotsliste KI-Floskeln

Diese Wörter und Muster raus, egal wessen Stimme:

- „zudem", „des Weiteren", „darüber hinaus", „nahtlos", „innovativ", „revolutionär", „bahnbrechend", „entfesseln", „eintauchen in die Welt von", „In der heutigen digitalen Welt", „Fazit:", „Zusammenfassend lässt sich sagen"
- Emoji-Aufzählungen
- „nicht nur X, sondern auch Y" als Dauerfigur
- Perfekte Parallelismen (wenn jeder Satz im Absatz gleich gebaut ist, klingt er nach Maschine)

### Keine Gedankenstriche

Kein „–" und kein „—". Das ist der bekannteste KI-Text-Marker, Leser erkennen ihn sofort. Stattdessen: Komma, Doppelpunkt, Klammer oder ein neuer Satz. Gilt auch in Überschriften und Captions. Bindestrich in einem zusammengesetzten Wort (z. B. "KI-Agent") ist kein Problem, nur der freistehende Gedankenstrich ist verboten.

### Die sechs Schreibregeln nach George Orwell (1946)

1. Nie eine Metapher, ein Gleichnis oder eine Redewendung benutzen, die man ständig gedruckt sieht.
2. Nie ein langes Wort, wo ein kurzes reicht.
3. Wenn ein Wort gestrichen werden kann, streichen.
4. Nie Passiv, wo Aktiv geht.
5. Nie Fremdwort, Fachbegriff oder Jargon, wenn es ein Alltagswort gibt.
6. Lieber eine dieser Regeln brechen, als etwas Barbarisches schreiben.

### Gesprochen vs. geschrieben

Was im gesprochenen Original oft vorkommt (Füllwörter wie "quasi", "halt", "irgendwie"), gehört in Schrift stark reduziert. In einem Reel-Skript, das laut vorgelesen wird, dürfen ein paar davon bleiben. In einer Caption oder E-Mail: fast null. Der Unterschied zwischen gesprochen und geschrieben ist Dosierung, nicht Verbot.

### Abgabe-Checkliste (fest, für jeden Text)

Vor jedem Text, der rausgeht, prüfen:

1. Kein einziger Gedankenstrich im Text? Nach „–" und „—" suchen, jeden Treffer ersetzen.
2. Steht mindestens eine konkrete Zahl oder ein eigenes Erlebnis drin, wo sonst eine Behauptung stünde?
3. Ist der Text in der Du-Form geschrieben, wenn das deine Anrede ist?
4. Kommt ein Wort von der Verbotsliste vor? Raus damit.
5. Laut vorlesen: würde ich das wirklich so sagen?
6. Kein vorgetäuschtes Wissen. Wenn du dir bei etwas nicht sicher bist, das auch so schreiben, nicht überspielen.
7. Füllwort-Dichte passt zum Format: viel im Reel-Skript erlaubt, fast keine in Caption oder E-Mail.
8. Endet der Text mit etwas Machbarem (nächster Schritt, Frage, CTA) statt mit einer Zusammenfassung?
