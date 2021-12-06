# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* addOneHandler executes, calls dispatch.
* dispatch calls addOne
* addOne returns type of ADD_ONE.
* Goes to reducer, hits switch case ADD_ONE
* Returns spread of state, value + 1.
* State is passed back to app, where its passed into TotalDisplay.
...

* TotalDisplay shows the total plus 1.
