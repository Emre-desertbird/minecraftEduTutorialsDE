### @explicitHints true

# Aktivität 3 - Hausrekonstruktion. 

```python
agent.turn(LEFT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.detect(AgentDetection.BLOCK, FORWARD) 
while True:
      pass
```

## Step 1
**Teil 1:** Schreibe einen Code, damit der Agent der Redstone-Linie folgt und links von sich Blöcke für das Fundament des kleinen Hauses setzt.
Nutze **zwei** `||loops:while||`-Schleifen mit **zwei** Sequenzen: eine für gerade Abschnitte und eine für Außenecken. 

## Step 2 
**Teil 2:** Ergänze den Code, damit der Agent das Fundament eines größeren Hauses baut. Schreibe eine zusätzliche `||loops:while||`-Schleife mit 
einer zusätzlichen Sequenz für die Innenecken.  
### ~ tutorialhint 
Die Sequenz für die Innenecken muss einen Teil enthalten, bei dem 
der Agent einen Block über die Umrandung hinausgeht, einen Block platziert und dann zurückgeht. 

```template
//Replace the lines below with your code #    
//While loop 1 with an Agent detect condition |Part 1
//Make the Agent place a block to its left    |Part 1       
//Make the Agent move forward                 |Part 1 
//While loop 2 with an Agent detect condition |Part 1
agent.turn(LEFT_TURN)
//Make the Agent move forward                 |Part 1
//End of while loop 2
//While loop 3 with an Agent detect condition         |Part 2
//Make the Agent place a block to its left            |Part 2        
//Make the Agent move forward                         |Part 2
//Make the Agent place a block to its left            |Part 2        
//Make the Agent move back                            |Part 2
//Make the Agent turn right                           |Part 2                 
//End of while loop 3
//End of while loop 1                        
```



