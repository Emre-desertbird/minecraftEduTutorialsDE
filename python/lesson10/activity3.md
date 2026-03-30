### @explicitHints true
### @hideIteration true 

# Diamant oder Erde?

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
Schreibe einen Code, um die Ergebnisse dieser vier Ausdrücke zu berechnen. Du musst den Agenten zum Goldblock bringen. Platziere dafür einen Diamant- oder Erdblock
aus der Truhe, abhängig vom Ergebnis des Ausdrucks. Von links nach rechts gilt: Wenn das Ergebnis 1 ist, platziere einen Diamantblock; wenn es 0 ist, einen Erdblock. 
```python
1. 10000 / 10000 + 64.64 + 64.64 - 72 - 57.28
2. 64 / 4 + 64 / 64 - 128 / 8 - 1
3. 19283746 / 19283746 - 1 + 1000 / 100 - 9
4. 8 - 9 + 7 + 32 * 2 - 64 / 2 - 38
```
```template
//Calculate the expression: 10000 / 10000 + 64.64 + 64.64 - 72 - 57.28 
//
//Calculate the expression: 64 / 4 + 64 / 64 - 128 / 8 - 1 
//
//Calculate the expression: 19283746 / 19283746 - 1 + 1000 / 100 - 9
//
//Calculate the expression: 8 - 9 + 7 + 32 * 2 - 64 / 2 - 38 
```



