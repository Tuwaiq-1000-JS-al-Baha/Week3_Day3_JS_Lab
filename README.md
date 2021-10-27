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


## DOM
## Creating Random Images

Start of with the following HTML:

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>

<body>

  <div>
    <label>
      Width:
      <input type="number" class="width" />
    </label>
    <label>
      Height:
      <input type="number" class="height" />
    </label>
    <button id="randomize">Get random image!</button>
  </div>

  <div class="image"></div>

</body>

</html>
```
### Bonus 1

- Create and link a JavaScript file
- When someone clicks on thebutton with the id `randomize`:
  - Create an `img` element
  - Create a URL based on [this documentation](https://source.unsplash.com/)
    - e.g. It might look something like this: `https://source.unsplash.com/1600x900`



### Bonus 2

Allow the user to select the width and the height!

### Bonus 3

Allow the user to select where their image comes from using a dropdown

Suggested options:

- [Picsum](https://picsum.photos/)
- [Fill Murray](http://www.fillmurray.com/)
- [Place Cage](http://www.placecage.com/)
- [Lorem Flickr](https://loremflickr.com/)
