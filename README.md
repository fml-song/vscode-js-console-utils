## js-quick-log

Easily insert and remove console.log statements in VS Code.

## Usage

With selection:
* Highlight a variable (or really any text)
* Press Cmd+Shift+L
* The output (on a new line) will be: console.log('variable: ', variable);
* Press Cmd+Shift+Alt+L
* The output (on a new line) will be: console.log('variable: ', JSON.parse(JSON.stringify(variable)));

Without selection:
* Press Cmd+Shift+L
* The output (on the same line) will be: console.log();
* Press Cmd+Shift+Alt+L
* The output (on the same line) will be: console.log(JSON.parse(JSON.stringify()));

To remove console.logs:
* Press Cmd+Shift+D
* This will delete all console.log statements in the current document

## License
[MIT License](LICENSE)