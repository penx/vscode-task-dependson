# VS Code Issue

This repo shows [an issue with VS Code](https://github.com/microsoft/vscode/issues/70283#issuecomment-639574218) when creating a task that depends on a background/watch task:

- the launch configuration depends on task 'Two' and works fine
- the task 'One' depends on task 'Two' but never executes
