### @explicitHints true

# Aktivität 1 - Wasserbarriere. 

```python
agent.turn(LEFT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.detect(AgentDetection.BLOCK, FORWARD) 
while True:
      pass
```

## Step 1
**Teil 1:** Schreibe einen Code, damit sich der Agent vorwärts bewegt, wenn vor ihm Redstone-Staub liegt. 

## Step 2 
**Teil 2:** Ergänze eine Sequenz, sodass der Agent beim Laufen rechts von sich eine zwei Blöcke hohe Wand baut. 
### ~ tutorialhint
Du musst dem Agenten keine Blöcke geben, er hat die benötigten Blöcke bereits im Inventar.  
```template
//Replace the lines below with your code #     
//While loop with an Agent detect condition |Part 1
//Make the Agent place a block to its right         |Part 2
//Make the Agent move up                            |Part 2
//Make the Agent place a block to its right         |Part 2
//Make the Agent move back down                     |Part 2:
    agent.move(FORWARD, 1)
//End of while loop                                
```

