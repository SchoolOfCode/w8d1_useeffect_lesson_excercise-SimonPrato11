[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6666966&assignment_repo_type=AssignmentRepo)
# React Side Effects

## Task 0

Open the console and add some to dos. Look at when each function is being called. Add some more console logs if you need!

## Task 1

My first side effect: changing the page title.

In `App`, change the page title to `{numthings} things to do...`, this should change every time the length of things to do changes. By interacting with the DOM directly, we are reaching outside of react, so we should use the effect hook.
