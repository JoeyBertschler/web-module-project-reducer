# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

* The user presses the 1 button.

* onClick => handleNumber(1)

* handleNumber takes num &
  dispatch(applyNumber(num))

* applyNumber is importet from actions/index, takes a number and returns APPLY_NUMBER / payload like below = (number) => {
`....return({type:APPLY_NUMBER, payload:number});`

* TotalDisplay shows the total plus 1.
