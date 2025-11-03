✅ How to Install & Use
1. 	Install the GitHub Theme Extension
• 	In VS Code, go to Extensions ()
• 	Search for "GitHub Theme" and install it
2. 	Open Setting > search settings.json 
3. 	Paste the Custom Theme Code in setting.json   
4. 	Save the File
• 	Press ctrl +s  to save
5. 	Reload VS Code ctrl + shift + p
• 	Changes apply instantly, but you can reload the window ( → ) if needed
6. 	Fix Errors (if any)
• 	If you see red squiggles or errors, use GitHub Copilot or Copilot Chat to help fix them
• 	Or just ask me — I’ve got your back!




{
  // Apply settings to all profiles (empty for now)
  "workbench.settings.applyToAllProfiles": [],

  // Use full tabs instead of preview mode
  "workbench.editor.enablePreview": false,

  // Set the theme to GitHub Dark Default
  "workbench.colorTheme": "GitHub Dark Default",

  // Customize syntax highlighting for GitHub Dark Default
  "editor.tokenColorCustomizations": {
    "[GitHub Dark Default]": {
      "textMateRules": [
        // Highlight the word "console" (e.g., console.log)
        {
          "scope": "variable.language.console",
          "settings": {
            "foreground": "#00ffff",
            "fontStyle": "italic"
          }
        },
        // Highlight console methods like .log, .warn, .error
        {
          "scope": [
            "support.function.console",
            "entity.name.function.method.console"
          ],
          "settings": {
            "foreground": "#ff6ec7",
            "fontStyle": "bold"
          }
        },
        // Highlight square brackets [ ]
        {
          "scope": "meta.brace.square",
          "settings": {
            "foreground": "#ff01c8"
          }
        },
        // Highlight array items inside [ ]
        {
          "scope": "meta.array.literal",
          "settings": {
            "foreground": "#61ff7b"
          }
        },
        // Highlight ${ and } in template strings
        {
          "scope": [
            "punctuation.section.interpolation.begin",
            "punctuation.section.interpolation.end"
          ],
          "settings": {
            "foreground": "#ff0090"
          }
        },
        // Highlight ( ) inside ${ }
        {
          "scope": "meta.interpolation meta.brace.round",
          "settings": {
            "foreground": "#7a63fa"
          }
        },
        // Highlight regular variables
        {
          "scope": "variable.other.readwrite",
          "settings": {
            "foreground": "#fefbff"
          }
        },
        // Highlight double-quoted strings
        {
          "scope": "string.quoted.double",
          "settings": {
            "foreground": "#f0eded"
          }
        },
        // Highlight template string content
        {
          "scope": "string.template",
          "settings": {
            "foreground": "#fdff82"
          }
        },
        // Highlight function parameters
        {
          "scope": "variable.parameter",
          "settings": {
            "foreground": "#c17df8"
          }
        },
        // Highlight object properties
        {
          "scope": "variable.other.property",
          "settings": {
            "foreground": "#c17df8"
          }
        },
        // Highlight numbers
        {
          "scope": "constant.numeric",
          "settings": {
            "foreground": "#f89538"
          }
        },
        // Highlight keywords like if, return, const
        {
          "scope": "keyword",
          "settings": {
            "foreground": "#ff4141"
          }
        },
        // Highlight comments
        {
          "scope": "comment",
          "settings": {
            "foreground": "#555555"
          }
        },
        // Highlight function names
        {
          "scope": "entity.name.function",
          "settings": {
            "foreground": "#61ff7b"
          }
        },
        // Highlight type keywords like function, class
        {
          "scope": "storage.type",
          "settings": {
            "foreground": "#00ffff"
          }
        },
        // Highlight quote marks
        {
          "scope": "punctuation.definition.string",
          "settings": {
            "foreground": "#c17df8"
          }
        },
        // Highlight constants like true, false, null
        {
          "scope": "constant.language",
          "settings": {
            "foreground": "#fd9c41"
          }
        },
        // Highlight JSX tags like <div>
        {
          "scope": "entity.name.tag",
          "settings": {
            "foreground": "#61ff7b"
          }
        },
        // Highlight syntax errors
        {
          "scope": "invalid",
          "settings": {
            "foreground": "#ff0000",
            "fontStyle": "underline"
          }
        },
        // Highlight assignment operator =
        {
          "scope": "keyword.operator.assignment",
          "settings": {
            "foreground": "#ff00b3"
          }
        },
        // Highlight ( in function parameters
        {
          "scope": "punctuation.definition.parameters.begin",
          "settings": {
            "foreground": "#c17df8"
          }
        },
        // Highlight ) in function parameters
        {
          "scope": "punctuation.definition.parameters.end",
          "settings": {
            "foreground": "#f1f500"
          }
        },
        // Highlight constants like API_KEY
        {
          "scope": "variable.other.constant",
          "settings": {
            "foreground": "#f5f1f7"
          }
        },
        // Highlight language keywords like this, super
        {
          "scope": "variable.language",
          "settings": {
            "foreground": "#aaaaaa"
          }
        },
        // Highlight type names like class User
        {
          "scope": "entity.name.type",
          "settings": {
            "foreground": "#61ff7b"
          }
        },
        // Highlight built-in types like String, Number
        {
          "scope": "support.type",
          "settings": {
            "foreground": "#ff00dd"
          }
        },
        // Highlight general grouping punctuation ( [ {
        {
          "scope": "punctuation.section.group",
          "settings": {
            "foreground": "#f500fd"
          }
        },
        // Highlight separators like , ;
        {
          "scope": "punctuation.separator",
          "settings": {
            "foreground": "#ffccaa"
          }
        },
        // Highlight arithmetic and logical operators
        {
          "scope": "keyword.operator.arithmetic, keyword.operator.logical",
          "settings": {
            "foreground": "#ff00b3"
          }
        },
        // Highlight round brackets () outside ${}
        {
          "scope": "meta.brace.round",
          "settings": {
            "foreground": "#f700ff"
          }
        },
        // Highlight curly braces {}
        {
          "scope": "meta.brace.curly",
          "settings": {
            "foreground": "#ff0000"
          }
        },
        // Highlight object keys in { key: value }
        {
          "scope": "meta.object-literal.key",
          "settings": {
            "foreground": "#c17df8"
          }
        }
      ]
    }
  }
}

