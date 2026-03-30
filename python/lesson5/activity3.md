### @explicitHints true
# Aktivität 3 - Aufräumen.

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
```

## Step 1
**Teil 1:** Schreibe einen Code, damit der Agent über jeden Block des kleinen Teppichs geht und den Schmutz aufnimmt.
### ~ tutorialhint 
Denke daran: In diesem Fall dürfen zwei Schleifen nicht denselben Variablennamen haben.

## Step 2
**Teil 2:** Bearbeite denselben Code so, dass der Agent dasselbe für den größeren Teppich macht. Wiederhole den Code dafür **3** Mal,
mit einer `||loops:for||`-Schleife. Am Ende soll der Agent den ganzen Schmutz in den Mülleimer zu seiner **rechten** Seite ablegen. 
### ~ tutorialhint 
Denke daran, dass du in deinem Code doppelte Einrückung brauchst.

```template
//Replace the lines below with your code #    
//loop number 3                                 | Part 2
//loop number 1                        | Part 1
agent.collect_all()
agent.move(FORWARD, 1)
//end of loop 1
agent.move(RIGHT, 1)
//loop number 2                        | Part 1
//make the Agent collect all           | Part 1  
//make the Agent move back             | Part 1  
//end of loop 2
//make the Agent move right                     | Part 2
//end of loop 3  
//make the Agent drop all to the right          | Part 2  
```


