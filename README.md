# latex-template-slides-1
A LaTeX template adapted from the presentation_1, this is includes all the necessary components to work with Visual Studio Code, including but not limited to:  Visual Studio Code tasks, custom syntax highlighting for LaTeX, a custom dictionary (spell checker).

## Tools required
This template is built to work with Visual Studio Code plus the following extensions:

- Code Spell Checker
- Dracula At Night
- GitLens — Git supercharged
- LaTeX Snippets
- LaTeX Workshop
- latex-formatter

## Structure
The following describes the parts of the template.

.vscode directory contains:
- dictionary.txt - works in conjunction with Code Spell Checker extension, adds words to ignore.
- cSpell.json - works in conjunction with Code Spell Checker extension, adds words to ignore.
- settings.json - custom settings for working with LaTeX, custom theme colours better highlight syntax with dark themes.
- task.json - exection direction for compiling the document.

- figures - a directory for placing figures to be included.

The main tex file is: latex-template-slides-1.tex

## Usage
Simply install the abovementioned software and extensions then save.