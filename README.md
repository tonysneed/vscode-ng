# VS Code Tasks and Launch Files for Angular Development

1. Add **tasks.json** and **launch.json** in this repo to the `.vscode` folder.

2. Add keyboard shortcuts in **keybindings.json** to your VS Code **keybindings.json**.

3. To execute a task press the corresponding keyboard shortcut.

    - Lint: `Ctrl+Shift+L`
    - Build: `Shift+Cmd+B`
    - Serve: `Shift+Cmd+S`
    - Open: `Shift+Cmd+O`
    - Tests: `Shift+Cmd+T`
    - E2E Tests: `Ctrl+Shift+E`
    - You can also execute tasks by pressing Cmd+P, then type **task** and press the spacebar.  
      Start typing the _name_ of the task and press `Enter` to execute the task.

4. To **debug** the _app_, first serve (`Shift+Cmd+S`) the app then press `F5` with the "Launch Chrome with ng serve" debug config selected.

5. To **debug** _unit tests_, launch tests (`Shift+Cmd+T`) the app and press F5 with the "Launch Chrome with ng test" debug config selected.

