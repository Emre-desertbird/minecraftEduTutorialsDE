### @explicitHints true
### @hideIteration true 
# Diamantenrausch. 

```python
agent.move(FORWARD, 5)
pos(0, 0, 0)
player.say("Finished")
agent.place(LEFT)
agent.inspect(AgentInspection.BLOCK, DOWN) 
agent.turn(RIGHT_TURN)
agent.destroy(BACK)
agent.drop_all(FORWARD)
agent.collect_all()
loops.pause(500)
for i in range(10):
    pass
if True: 
    pass
else: 
    pass
elif:
    pass
while True:
    pass
```

## Step 1
Entferne die Anführungszeichen (**'**) am Anfang und Ende jeder Zeile. 
Vervollständige den Code so, dass der Agent zum Goldblock läuft und jeden Diamantblock zählt, über den er läuft.   
Am Ende, wenn der Agent den Goldblock erreicht, soll er vor sich so viele Blöcke platzieren, wie Diamantblöcke er überquert hat, 
einen nach dem anderen. Diese Blöcke werden automatisch von einem Kolben gestapelt.  
```template
'diamond = 0'
'for index in range(11):'
'    agent.move(FORWARD, 1)'
'for index2 in range(diamond):'
'    agent.place(FORWARD)'
'    loops.pause(500)'
```

