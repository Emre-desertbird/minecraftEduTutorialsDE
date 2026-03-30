### @explicitHints true

# Aktivität 3 - Wie heißt die Katze?

```python
player.say("hi")
```

## Step 1
Setze den letzten Namen in der Liste der Katzennamen auf den String **Shadow**. 
Ändere den Wert im Befehl `||player:say||`, sodass der **letzte** Name der Liste angezeigt wird. 
Drücke dann die Schaltfläche **select a cat** und wähle die Katze aus, die im Chat angezeigt wird.   
### ~ tutorialhint 
Um einen Wert in einer Liste zu ändern, nutze: List_Name[positional value] = "New Cat Name".

## Step 2
Sortiere die Liste der Katzennamen alphabetisch mit der Methode **sort**. 
Ändere danach den Wert im `||player:say||`-Befehl so, dass der **vierte** Name in der Liste angezeigt wird.   
Denk daran: Listen zählen ab 0, daher ist der 4. Eintrag nicht `Cat_Names[4]`.    
Drücke dann die Schaltfläche **select a cat** und wähle die Katze aus, die im Chat angezeigt wird.   
### ~ tutorialhint 
Denke daran, dass Listenpositionen bei null beginnen. 

## Step 3
Drehe die Liste der Katzennamen mit der Methode **reverse** um. 
Behalte denselben Wert im Befehl `||player:say||` bei.
Drücke dann die Schaltfläche **select a cat** und wähle die Katze aus, die im Chat angezeigt wird.   

```template
Cat_Names= ["Smokey", "Oreo", "Sammy", "Patch", "Princess", "Snowy"]
//Replace the lines below with your code #   
//Change the last name to shadow           | Step 1
//Sort the names alphabetically in the list         | Step 2
//Reverse all names                                          | Step 3 
//Change the value of the list below | Step 1,2,3
player.say(Cat_Names[0])  
```


