### @explicitHints true
### @hideIteration true 
# Aktivität 1 - Tiere kategorisieren.

```python
blocks.place()
mobs.spawn()
world(0, 0, 0)
```

## Step 1
Schreibe einen Code mit einer Liste namens **My_list**, die die Tiere in der Minecraft-Welt von **links** nach **rechts** enthält. 
Füge **4** weitere `||mobs:spawn mob at position||`-Befehle nach dem bereits vorhandenen Befehl ein. Nutze die Informationen auf den Schildern 
an den Gehegen, um diese Befehle zu vervollständigen. 

### ~ tutorialhint 
Denke daran, dass Listenpositionen bei null beginnen. 

```template 
location1 = world(-2, 40, -11)
location2 = world(-2, 40, -5)
location3 = world(-8, 40, -0)
location4 = world(-13, 40, -5)
location5 = world(-13, 40, -11)
//Replace the lines below with your code #   

//list of animals 

mobs.spawn(My_list[0], location1)
//spawn the third mob from the list at location2
//spawn the fifth mob from the list at location3
//spawn the second mob from the list at location4
//spawn the fourth mob from the list at location5
```


