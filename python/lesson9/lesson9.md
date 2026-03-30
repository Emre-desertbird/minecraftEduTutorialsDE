### @explicitHints true
# Agenten-Invasion  

```python
pos(0, 0, 0)
mobs.spawn(FIREWORKS_ROCKET, agent.get_position())
blocks.place()
blocks.test_for_block(GRASS, pos(0, 0, 0))
positions.add(pos(0, 0, 0), pos(0, 0, 0))
pos(0, 0, 0)
loops.pause(100)
agent.move(FORWARD, 5)
agent.get_position()
gameplay.title(mobs.target(NEAREST_PLAYER), "Congratulations!", "You won!")
mobs.target(NEAREST_PLAYER)
player.say("HI")
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
**Aktivität 1 - Spielsteuerung:**
Es gibt zwei 'Tasten' auf dem Controller: Blau bewegt den Agenten nach links und Rot nach rechts. Schreibe einen Code, 
sodass sich der Agent in die richtige Richtung bewegt, wenn du auf den roten oder blauen Blöcken stehst. Nutze den unten gezeigten Befehl zum Blocktest, um zu prüfen, ob ein Block 
an einer bestimmten Position ist:
```python
blocks.test_for_block(BLOCK_NAME, pos(0, 0, 0))
```

### ~ tutorialhint
Eine `||loops:while||`-Schleife mit der Bedingung **True** wiederholt sich fortlaufend. Lösche **keinen** vorgegebenen Code im Codefenster.

## Step 2
**Aktivität 2 - Schusssystem -**
**Teil 1:** Schreibe eine weitere Funktion, damit der Agent die Goldblöcke über sich abschießt.
Verwende zum Schießen den Befehl `||mobs: mob spawn||` mit **FIREWORKS_ROCKET**. Jeder getroffene Goldblock muss durch einen **AIR**-Block ersetzt werden, damit er verschwindet.
Nutze den Befehl `||agent: agent position||`, um die Position des Agenten zu erhalten.
Verwende einen Add-Positions-Befehl mit `||agent: agent position||`, um die Position des **AIR**-Blocks zu ermitteln. 
Zusammen sehen die beiden Befehle so aus:
```python 
positions.add(agent.get_position(), pos(0, 0, 0))
```
## Step 3
**Teil 2:** Ergänze den Code, damit der Agent auch auf die zweite Reihe Goldblöcke schießt, mit einer zusätzlichen `||logic: elif||`
Bedingung. 

## Step 4
**Aktivität 3 - Punktesystem:**
Im gegebenen Code gibt es die Variable `||variables:score||`. Addiere **1**, jedes Mal, wenn der Agent einen Goldblock abschießt.
Bearbeite die Bedingung der While-Schleife so, dass sie nur läuft, wenn `||variables:score||` kleiner oder gleich **15** ist. 
Füge am Anfang und Ende des Spiels zwei Splash-Screens mit `||gameplay:show title||` hinzu. Deklariere die Variable `||variable:score||`
als global mit folgendem Befehl:
```
global score 
```

### ~ tutorialhint
**<=** bedeutet **kleiner oder gleich**.


```template
//Replace with your functions below #
//Declare function 2                                                          |Act. 2 Part 1
//Declare score variable as global                                                           |Act. 3      
//If conditional, test for block condition, Agent pos + 2                     |Act. 2 Part 1
//Spawn firework rockets at Agent position                                    |Act. 2 Part 1
//Pause for 100ms                                                             |Act. 2 Part 1
//Place AIR block at Agent pos + 2                                            |Act. 2 Part 1
//Add 1 to the variable score                                                                |Act. 3
//Elif conditional, test for block condition, Agent pos + 3                   |Act. 2 Part 2
//Spawn firework rockets at Agent position                                    |Act. 2 Part 2
//Pause for 100ms                                                             |Act. 2 Part 2
//Place AIR block at Agent pos + 3                                            |Act. 2 Part 2
//Add 1 to the variable score                                                                |Act. 3
//Replace with comment about function below                           |Act. 1      
//Declare function                                                    |Act. 1
//If conditional with test for block condition (LIGHT_BLUE_CONCRETE)  |Act. 1
//Make the Agent move right                                           |Act. 1
//Elif conditional with test for block condition (RED_CONCRETE)       |Act. 1
//Make the Agent move left                                            |Act. 1
//Replace the lines below with your code #  
score = 0
//Add a start splash screen using the gameplay title command                                 |Act. 3
//Change while loop to only loop when score is <= 15                                         |Act. 3
//While loop with True as condition                                   |Act. 1
//Call function                                                       |Act. 1
//Call function 2                                                             |Act. 2 Part 1
//Add a end splash screen using the gameplay title command                                   |Act. 3
//Spawn lighting bolt on Agent position                                                      |Act. 3  
if score > 15
player.execute("scoreboard players set @p score 15")
```


