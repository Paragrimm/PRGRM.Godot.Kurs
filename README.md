# PRGRM.Godot.Kurs
Willkommen zu meinem Godot Kurs!

Dieses Projekt ist als Begleitung zum eigentlichen Kurs gedacht. Hier kannst du dir, völlig transparent, jeden Commit anschauen. Außerdem kannst du genau nachvollziehen, was in welcher Session umgesetzt wurde.

## Ist dieser Kurs für dich?
Dieser Kurs ist für dich, wenn du folgendes beherrschst:
- Grundlagen der Programmierung
  - Im Bestfall in C# oder GDScript, Sprach-Eigenheiten spielen in diesem Kurs jedoch keine allzu große Rolle
  - If/Else, Schleifen, Variablen, OOP Grundlagen
  - Dazugehörige "Lingo"; typische Begriffe aus der Softwareentwicklung solltest du kennen
- Git Grundlagen
  - Commit, Pull, Push, Checkout - sollten die wesentlichen Befehle sein

Außerdem wäre es wünschenswert, wenn du bereits eine Spielidee mitbringst, sodass du direkt anfangen kannst, mit dem gewonnenen Wissen, deine Idee(n) umzusetzen.

Falls du die oben genannten Dinge nicht beherrschst oder dir bei einzelnen Dingen unsicher bist, kannst du mich gerne diesbezüglich kontaktieren. Vielleicht bietet sich ein extra Session-Abschnitt o.ä. für dieses Thema an.

## Aufbau des Kurses
Der Kurs ist in Sessions aufgeteilt, jede Sessions besteht dabei aus Session-Abschnitten. Zudem kann es für jede Session "Zusatzmaterial" in Form von extra Videos geben, in denen ich genauer auf ein Thema eingehe.

Jede Session deckt dabei ein Themenkomplex ab, den ich in den Session-Abschnitten entsprechend aufbereite.

Um den Kurs möglichst erweiterbar zu lassen, habe ich mich dafür entschieden, "[Semantic Versioning](https://semver.org/)" für die Benennung zu verwenden.

Das bedeutet, dass du hier im "main"-Branch sozusagen die Version `0.0.0` siehst. Außerdem kannst du so einfach anhand der Bezeichnung erkennen, um welche Session, welchen Session-Abschnitt und ggf. welches konkrete Zusatzmaterial es sich handelt.

So ist das Format aufgebaut: `0.{Session}.{SessionAbschnitt}-{Zusatzmaterial}`. Version `1.0.0` markiert demzufolge das Ende des Kurses.

Beispiele für Versionen sind:
- `0.1.0` - Anfang Session 1
- `0.0.1-Literatur` - Session 0; Abschnitt 1; Zusatzmaterial zum Thema "Literatur"

## Wie kannst du dieses Repository verwenden?
Der Code zu einer jeden Session und weitere Änderungen werden in diesem Git Repository über Branches gepflegt. Es gibt den standard Main-Branch, hier werde ich immer die Beschreibung aktualisieren.

Die Idee ist, dass du zu Beginn einer Session bzw. eines Session-Abschnitts den dazugehörigen Branch "auscheckst", das machst du zum Beispiel zum Start der Session 1 über folgenden Befehl:
- `git checkout course/0.1.0`

Natürlich kannst du auch die Oberfläche, die dir deine IDE bietet verwenden. Wichtig ist nur, dass du zu Beginn den Code auscheckst, dann bist du automatisch für die Session bzw. den Session-Abschnitt vorbereitet.

## Linksammlung
- IDEs (Auswahl):
  - [VSCode](https://code.visualstudio.com/) / [VSCodium](https://vscodium.com/)
  - [Visual Studio](https://visualstudio.microsoft.com/de/downloads/)
  - [Jetbrains Rider](https://www.jetbrains.com/rider/)
- [Godot Engine](https://godotengine.org/)
  - Ich verwende die .NET Version, wenn du in GDScript programmieren möchtest, solltest du die normale Version nehmen.