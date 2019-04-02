# Voice Controlled User Interface

## How does speech recognition work?
AI/ML

## Which applications are suited for control via speech and which requirements are necessary?  ### Applications
- Personal voice assistant
- Commands in the car (TODO specify better)

## Which advantages and disadvantages offer speech controlled dialogs?
- Advantages
  - Hands free
  - No complex menu interaction
  - Quick fire and forget command
- Disadvantages
  - Hard/impossible to enter non-word content
  - Low accuracy => High chance of not doing what you want
  - Often limited to a few predefined actions
  - Often robotic, unnatural commands necessary
  - Doesn't convey information unless it's talking right at this moment

## Guidelines
### How can existing guidelines for designing interactive interfaces be formulated for voice control?
- Law of proximity (Objects closer together appear as a single unit)
- Law of equality (Similar objects appear as a group)
- Law of closedness (Closed structures are more recognizeable)
- Law of continuity (Objects in a line or curve as seen as a single figure)
- Law of experience
- Law of same fate (Objects moving in the same way appear as a group)
- Law of symmetry (Objects that are arranged in symmetry are more easily recognizable)
- Law of simplicity (The brain simplifies complex shapes)

- Different kinds of memory
  - Chunking
  - Repetiton

- Benutzer nicht mehr als 3 Informationseinheiten länger als 7 Sekunden merken lassen
- Ablenkung minimieren
- langsame Antwortzeiten vermeiden
- Fortschrittsanzeigen nutzen
- Varianten zur Erledigung einer Aufgabe minimieren
- Zwischenergebnisse präsentieren
- Interaktion so gestalten, dass Mechanismus des Erkennens angewendet wird und ein Erinnern nicht erforderlich ist
- Konsistenz zur nachhaltigen Erlernbarkeit sicherstellen
- Affordances: durch Gestaltung suggerierte Aktionen zur Benutzung eines Objekts
- Constraints (physikalisch, semantisch, kulturell, logisch) verhindern Bedienfehler
- Natürliche Abbildungen (Bedienelement <-> Welt) erhöhen Benutzbarkeit & Merkbarkeit
- Gutes Feedback
- Das System dem Anwender so zu präsentieren, dass er sich leicht ein zweckentsprechendes Modell aufbauen kann.
- Methapors
- principle of least astonishment
- Adaptierbarkeit vs. Adaptivität
- Fehlertoleranz
- Lernförderlichkeit

Shneidermans 8 goldene Regeln
- Versuche Konsistenz zu erreichen
- Biete erfahrenen Benutzern Abkürzungen an
- Biete informatives Feedback
- Dialoge sollten abgeschlossen sein
- Biete einfache Fehlerbehandlung
- Biete einfache Rücksetzmöglichkeiten (undo)
- Unterstütze benutzergesteuerten Dialog
- Reduziere die Belastung des Kurzzeitgedächtnisses

### Which additional guidelines for designing interactive voice controlled systems do you recommend?
Voice controlled interfaces should be able to parse and recognize commands in different scenarios. Often times people use different fill words, sentence strucutures and orders of actions to express a desired will. Depending on the complexity of the interface and its commands this guideline is more or less appliciable, but even in cases of high complexity voice controlled interfaces some basic commands will be available to which this guideline can apply to. Furthermore a feedback from the interface, when it is listening and when not, makes the use less stressfull since the user knows that his input is beeing recorded and processed. Such a feedback can be visual, auditorial and / or through vibrations. 

### How are the guidelines dependend on the software application?
As mentioned above the application of the guidelines depend on the complexity and environemnt of the software application. Sometimes certain guidelines are more difficult to realize or even hinder certain features of the core application. Overall it can be stated that in any case this guideline should be worked through and each point individually assesed weather it fits into the application context or not.
There will be at least a few points which are worth to realize, improving the overall experience the voice controlled system.
