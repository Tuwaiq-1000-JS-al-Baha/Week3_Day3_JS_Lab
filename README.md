## Week3 Day3: JS Lab

### Exercises:

- _**Hint:** Javascript includes a `Math.random()` method.

- and another called `Math.floor()`


1. Dice Roller
    - Write a function that generates a random number from 1 to 6 and returns it.
    - Example: `rollDice() // => 3`
               `rollDice() // => 6`
    #### Tip:
- make sure you get the right number interval (never 0)
    
    - Write a function that chooses two random numbers (1-6) and returns them. It should also return the sum.
    - Example: `rollDoubleDice() // Dice rolled are 6 and 1.  Sum is 7`
    
    - BONUS: have your function take an argument of the # of dice to be rolled.
    - Example: `rollAnyDice(3) // Dice rolled are 4, 2, and 7.  Sum is 13.`

2. Rock, Paper, Scissors
    - Write a function that takes `rock`, `paper`, or `scissors` as an argument for the user 1 and a user 2 variables, and returns whether the user 1 `win`, `lose`, or `tie.
    - Example:  `playGame('rock', 'paper') // user 1 picked rock. user 2 has paper: => return 'lose'.`
    
    #### Extra Bonus:
     - Write a function that only takes `rock`, `paper`, or `scissors` as an argument for the user 1 then chooses `rock`, `paper`, or `scissors` randomly for the computer, and returns whether the user 1 `win`, `lose`, or `tie.
    - Example: `playGame('rock') // Computer picked: paper. User picked: rock.  user 1 lose => return 'lose'.`
