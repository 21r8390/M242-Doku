---
tags:
    - Programmierung
---

# Multitasking

**Präemptiv:** Threads entscheiden nicht, wann sie laufen und sind gezwungen, sich die CPU zu teilen

**Kooperativ:** Jeder Thread entscheidet, sobald er läuft, wie lange er die CPU behält und (entscheidend) wann es Zeit ist, sie abzugeben, damit ein anderer Thread sie nutzen kann.

_[Quelle](https://stackoverflow.com/a/55703529/16632604)_

## Präemptiv

Beim kooperativen Multitasking hat der Planer keinen Einfluss darauf, wann ein Thread laufen kann. Jeder **Thread entscheidet, wie lange** er die CPU behält. Wenn er beschließt, die CPU nicht mit anderen Threads zu teilen, werden keine anderen Threads ausgeführt, was zu einer so genannten "Hungersnot" führt.

## Kooperativ

Das bedeutet, dass die Threads keine Kontrolle darüber haben, **wann und/oder wie lange** sie die CPU nutzen und laufen werden. Es ist der Scheduler (eine Komponente des Betriebssystems), der zu jedem Zeitpunkt entscheidet, welcher Thread laufen kann und welcher schlafen muss. Es gibt keine festen Garantien dafür, wann ein Thread das nächste Mal laufen wird und wie lange. Das liegt ganz in der Hand des **Schedulers**.
