### @explicitHints true

# Aktivität 2 - Felsen zerschlagen.

```python
agent.destroy(FORWARD)
agent.place(RIGHT)
agent.collect_all()
agent.move(FORWARD, 5)
agent.till(BACK)
for i in range(4):
      pass
if agent.inspect(AgentInspection.BLOCK, FORWARD) == GRASS:
    pass
else: 
    pass
```

## Step 1
**Teil 1:** Schreibe einen Code, damit der Agent vorwärtsläuft und jeden **Stein**block auf seinem Weg abbaut und einsammelt.
### ~ tutorialhint
Struktur des Agent-inspect-Befehls für Bedingungen:  
```python
agent.inspect(AgentInspection.BLOCK, DIRECTION) == BLOCK_TYPE
```

## Step 2 
**Teil 2:** Ergänze den Code so, dass der Agent nun die **Gras**blöcke bearbeitet und Setzlinge pflanzt.  
### ~ tutorialhint
Struktur des Agent-inspect-Befehls für Bedingungen:  
```python
agent.inspect(AgentInspection.BLOCK, DIRECTION) == BLOCK_TYPE
```

```template
//Place your functions below #
//Replace with comment about function below                  |Part 1   
//Declare function 1                                         |Part 1
//Make the Agent destroy the block forward                   |Part 1
    agent.move(FORWARD, 1)
//Replace with comment about function below                          |Part 2   
//Declare function 2                                                 |Part 2
//Make the Agent move forward                                        |Part 2
//Make the Agent till back                                           |Part 2
//Make the Agent place back                                          |Part 2
//Replace the lines below with your code #  
//For loop set to 12                                         |Part 1
//If else conditional with Agent inspect condition for STONE |Part 1
//Call function for removing rocks                           |Part 1
//Elif conditional with Agent inspect condition for GRASS            |Part 2            
//Call function for planting trees                                   |Part 2
//Else part of if else conditional                           |Part 1
//Make the Agent move forward                                |Part 1          
```

