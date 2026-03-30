### @explicitHints true
# Aktivität 2 - Schleudergang.

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
agent.turn(LEFT)

```

## Step 1
**Teil 1:** Schreibe einen Code, damit der Agent die schmutzige Wäsche aufnimmt, **vorwärts** in die Maschine geht, sich **20** Mal nach links dreht und dann aus
der Maschine herausgeht, um die saubere Wäsche auf der anderen Seite der schmutzigen Wäsche abzulegen.

## Step 2
**Teil 2:** Bearbeite denselben Code so, dass der Agent dasselbe für **3** Ladungen Wäsche macht. Nutze dafür vor dem restlichen 
Code eine `||loops: for||`-Schleife.

### ~ tutorialhint 
Denke daran: In diesem Fall dürfen zwei Schleifen nicht denselben Variablennamen haben, also benenne die zweite Schleife um. 
Um einen größeren Codebereich einzurücken, markiere den gewünschten Code und drücke die **Tab**-Taste. 

```template
//Replace the lines below with your code #    
//loop number 2 set to 3                              | Part 2
agent.collect_all()
agent.move(FORWARD, 7)
agent.drop_all(FORWARD)
//loop number 1                              | Part 1
//make the Agent turn left 20 times          | Part 1 
//end of loop 1
//make the Agent collect all                 | Part 1          
//make the Agent move back                   | Part 1
//make the Agent drop everything to the left | Part 1
//end of loop 2
```

