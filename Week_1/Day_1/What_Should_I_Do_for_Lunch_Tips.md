### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

``` javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime < 20) {
      return 'Pick something up and eat in the lab.';
    } else if (availableTime >= 20 && availableTime <= 30) {
      return 'Try to get food in a place nearby';
    } else if (availableTime > 30) {
      return 'Reconsider how much time you actually have.';
    }
  } else {
    return 'Get back to work.';
  }
};
```