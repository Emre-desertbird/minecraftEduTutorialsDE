### @explicitHints true
### @hideIteration true 
# Aktivität 3 - Schritt für Schritt.

```python
blocks.place(GRASS_BLOCK, pos(0, 0, 0))
blocks.block_with_data(GRASS_BLOCK, 0)
```

## Step 1
Schreibe einen Code, um eine komplette Treppe aus **Ziegelstufen** zu bauen. Du musst die **zweite** und **dritte** Koordinate des **zweiten** Parameters in allen drei `||blocks: place block at position||`-Befehlen ändern. Außerdem musst du die Datenwerte in den `||blocks: block with data||`-Befehlen anpassen. Denk daran: Jeder Datenwert entspricht einer Treppenrichtung.

### ~ tutorialhint 
Sieh auf die Wände, um die Richtungen Osten, Westen, Norden und Süden zu erkennen.
Für die Datenwerte gilt: 
0 = W  
1 = E   
2 = N  
3 = S

