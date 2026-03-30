### @explicitHints true
 
# Aktivität 2 -  Ist es links oder rechts? 

```python
agent.inspect(AgentInspection.BLOCK, FORWARD)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
```

## Step 1
**Teil 1:** Schreibe einen Code mit einer `||logic:if else||`-Bedingung, damit der Agent am Schild nach links dreht und
sich dann vorwärts auf den Goldblock bewegt. Nutze `||agent:agent inspect||` als Bedingung und vergleiche mit der Variable **left**.
Der Befehl `||agent:agent inspect||` sieht so aus: 
```python
agent.inspect(AgentInspection.BLOCK, FORWARD)
```
Nutze die bereits vorhandenen Variablen in deinem Code: left = BLUE_GLAZED_TERRACOTTA, right = PINK_GLAZED_TERRACOTTA.
### ~ tutorialhint 
Um zu prüfen, ob zwei Werte gleich sind, verwende **==**.

## Step 2
**Teil 2:** Bearbeite den Code so, dass der Agent in beide Richtungen abbiegt, bis er den Goldblock erreicht. Füge dazu ein **elif**
zwischen **if** und **else** ein.
### ~ tutorialhint 
Verwende **elif** mit einem `||agent:agent inspect||`-Befehl
als Bedingung und vergleiche mit der Variable **right**.

```template
left = BLUE_GLAZED_TERRACOTTA
right = PINK_GLAZED_TERRACOTTA
//Replace the lines below with your code #
//Change value of loop below from 9 to 21                     |Part 2
//for loop set to 9                                   |Part 1
//if else conditional with an Agent inspect condition |Part 1
agent.turn(LEFT_TURN)
//elif conditional with an Agent inspect condition            |Part 2
//Make the agent turn right                                   |Part 2
//else part of the if else conditional                |Part 1
//Make the agent move forward                         |Part 1
//End of loop                                         |Part 1
```


