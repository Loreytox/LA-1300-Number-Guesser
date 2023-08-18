# LA-1300-Number-Guesser
In this LA projekt, i'm going to program a number guesser with my newly aquired knowledge.
By: Lorenzo Lai

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|18.08.2023       | 0.0.1   | Today, i researched information about OOP and have started working on the projekt in C# |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 My Projekt

In this LA projekt, as already mentioned above, i will test what i've learned in these last days and program with the help of C# a number guesser with a variety of features and functions.

### 1.2 User Stories

| US-№ | Liability | Type  | Explenation                       |
| ---- | --------------- | ---- | ---------------------------------- |
|1    |Must                 |Functional      | As the user, i would like to see in this projekt, the computer generating and saving a number between 1 and 100 |
|2    |Must                 |Functional      | As the user, i would like to see in this projekt, the ability for me to guess the randomly generated number. |
|3    |Must                 |Functional      | As the user, i would like to see in this projekt, the computer giving hints to the user, for example: "The number you chose was too high/low", or "Congratulations, you guessed the number correctly".  |
|4    |Must                 |Functional      | As the user, i would like to see in this projekt, the number of tries it took the user to choose correctly.  |
|5    |Must                 |Functional      | As the user, i would like to see in this projekt, a level of security, as in being able to counter error inputs. |
|6    |Can                 |Quality      | As the user, i would like to see in this projekt, a highscore of all the tries, to see which one was the best. |
|7    |Can                 |Quality      | As the user, i would like to see in this projekt, a 1 vs 1 player mode, where the first one to guess the number correctly wins. |

### 1.3 Testfälle

| TC-№ | Starting Position | Input | Expected Output |
| ---- | ------------ | ------- | ----------------- |
|1.1  |Program has been started              |-         |"Number between 1 and 100 is generated"                   |
|2.1  |Program has been started              |11         |"The number you guessed is correct, great job!"                   |
|3.1  |Program has been started              |10         |"The number you guessed is incorrect, try higher!"                   |
|3.2  |Program has been started              |12         |"The number you guessed is incorrect, try lower!"                   |
|4.1  |The hidden number has been found              |-         |"It took you 3 tries to find the hidden number!"                   |
|5.1  |Program has been started              |1000         |"The number you wrote is not between 1 and 100, please use numbers between 1 and 100 only. Try again!"          |
|5.2  |Program has been started              |ten         |"Please restrain from using letters, only numbers between 1 and 100. Try again!"                   |
|6.1  |The hidden number has been found              |-         |*Highscore is shown*                   |
|7.1  |Program has been started              |-         |"Please choose your Team name"                   |
|7.2  |Program has been started              |*Team Red* 11         |"The number you guessed is correct. Team red wins this match!"                   |

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
