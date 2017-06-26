# VS Code Tasks and Launch Files for Angular Development

- Add the following to the **scripts** section of package.json: `"open": "ng serve -o"`
- Add tasks.json and launch.json to the .vscode folder.
- To execute tasks, press Cmd+P, then type **task** and press the spacebar. 
  Start typing the name of the task and press Enter to execute the task.
- To debug the app, serve the app and press F5 with the "Launch Chrome with ng serve" debug config selected.
- To debug unit tests, launch tests the app and press F5 with the "Launch Chrome with ng test" debug config selected.
- Add the following key bindings.
    + Preferences, Keyboard Shortcuts, click **keybindings.json**

  ```json
    // Place your key bindings in this file to overwrite the defaults
    [
        // End a running background task
        {
            "key": "shift+cmd+x",
            "command": "workbench.action.tasks.terminate"
        },
        // Show Source Control
        {
            "key": "shift+cmd+g",
            "command": "workbench.view.scm"
        },
        {
            "key": "ctrl+shift+g",
            "command": "-workbench.view.scm"
        },
        // Serve the app
        {
            "key": "shift+cmd+s",
            "command": "workbench.action.tasks.runTask",
            "args": "serve"
        },
        // Open the app
        {
            "key": "shift+cmd+o",
            "command": "workbench.action.tasks.runTask",
            "args": "open"
        },
        // Run unit tests
        {
            "key": "shift+cmd+t",
            "command": "workbench.action.tasks.test"
        }
    ]
  ```
