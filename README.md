# VS Code Tasks and Launch Files for Angular Development

1. Add **tasks.json** and **launch.json** in this repo to the `.vscode` folder.

2. To execute tasks, press Cmd+P, then type **task** and press the spacebar.
    - Start typing the _name_ of the task and press `Enter` to execute the task.

3. To **debug** the _app_, first serve (`Shift+Cmd+S`) the app then press `F5` with the "Launch Chrome with ng serve" debug config selected.

4. To **debug** _unit tests_, launch tests (`Shift+Cmd+T`) the app and press F5 with the "Launch Chrome with ng test" debug config selected.

5. Add keyboard shortcuts for running tasks, as well as terminating running tasks.
    - Selec Preferences, Keyboard Shortcuts, then click keybindings.json link.
    - Copy contents of **keybindings.json** in this repo and paste them into your keybindings.json file.
