### @explicitHints true
### @hideIteration true 
# Das Agenten-Labyrinth.

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
Steuere den Agenten durch das Labyrinth. Schreibe einen Code, um die farbigen Blöcke als Steuerung für vorwärts, links und rechts zu verwenden.
Steuere den Agenten dann bis zum Ende des Labyrinths, indem du auf den farbigen Blöcken stehst. 

### ~ tutorialhint
Versuche eine endlos laufende `while`-Schleife zu verwenden.

