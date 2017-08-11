This is a for loop. It runs a fixed number of times based on a counter variable.

```JavaScript
for(var i=0; i < 5; i++){
    alert("This is a loop");
}
```

In this example:
- The counter variable is called `i` and it starts with the value of `0` - this is the part `var i = 0;`
- The loop will stop when the condition `i < 5` is no longer true - i.e. it will run when `i` equals 0, 1, 2, 3, 4 but not when `i` equals 5.
- Each time the loop runs, we add one to `i` - this is the part `i++`
- Any lines of code within the braces `{ }` will be executed each time the loop runs
