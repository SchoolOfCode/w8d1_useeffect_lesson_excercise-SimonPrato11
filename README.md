# React Side Effects

## Task 0

Open the console and add some to dos. Look at when each function is being called. Add some more console logs if you need!

## Task 1

My first side effect: changing the page title.

In `App`, change the page title to `{numthings} things to do...`, this should change every time the length of things to do changes. By interacting with the DOM directly, we are reaching outside of react, so we should use the effect hook.
