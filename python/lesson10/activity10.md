### @explicitHints true
### @hideIteration true 

# Muss ich das auflisten? 

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
Du hast eine Liste erhalten. Entferne die Anführungszeichen (**'**) am Anfang und Ende jeder Zeile. Um den Blocktyp zu finden, auf dem der Agent stehen soll, **sortiere** die Liste alphabetisch
und nimm den **zweiten** Eintrag. Stelle dich auf den richtigen Blocktyp und drücke die Taste, um den Agenten dorthin zu teleportieren. 
Um den Blocktyp zu finden, auf dem dein Spieler stehen soll, **drehe** die Liste um (**reverse**) und **poppe** den **vierten** Eintrag. 
Nimm den **sechsten** Blocktyp aus der Liste und stelle dich darauf.

```template
'block_list = ["DIAMOND", "ICE", "EMERALD", "STONE", "WOOD", "GOLD", "QUARTZ"]'
```


