### @explicitHints true

# Aktivität 1 - Stopp und Los.

```python
loops.pause(2000)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
agent.detect(AgentDetection.BLOCK, FORWARD)
```

## Step 1
**Teil 1:** Schreibe einen Code, damit sich der Agent nur bewegt, wenn links von ihm **ein** Block ist. 
Verwende für die Bedingung einen `||agent: agent detect||`-Befehl: 
```python
agent.detect(AgentDetection.BLOCK, LEFT)
```

## Step 2
**Teil 2:** Bearbeite den Code so, dass sich der Agent bewegt, wenn links von ihm **kein** Block ist. 
Füge dafür vor der Bedingung den Operator **not** hinzu. 

## Step 3
**Teil 3:** Lass den Agenten nach dem Befehl `||loops:pause||` erneut laufen, um den letzten Goldblock zu erreichen.

### ~ tutorialhint
**1000** ms sind **1** Sekunde.

```template
//Replace the lines below with your code #    
//for loop set to 7                            |Part 1
//Add the operator NOT to the condition below          |Part 2 
//if conditional with an Agent detect condition|Part 1
//Make the Agent move forward                  |Part 1
//if conditional with an Agent detect condition                |Part 3
loops.pause(2000)
//Make the Agent move forward                                  |Part 3
//End of loop
```


