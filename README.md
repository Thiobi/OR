# Frachtschiffbeladungsproblem

Ein Frachtschiff hat drei Laderäume, jeweils einen im Bug, in der Mitte und im Heck. 
Diese Laderäume können die folgenden Frachten halten:

| Laderaum | Maximales Gewicht in Tonnen | Verfügbares Volumen in m³ |
|----------|-----------------------------|---------------------------|
| Bug      | 10                          | 6800                      |
| Mitte    | 16                          | 8700                      |
| Heck     | 8                           | 5300                      |

Damit das Schiff stabil schwimmt, müssen die Gewichte in den drei Laderäumen möglichst gemäß den maximalen Zuladungen proportional verteilt werden.

Es stehen folgende vier Frachtaufträge zur Verschiffung an:

| Frachtauftrag | Gewicht in Tonnen | Volumen pro Tonne in m³ | Profit pro Tonne in CHF |
|---------------|-------------------|-------------------------|-------------------------|
| Auftrag 1     | 18                | 480                     | 310                     |
| Auftrag 2     | 15                | 650                     | 380                     |
| Auftrag 3     | 23                | 580                     | 350                     |
| Auftrag 4     | 12                | 390                     | 285                     |

Die Frachtaufträge können beliebig in Teilaufträge aufgeteilt werden. Welche Frachtaufträge sollen in welchen Gewichten auf das Frachtschiff geladen werden und wie müssen diese in den Frachträumen aufgeteilt werden, damit der Profit maximiert wird.

1. Identifizieren Sie die Entscheidungsvariablen.
2. Stellen Sie die Zielfunktion auf.
3. Stellen Sie ein geeignetes lineares Programm auf, das dieses Problem modelliert und erläutern Sie dieses.
