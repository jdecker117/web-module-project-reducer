# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* Triggers the handleAddOne method which dispatches(updates state) with the imported addOne function.
* The addOne function within notifies the reducer function located in reducers/index.js that the case is add one. This case adds one to the state property, total.
...

* TotalDisplay shows the total plus 1.
