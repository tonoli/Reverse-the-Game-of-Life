# Reverse the Game of Life
Building a ML algorithm that predicts past states of a given grid of John Conway's Game of Life. [This is the official Kaggle page](https://www.kaggle.com/c/conway-s-reverse-game-of-life)

<p align="center"><img src="https://kaggle2.blob.core.windows.net/competitions/kaggle/3638/media/game_of_life.gif"></p>

## The Game of Life

The Game of Life has been created by John Conway a british mathematicien and pubished in Scientific American in 1970. Conway explains that the idea came after reading *Automata Studies, Edited by C.E. Shannon & J. McCarthy*. In there he discovers [John Van Neuman](https://en.wikipedia.org/wiki/John_von_Neumann) idea of an autonomous machine to colonize planets. Van Neuman’s idea was that we can’t afford to take humans in other planets, you got to equip your planet with an atmosphere, bring equipment and food… Instead he proposes to first send some machines over, his example was based on the colonization of Mars which is called the red planet because of iron ore. These machines have several states and one of them is smelt iron ore which will be used to build an other identical machine. But they don’t do only that as iron in Mars is iron oxide and so, when you separate it into the iron, you get oxygen out of it. Now you can build up an atmosphere containing oxygen. That's where comes the Musk's secret plan of colonizing Mars.

The "Game" takes place on a two-dimensional grid consisting of "living" and "dead" cells, and the rules to step from generation to generation are simple:

* __Overpopulation__: if a living cell is surrounded by more than three living cells, it dies.
* __Stasis__: if a living cell is surrounded by two or three living cells, it survives.
* __Underpopulation__: if a living cell is surrounded by fewer than two living cells, it dies.
* __Reproduction__: if a dead cell is surrounded by exactly three cells, it becomes a live cell.

By enforcing these rules in sequential steps, beautiful and unexpected patterns can appear.
