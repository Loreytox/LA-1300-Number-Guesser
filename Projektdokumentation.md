# LA-1300-Number-Guesser
In this LA projekt, i'm going to program a number guesser with my newly aquired knowledge.
By: Lorenzo Lai

| Date | Version | Summary                                              |
| ----- | ------- | ------------------------------------------------------------ |
|18.08.2023       | 0.0.1   | Today, i researched information about OOP and have started working on the projekt in C#. |
|25.08.2023       | 0.0.2   | Today, i was able to implement most of my user stories in the code, but there are still some minor problems that i have to solve.|
|1.09.2023        | 0.1.0   | Today, i solved some of the minor problems of last time andd could implement some new features.|
|8.09.2023        |1.0.0    | Today, i finished the project. Sadly i couldn't implement one of the planned features, but i've added some newer minor ones (quality of life).|

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

| AP-№ | Date | Responsible | Summary | Planned time |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 18.08.23      |  Lorenzo Lai         |  The program is able to generate a number between 1 and 100.            |  5'             |
| 2.A  | 25.08.23      | Lorenzo Lai          | The program is able to tell, if the guessed number was correct.             | 15'              |
| 3.A  | 25.08.23      |  Lorenzo Lai         | The program is able to detect, if the guessed number is too low.              |  15'             |
| 3.B  |  25.08.23     | Lorenzo Lai          | The program is able to tell, if the guessed number is too high.              |  15'             |
| 4.A  |  25.08.23     |  Lorenzo Lai         |  The program is able to tell you how many tries it took to find the hidden number.            | 30'              |
| 5.A  |  25.08.23     |  Lorenzo Lai         |  The program is able to detect if the guessed number was outside of the generated numbers range.            |  20'             |
| 5.B  |  25.08.23     |  Lorenzo Lai         | The program is able to detect, if the user did not input a number.             | 20'              |
| 6.A  |  1.09.23     |  Lorenzo Lai         |  The program is able to save past sessions and output a highscore.            |  45' - 80'             |
| 7.A  |  1.09.23     |  Lorenzo Lai         |  The program will ask the user to input the teams name.            |  45'             |
| 7.B  | 1.09.23      | Lorenzo Lai          |  The program is able to understand, which team won the session.            |    25'           |

Total: 
250'

## 3 Entscheiden

I chose these user storie because they make sense to me to implement into the program.

## 4 Realisieren

| AP-№ | Date | Responsible | Planned time | Actual time |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  18.08.2023     |  Lorenzo        |    5'            |       10'-15'       |
| 2.A  |  18.08.2023     |  Lorenzo        |    15'           |       5'            |
| 3.A  |  18.08.2023     |  Lorenzo        |    15'           |       10'           |
| 3.B  |  18.08.2023     |  Lorenzo        |     15'          |       10'           |
| 4.A  |  25.08.2023     |  Lorenzo        |    30'           |      30'             |
| 5.A  |  25.08.2023     |  Lorenzo        |    20'           |      10'             |
| 5.B  |  25.08.2023     |  Lorenzo        |    20'           |      15'             |
| 6.A  |  1.09.2023      |  Lorenzo        |    45'-80'       |        80'+ (not finished)           |
| 7.A  |  1.09.2023      |  Lorenzo        |     45'          |       60'            |
| 7.B  |  1.09.2023      |  Lorenzo        |      25'         |       80'           |

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Date | Result | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |  1.09.2023     |    OK      |   Lorenzo     |
| 2.1  |  1.09.2023     |    OK      |   Lorenzo     |
| 3.1  |  1.09.2023     |    OK      |   Lorenzo     |
| 3.2  |  1.09.2023     |    OK      |   Lorenzo     |
| 4.1  |  1.09.2023     |    OK      |   Lorenzo     |
| 5.1  |  1.09.2023     |    OK      |   Lorenzo     |
| 5.2  |  1.09.2023     |    OK      |   Lorenzo     |
| 6.1  |  1.09.2023     |    NOK     |   Lorenzo     |
| 7.1  |  1.09.2023     |    OK      |   Lorenzo     |
| 7.2  |  1.09.2023     |    OK      |   Lorenzo     |

Everything was implemented without too much trouble, but i couldn't implement 6.1. I couldn't bring myself to find a solution and didn't want to copy it from somewhere else.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
