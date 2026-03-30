### @explicitHints true

# Aktivität 2 - Ernährungsbedarf.

```python
blocks.place()
```

## Step 1
Gib dem **ersten** Hund alles, was bereits in der vordefinierten Liste steht, indem du die Werte der ersten **4** `||blocks:place block at position||`-Befehle änderst
sodass jeder Befehl in Reihenfolge einen Eintrag aus der Liste platziert. Gib dann das Futter aus der Truhe an Hund 1.

### ~ tutorialhint 
Um Gegenstände aus der Hotbar fallen zu lassen, drücke die Taste [**Q**] auf deiner Tastatur. 

## Step 2
Gib dem **zweiten** Hund alles, was bereits in der Liste ist, plus zusätzliche Vitamine. 
Nutze dafür die Methode **append**, um die Variable **Vitamins** am Ende der Liste hinzuzufügen.
Ändere dann den Wert im letzten `||blocks: place block at position||`-Befehl so, dass die Vitamine in die Maschine gelegt werden, und 
gib dann das Futter an Hund 2.

## Step 3
Gib dem **dritten** Hund alles, was bereits in der Liste ist, aber ohne **Rindfleisch**. 
Nutze dafür die Methode **pop**, um die Variable **Beef** aus der Liste zu entfernen.
Gib dann das Futter an Hund 3.

### ~ tutorialhint 
Bei der Methode **pop** musst du den Positionswert der Liste verwenden und **nicht** den Namen. 

```template
Bone = world(-21, 45, -31)
Beef = world(-21, 45, -29)
Chicken = world(-21, 45, -27)
Biscuit = world(-21, 45, -25)
Vitamins = world(-21, 45, -23)
// Replace the lines below with your code #   
Dog_Food=[Bone, Beef, Chicken, Biscuit]
//Add the variable Vitamins to the list using the append method | Step 2
//Remove the variable Beef using the pop method                          | Step 3

blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
//Change the numerical value of the list below         | Step 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
//Change the numerical value of the list below         | Step 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
//Change the numerical value of the list below         | Step 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0])   
//Change the numerical value of the list below                  | Step 2
blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
```


