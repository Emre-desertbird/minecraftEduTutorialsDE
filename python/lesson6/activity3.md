### @explicitHints true
### @hideIteration true 
# Aktivität 3 -  Hindurchkommen. 

```python
agent.detect(AgentDetection.BLOCK, FORWARD) 
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
```

## Step 1
Schreibe einen Code, damit der Agent zufällig platzierte Blöcke erkennt und ihnen ausweicht, während er den Parcours durchläuft. Nutze dafür eine 
`||logic:if else||`-Bedingung mit einem **elif** dazwischen. Für die **if**-Bedingung nutze zwei `||agent:agent detect||`-Befehle 
mit einem **and not**-Operator dazwischen. Für die **elif**-Bedingung nutze zwei `||agent:agent detect||`-Befehle 
mit einem **and**-Operator dazwischen. Ein Beispiel mit zwei Bedingungen und **and not**:
```python
agent.detect(AgentDetection.BLOCK, DIRECTION) and not agent.detect(AgentDetection.BLOCK, DIRECTION)
```

### ~ tutorialhint 
Wenn du mehrere Bedingungen kombinierst, kannst du **and** oder **and not** verwenden, um mehrere Zustände zu prüfen. 

```template
//Replace the lines below with your code #    
//for loop set to 23                                            
//if else conditional with two Agent detect commands, seperated by an and not operator
agent.move(LEFT, 1)                              
//elif conditional with two Agent detect commands, seperated by an and operator
agent.move(RIGHT, 2)
//else part of the else if conditional             
agent.move(FORWARD, 1)                                   
//End of loop                                       
```

