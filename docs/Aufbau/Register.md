---
tags:
    - Aufbau & Funktion
---

# Interner Speicher (Akku/Register)

Der **Akku** ist ein interner Speicher und Teil des [Rechenwerks](ALU.md). Während man in den ersten [Mikroprozessoren](../Micro/Microprozessor.md) den internen Speicher noch **Akkumulator**, kurz Akku, nannte, haben die gleiche Aufgabe heute die Register.
Zum internen Speicher gehören wichtige Register, die als **Zwischenspeicher** dienen und der Befehlszähler, in dem steht aus welcher Speicherzelle der nächste Befehl geladen wird.

_[Quelle](https://www.elektronik-kompendium.de/sites/com/1310171.htm)_

## Arten

Ein Register ist eine spezielle Art von Speicher in einem Computer oder Mikroprozessor, der dazu dient, Daten temporär zu speichern und auf die diese Daten schnell zugegriffen werden kann. Es handelt sich um eine kleine und schnelle Speicherzelle, die Teil des Prozessors ist und eng mit seiner internen Logik verbunden ist.

Es gibt verschiedene Arten von Registern, die verschiedene Zwecke erfüllen:

-   **Allgemeine Register:** Diese werden zur Speicherung von Daten verwendet, die vom Prozessor während der Ausführung von Anweisungen manipuliert werden. Sie dienen zur Zwischenspeicherung von Operanden, Zwischenergebnissen und Ergebnissen von Berechnungen.

-   **Statusregister:** Dieses Register enthält Statusinformationen über den Zustand des Prozessors oder bestimmte Bedingungen, die durch die Ausführung von Anweisungen entstehen können. Zum Beispiel kann es Flags enthalten, die anzeigen, ob eine vorherige Berechnung ein Überlauf oder eine Null erreicht hat.

-   **Befehlszähler (Program Counter):** Dieses Register enthält die Speicheradresse des nächsten auszuführenden Befehls im Programm. Nachdem ein Befehl abgeschlossen ist, wird der Program Counter aktualisiert, um auf den nächsten Befehl zu verweisen.

-   **Adressregister:** Diese Register enthalten Adressinformationen, die für den Zugriff auf Speicherstellen oder Peripheriegeräte verwendet werden. Sie können auch als Indexregister fungieren, um den Zugriff auf Speicheradressen zu vereinfachen.

Register sind normalerweise in begrenzter Anzahl vorhanden und ihre Größe hängt von der Architektur des Prozessors ab. Sie ermöglichen eine schnellere Datenverarbeitung, da der Zugriff auf sie wesentlich schneller ist als der Zugriff auf den Hauptspeicher. Durch die Verwendung von Registern kann die Leistung und Effizienz eines Prozessors verbessert werden.

## Akkumulator

Ein Akkumulator ist ein spezielles Register in einem Computer oder Mikroprozessor, das für die Durchführung arithmetischer und logischer Operationen verwendet wird. Es ist ein allgemeines Register, das oft für **Zwischenspeicherungszwecke** und zur Speicherung von Ergebnissen von Berechnungen dient.

Der Begriff "**Akkumulator**" stammt aus der frühen Ära der Computer, als die meisten Maschinen nur über einen einzigen Akkumulator verfügten. Heutzutage haben moderne Prozessoren normalerweise mehrere allgemeine Register, aber der Begriff "Akkumulator" wird immer noch verwendet, um ein bestimmtes Register zu bezeichnen, das für ähnliche Zwecke verwendet wird.

Ein Akkumulator kann als **temporärer Speicher** betrachtet werden, in dem Operanden für **arithmetische oder logische Operationen** zwischengespeichert werden. Der Inhalt des Akkumulators wird mit anderen Daten im Prozessor manipuliert, um Berechnungen durchzuführen. Das Ergebnis einer Operation wird normalerweise im Akkumulator gespeichert, von wo aus es weiterverwendet oder in den Hauptspeicher geschrieben werden kann.

Die Verwendung eines Akkumulators ermöglicht es dem Prozessor, wiederholt auf die Daten zuzugreifen, ohne ständig auf den Hauptspeicher zugreifen zu müssen. Dies führt zu einer verbesserten Leistung, da der Zugriff auf den Akkumulator viel schneller ist als der Zugriff auf den Hauptspeicher.

Es ist wichtig anzumerken, dass der Begriff "Akkumulator" in verschiedenen Kontexten unterschiedliche Bedeutungen haben kann. In einigen Prozessorarchitekturen kann der Begriff auch für spezielle Register verwendet werden, die für bestimmte Aufgaben wie Gleitkommaoperationen, Adressberechnungen oder Vektorverarbeitung bestimmt sind. In jedem Fall **bezieht sich ein Akkumulator jedoch auf ein Register**, das für die Zwischenspeicherung von Daten während der Ausführung von Operationen verwendet wird.
