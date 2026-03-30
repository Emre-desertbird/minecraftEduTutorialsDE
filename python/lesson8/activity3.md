### @explicitHints true

# Aktivität 3 - Baumweide. 

```python
agent.turn(RIGHT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.inspect(AgentInspection.BLOCK, FORWARD) 
agent.till(BACK)
for i in range(4):
      pass
if True: 
    pass
else: 
    pass
elif:
    pass
```

## Step 1
**Teil 1:** Schreibe drei neue Funktionen mit unterschiedlichen Sequenzen: eine für **vorwärts gehen**, eine für **links drehen** und eine für **rechts drehen**. 
Nutze diese Funktionen dann in einer `||loops:for||`-Schleife, damit der Agent den Bereich Reihe für Reihe über jeden Block durchläuft, bis er den Goldblock erreicht.

## Step 2 
**Teil 2:** Ergänze den Code so, dass der Agent die Grasblöcke bearbeitet, über die er läuft, und einen Setzling pflanzt.
Füge dafür in der Vorwärts-Funktion eine `||logic:if else||`-Bedingung hinzu, die auf Grasblöcke prüft. 

```template
//Place your functions below #  
//Add to the comment below, as it has now changed             |Part 2
//Replace with comment about function below           |Part 1    
//Declare function 1                                  |Part 1
//For loop 1 set to 9                                 |Part 1
//If else conditional with Agent inspect condition            |Part 2
//Add function that plants saplings                           |Part 2
//Place the command below in the else part of the conditional |Part 2
//Make the Agent move forward                         |Part 1
//End of loop 1
//Replace with comment about function below           |Part 1    
//Declare function 2                                  |Part 1
//Make the Agent turn right                           |Part 1
//Make the Agent move forward                         |Part 1
//Make the Agent turn right                           |Part 1
//Replace with comment about function below           |Part 1    
//Declare function 3                                  |Part 1
//Make the Agent turn left                            |Part 1
    agent.move(FORWARD, 1)
//Make the Agent turn left                            |Part 1
//Replace with comment about function below                   |Part 2 
//Declare function 4                                          |Part 2
//Make the Agent move forward                                 |Part 2
//Make the till back                                          |Part 2
//Make the place back                                         |Part 2
//Replace the lines below with your code #
//For loop 2 set to 4                                 |Part 1
//Call function to make Agent move forward            |Part 1
//Call function to make Agent turn right              |Part 1
//Call function to make Agent move forward            |Part 1
//Call function to make Agent turn left               |Part 1                       
```

