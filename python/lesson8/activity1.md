### @explicitHints true

# Aktivität 1 - Eine Reihe nach der anderen. 

```python
agent.till(RIGHT)
agent.move(FORWARD, 5)
agent.set_slot(1)
```

## Step 1
**Teil 1:** Schreibe einen Code, damit der Agent vorwärtsläuft und auf den **Gras**blöcken links von sich den Boden bearbeitet und Setzlinge pflanzt. Beispiel für die 
Funktionsstruktur: 
```python
def function_name():
    agent.till(RIGHT)
```

### ~ tutorialhint 
Denke daran, in einem Kommentar zu beschreiben, was deine Funktion macht.  

## Step 2 
**Teil 2:** Ergänze den Code so, dass der Agent jeden Setzling **6**-mal düngt.
### ~ tutorialhint 
Der Agent hat Dünger im **zweiten** Inventarplatz. Wechsle zwischen dem **ersten** und **zweiten** Platz mit `||agent:set active slot||`
Befehl.  

```template
//Replace with your functions below #
//Replace with comment about function below   |Part 1   
//Declare your function                       |Part 1
//Set the Agent's inventory slot to 1                 |Part 2
//Make the Agent till to its left             |Part 1
//Make the Agent place a sapling to its left  |Part 1
//Set the Agent's inventory slot to 2                 |Part 2
//Make the Agent place fertilizer to its left         |Part 2
//Make the Agent place fertilizer to its left         |Part 2
//Make the Agent place fertilizer to its left         |Part 2
//Make the Agent place fertilizer to its left         |Part 2
//Make the Agent place fertilizer to its left         |Part 2
//Make the Agent place fertilizer to its left         |Part 2
//Replace the lines below with your code #    
agent.move(FORWARD, 1)
//Call your function                          |Part 1
//Make the Agent move forward                 |Part 1
//Call your function                          |Part 1
//Make the Agent move forward                 |Part 1
//Call your function                          |Part 1                 
```


