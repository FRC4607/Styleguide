# Styleguide
We are using a modified version of the Google Styleguide and the 
<a href="https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-checkstyle">
Checkstyle for Java</a> extension to lint our Java files.

## Usage
1. Install the <a href="https://marketplace.visualstudio.com/items?itemName=shengchen.vscode-checkstyle">
Checkstyle for Java</a> extension and add styleguide-frc4607.xml to the project directory
2. Add/modify the following in .vscode/settings.json

```json
"[java]": {
    "editor.tabSize": 4,
    "editor.detectIndentation": false,
    "editor.insertSpaces": true
},
"editor.formatOnSave": false,
"java.checkstyle.configuration": "${workspaceFolder}/styleguide-frc4607.xml",
"java.checkstyle.version": "10.3",
```
3. (Optional) Add the 
<a href="https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker">
Code Spell Checker</a> extension.

## About
This linting is based off of the <a href="https://google.github.io/styleguide/javaguide.html">Google Style Guide</a>
modified to our liking.
