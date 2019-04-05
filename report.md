# Voice Controlled User Interface

## How does speech recognition work?
AI/ML

## Which applications are suited for control via speech and which requirements are necessary?
- Personal voice assistant
- Commands in the car (TODO specify better)

## Which advantages and disadvantages offer speech controlled dialogs?
- Advantages
  - Hands free, eyes free
  - No complex menu interaction
  - Quick fire and forget command
  - Could be capable of asking questions
- Disadvantages
  - Hard/impossible to enter non-word content
  - Low accuracy => High chance of not doing what you want
  - Often limited to a few predefined actions
  - Often robotic, unnatural commands necessary

No visuals
  - Doesn't convey information unless it's talking right at this moment
  - Can't show multiple things at the same time
  - Is slower than visuals because you can't skip anything
  - If you missed something, you missed it

## Guidelines
### How can existing guidelines for designing interactive interfaces be formulated for voice control?

- [.] Law of proximity (Objects closer together appear as a single unit)
- [ ] Law of equality (Similar objects appear as a group)
- [ ] Law of closedness (Closed structures are more recognizeable)
- [ ] Law of continuity (Objects in a line or curve as seen as a single figure)
- [x] Law of experience
- [x] Law of same fate (Objects moving in the same way appear as a group)
- [x] Law of symmetry (Objects that are arranged in symmetry are more easily recognizable)
- [x] Law of simplicity (The brain simplifies complex shapes)

---

- Benutzer nicht mehr als 3 Informationseinheiten länger als 7 Sekunden merken lassen
  -> Nicht zu lange Antworten
- Ablenkung minimieren
  -> Nur wichtiges sagen (keine Zeitverschwendung)
- Langsame Antwortzeiten vermeiden
- Fortschrittsanzeigen nutzen
  -> Bsp. Alexa blinkender Ring, wenn sie "nachdenkt"
- Varianten zur Erledigung einer Aufgabe minimieren
  -> Anti guideline bei Sprache - sollte möglichst viele Wege geben etwas zu tun, da man sie nicht offensichtlich sieht
- Zwischenergebnisse präsentieren
  -> Warte, ich sehe es für dich nach
- Interaktion so gestalten, dass Mechanismus des Erkennens angewendet wird und ein Erinnern nicht erforderlich ist
- Konsistenz zur nachhaltigen Erlernbarkeit sicherstellen
- Affordances: durch Gestaltung suggerierte Aktionen zur Benutzung eines Objekts
- Constraints (physikalisch, semantisch, kulturell, logisch) verhindern Bedienfehler
- Natürliche Abbildungen (Bedienelement <-> Welt) erhöhen Benutzbarkeit & Merkbarkeit
- Gutes Feedback
  -> Erraten, was der User gemeint haben könnte und Vorschläge geben zu möglichen Befehlen
- Das System dem Anwender so zu präsentieren, dass er sich leicht ein zweckentsprechendes Modell aufbauen kann.
  -> Normaler Konversation ähnlich
  -> Oder eigene Kommandostruktur
- Methapern
- Principle of least astonishment
- Adaptierbarkeit vs. Adaptivität
- Fehlertoleranz
  -> Synonyme erkennen
  -> Störgeräusche ignorieren
  -> Zeit zum überlegen geben und nicht plötzlich antworten
- Lernförderlichkeit

Shneidermans 8 goldene Regeln
- Versuche Konsistenz zu erreichen
  -> Gleiche Sprachanfragen sollten gleiche Aktionen hervorrufen
- Biete erfahrenen Benutzern Abkürzungen an
  -> Spezielle Wörter, die man einstellen kann, die direkt eine komplexe Aktion aufrufen
- Biete informatives Feedback
  -> Gutes
- Dialoge sollten abgeschlossen sein
- Biete einfache Fehlerbehandlung
- Biete einfache Rücksetzmöglichkeiten (undo)
- Unterstütze benutzergesteuerten Dialog
  ->
- Reduziere die Belastung des Kurzzeitgedächtnisses
  -> Kurze Antworten

- Different kinds of memory
  - Chunking
  - Repetiton

### Which additional guidelines for designing interactive voice controlled systems do you recommend?
Voice controlled interfaces should be able to parse and recognize commands in
different scenarios. Often times people use different fill words, sentence
strucutures and orders of actions to express a desired will. Depending on the
complexity of the interface and its commands this guideline is more or less
appliciable, but even in cases of high complexity voice controlled interfaces
some basic commands will be available to which this guideline can apply to.
Furthermore a feedback from the interface, when it is listening and when not,
makes the use less stressfull since the user knows that his input is beeing
recorded and processed. Such a feedback can be visual, auditorial and / or
through vibrations.

### How are the guidelines dependend on the software application?
As mentioned above the application of the guidelines depend on the complexity
and environemnt of the software application. Sometimes certain guidelines are
more difficult to realize or even hinder certain features of the core
application. Overall it can be stated that in any case this guideline should be
worked through and each point individually assesed weather it fits into the
application context or not.
There will be at least a few points which are worth to realize, improving the
overall experience the voice controlled system.
