# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code executes for each step.

* The user presses the 1 button.
* The onClick handler on the button in App.js fires, calling the named click handler function.
* The named click handler function is invoked and runs, dispatching an addOne action package.
* The corresponding block within the reducer then executes, updating the total value in state.
* App then re-renders, displaying the updated value from the updated state.
* TotalDisplay shows the total plus 1.
