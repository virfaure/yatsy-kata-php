To practice outside-in TDD, we will work with a subset of ***John Jagger's Yatzy Kata***.

We’ll build an application called Yatzi that is a simplified and playable console version of the Yahtzee game, (it’s worth reading about the game before you start if you are not very familiar with it).

1. Our subset of the game will support only 2 categories (Ones and Twos).
2. The player needs to roll the biggest number of 1s and 2s for each category respectively.
3. Besides the player will play the 2 categories in turn.

The following is what you should see if you run the application on the console:

```
> Category: Ones
> Dice: D1:2 D2:4 D3:1 D4:6 D5:1
> [1] Dice to re-run:
$ D1 D2 D4
> Dice: D1:1 D2:5 D3:1 D4:2 D5:1
> [2] Dice to re-run:
$ D2 D4
> Dice: D1:1 D2:1 D3:1 D4:5 D5:1
> Category Ones score: 4
> Category: Twos
> Dice: D1:3 D2:5 D3:2 D4:6 D5:4 > ....
> Yahtzee score
> Ones: 4
> Twos: [Total for Twos]
> Final score: [sum of the points in each category]
```