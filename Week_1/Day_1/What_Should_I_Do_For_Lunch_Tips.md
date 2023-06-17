### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log("Wait until you are hungry to take a lunch break.");
  } else if (availableTime < 20) {
    console.log("Pick up a quick snack or grab something you have ready at home.");
  } else if (availableTime <= 30) {
    console.log("You deserve a break! Take some time to cook yourself a tasty meal.");
  } else if (availableTime > 30) {
    console.log("Go get something to eat but remember this is an intense program. You should take a shorter break. ");
  }
};
```