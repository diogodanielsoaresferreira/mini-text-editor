# Mini Text Editor

This text editor is based on the [kilo text editor tutorial](https://github.com/snaptoken/kilo-tutorial).
The goal is to build a basic command-line text editor using a single C file without dependencies.

The main features in the kilo text editor are:
- Basic navigation using arrow keys
- Basic input and loading/storing files
- Search capabilities
- Syntax highlighting

Some features were added to make the text editor more complete:
- Cursor memory (when the up/down arrow key is pressed, the cursor should stay in the same column if the line it as least as long, instead of going to the first column)
- Line numbers
- Undo/Redo capabilities
