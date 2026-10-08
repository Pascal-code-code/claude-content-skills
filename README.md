# Claude Content-Skills

Claude schneidet nicht nur meine Videos, er ist inzwischen auch mein Creative Manager. Er interviewt mich, recherchiert, was meine Zielgruppe gerade fragt, baut daraus den Content-Plan, schreibt die Skripte in meinem Ton und hilft beim Schnitt. Genau diese fünf Skills bekommst du hier.

Die Anleitung Schritt für Schritt, mit Beschreibung jedes Skills, liegt in [`docs/Anleitung.pdf`](docs/Anleitung.pdf).

## Die fünf Skills

| Skill | Was er macht | Ergebnis |
|---|---|---|
| `/interview` | Fragt dich eine Frage nach der anderen: wer du bist, was du anbietest, wie du deinen Kunden hilfst, wer zuschaut, was du belegen kannst. Optional baut er deine Stimme. | `mein-content/profil.md`, `stimme.md` |
| `/recherche` | Sucht im Netz, was deine Zielgruppe fragt, was neu ist und was bei anderen läuft. Jede Aussage mit Link. | `mein-content/recherche/<datum>.md` |
| `/content-plan` | Baut daraus den Plan: welches Video an welchem Tag, mit Hook-Idee, Beleg und CTA. Wertet später deine Zahlen aus. | `mein-content/plan.md` |
| `/skript` | Schreibt pro Video das Skript in deinem Ton, mit drei Hooks zum Testen. | `mein-content/skripte/` |
| `/edit` | Bringt deine Aufnahme zum fertigen Reel. Claude schneidet selbst, oder du bekommst eine Schnittliste für CapCut. | fertiges Video |

Die Skills bauen aufeinander auf und lesen alle aus dem Ordner `mein-content/`. Was du einmal im Interview erzählst, musst du nie wieder erklären.

## Quick Start

1. Auf GitHub oben den grünen Button "Code", dann "Download ZIP", entpacken. Oder per Terminal:
   ```
   git clone https://github.com/Pascal-code-code/claude-content-skills.git
   ```
2. Den Ordner in Claude Code öffnen. Nach dem ZIP-Download heißt er "claude-content-skills-main", nach git clone "claude-content-skills". In der Desktop-App: Ordner wählen. Im Terminal: in den Ordner wechseln, dann `claude` tippen.
3. Tipp `/interview` und beantworte die Fragen. Dauert 15 bis 20 Minuten.
4. Dann der Reihe nach `/recherche`, `/content-plan`, `/skript`. Claude sagt dir nach jedem Schritt, was als Nächstes kommt.
5. Video drehen, dann `/edit`.

Willst du die Skills in jedem Ordner haben, nicht nur in diesem: einmal `mkdir -p ~/.claude/skills && cp -R .claude/skills/* ~/.claude/skills/` im Terminal (Mac und Linux). Dann legt Claude `mein-content/` in dem Ordner an, in dem du gerade arbeitest.

## Was im Repo liegt

- `.claude/skills/`: die fünf Skills, je ein Ordner mit `SKILL.md` und Hintergrundwissen in `references/`
- `mein-content/`: hier landet alles über dich und deinen Content (am Anfang leer)
- `docs/Anleitung.pdf`: die Anleitung zum Ausdrucken oder Nebenherlesen
- `CLAUDE.md`: sagt Claude, welcher Skill wann dran ist

## Voraussetzungen

- Claude Code, mit Pro- oder Max-Plan
- Für `/recherche`: Claude Code braucht die Websuche (ist normalerweise an, Claude fragt beim ersten Mal um Erlaubnis)
- Für `/edit` mit Claude als Cutter: ein Mac und ~5 GB frei. Selbst schneiden geht überall.

## Wichtig, bevor du loslegst

Die Skills erfinden nichts. Keine Zahlen, keine Kundenergebnisse, keine Erfolge, die du nicht selbst genannt hast. Fehlt ein Beleg, steht im Skript "Beleg fehlt noch". Das kostet am Anfang ein paar Klicks mehr, aber es ist das, was dich auf Dauer von den Accounts mit den ausgedachten Zahlen unterscheidet.

Ein paar Regeln in den Skills stammen aus meinen eigenen Reels und deren Insights, andere aus Methoden anderer Creator. Was gemessen ist und was nur Empfehlung, steht jeweils dabei.

## Fragen

Wenn etwas hakt, schreib mir auf Instagram oder in die Community. Am besten mit einem Screenshot von der Stelle, wo es hängt.

## Credits und Lizenzen

- Einige Methoden lehnen sich an die Skills von Eric Siu (github.com/ericosiu/ai-marketing-skills) und Corey Haines (github.com/coreyhaines31/marketingskills) an, beide unter MIT-Lizenz. Details in [THIRD_PARTY.md](THIRD_PARTY.md).
- Der Schnitt mit Claude läuft über den [Claude Video Editor](https://github.com/Pascal-code-code/claude-video-editor).

Claude ist eine Marke von Anthropic. Dieses Projekt steht in keiner Verbindung zu Anthropic.

Inhalt steht unter der MIT-Lizenz, © 2026 Pascal Frey.
