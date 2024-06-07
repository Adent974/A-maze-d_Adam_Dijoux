
# A-maze-d

Ce projets utilise un algorithme semblable à celui de Dijkstra, il permet à des entités de ce deplacé dans un labyrinthes complexes comportant des boucles ou des impasses jusqu'a trouvé ca fin.

## Technologie

**Langage :** C

**Libraire:** CSFML

## Lancer un test

Pour lancer le programme suivez ces etapes :

Pour creér le binaire :
```bash
  Make
```
Ensuite l'éxecuter :
```bash
  ./amazed [nom du fichier]  
```
## Bonus

Visualiser ainsi que generateur de labyrinthes:

Creér le fichier generated_map.txt :
```bash
  make bonus/csfml_map_generator && ./map_generator
```
Puis, executer le visualiseur avec la map génerer :
```bash
  ../amazed < generated_map.txt | ./bonus/visualizer/visualizer 
```


## Auteurs

- [@Adent974](https://www.github.com/Adent974)
- [@Yardaven](https://www.github.com/Yardaven)
- [@Nzoctopus](https://www.github.com/Nzoctopus)
