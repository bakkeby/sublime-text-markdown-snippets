This repository provides a series of Sublime Text snippets that are related to
Markdown formatting syntax.

[Sublime Text](https://www.sublimetext.com/) is a text editor and a
[snippet](https://sublime-text-unofficial-documentation.readthedocs.io/en/sublime-text-2/extensibility/snippets.html)
can be thought of as predefined text and is often used to write out template text or code.

The snippets here can be used for example to add \*\* around the selected text to make it bold.
In this scenario the snippet will ignore leading and trailing spaces in the selected text.

Snippets are usually placed in the following directory:
   - \~/.config/sublime-text/Packages/User/ (Linux)

Example keybindings:

```json
	{
		"keys": ["alt+m"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_escape.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["alt+w"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_code.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+enter"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_linebreak.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+b"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_bold.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+i"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_italic.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+u"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_underline.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+shift+s"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_strikethrough.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+m"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_monospaced.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+q"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_quote.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["ctrl+l"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_noformat.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
	{
		"keys": ["alt+l"],
		"command": "insert_snippet",
		"args": { "name": "Packages/User/markdown_link.sublime-snippet" },
		"context": [{ "key": "selector", "operator": "equal", "operand": "text.html.markdown" }]
	},
```
