### @explicitHints true
### @hideIteration true 

# Do I need to list it out? 

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
You have been given a list. Delete the quotes (**'**) from the beginning and end of each line. To find what block type the Agent should stand on, **sort** the list alphabetically
and take the **second** item. Stand on the correct block type and press the button to teleport the Agent there. 
To find which block type your player should stand on, **reverse** the list and **pop** the **fourth** item. 
Get the **sixth** block type from the list and stand on it.

```template
'block_list = ["DIAMOND", "ICE", "EMERALD", "STONE", "WOOD", "GOLD", "QUARTZ"]'
```

