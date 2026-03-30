### @explicitHints true
### @hideIteration true 
# Aktivität 2 - Feuerschneise. 

```python
agent.turn(LEFT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.detect(AgentDetection.BLOCK, FORWARD) 
while True:
      pass
```

## Step 1
Schreibe einen Code, damit sich der Agent vorwärts bewegt, wenn vor ihm Redstone-Staub liegt.
Während der Vorwärtsbewegung soll der Agent links von sich eine ein Block hohe Wand bauen.
Wenn sich die Geländehöhe ändert, muss der Agent nach oben gehen und die Wand fortsetzen.

```template
//Replace the lines below with your code #
//While loop 1 with an Agent detect Redstone condition 
//While loop 2 with an Agent detect block condition 
agent.place(LEFT)
//Make the Agent move up                            
//Make the Agent place a block to its left         
//Make the Agent move forward
//End of while loop 2
//Make the Agent place a block to its left         
//Make the Agent move forward
//End while loop 1                         
```

