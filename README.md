✅ How to Install & Use
1. 	Install the GitHub Theme Extension
• 	In VS Code, go to Extensions ()
• 	Search for "GitHub Theme" and install it & choose github dark default
2. 	Open Setting > search settings.json 
3. 	Paste the Custom Theme Code in setting.json   
4. 	Save the File
• 	Press ctrl +s  to save
5. 	Reload VS Code ctrl + shift + p
• 	Changes apply instantly, but you can reload the window ( → ) if needed
6. 	Fix Errors (if any)
• 	If you see red squiggles or errors, use GitHub Copilot or Copilot Chat to help fix them
• 	Or just ask me — I’ve got your back!




  "workbench.colorTheme": "GitHub Dark Default",

  "editor.semanticHighlighting.enabled": true,
  "editor.semanticTokenColorCustomizations": {
    "enabled": true,
    "rules": {
      "variable.defaultLibrary": "#00eeff",
      "property": "#00eeff"
    }
  },

  "editor.tokenColorCustomizations": {
    "[GitHub Dark Default]": {
      "textMateRules": [
        {
          "scope": "support.type.object.console",
          "settings": { "foreground": "#00eeff", "fontStyle": "" }
        },
        {
          "scope": [
            "variable.language.console",
            "support.function.console",
            "entity.name.function.method.console",
            "support.variable.console",
            "variable.other.object.console",
            "meta.member.expression",
            "variable.other.property"
          ],
          "settings": { "foreground": "#00eeff", "fontStyle": "" }
        },
        { "scope": "meta.brace.square", "settings": { "foreground": "#ff01c8", "fontStyle": "" } },
        { "scope": "meta.array.literal", "settings": { "foreground": "#61ff7b", "fontStyle": "" } },
        { "scope": ["punctuation.section.interpolation.begin", "punctuation.section.interpolation.end"], "settings": { "foreground": "#ff0090", "fontStyle": "" } },
        { "scope": "meta.interpolation meta.brace.round", "settings": { "foreground": "#00ffff", "fontStyle": "" } },
        { "scope": "variable.other.readwrite", "settings": { "foreground": "#fefbff", "fontStyle": "" } },
        { "scope": "string.quoted.double", "settings": { "foreground": "#f0eded", "fontStyle": "" } },
        { "scope": "string.template", "settings": { "foreground": "#fdff82", "fontStyle": "" } },
        { "scope": "variable.parameter", "settings": { "foreground": "#c17df8", "fontStyle": "" } },
        { "scope": "constant.numeric", "settings": { "foreground": "#f89538", "fontStyle": "" } },
        { "scope": "keyword", "settings": { "foreground": "#ff4141", "fontStyle": "" } },
        { "scope": "comment", "settings": { "foreground": "#555555", "fontStyle": "" } },
        { "scope": "entity.name.function", "settings": { "foreground": "#61ff7b", "fontStyle": "" } },
        { "scope": "storage.type", "settings": { "foreground": "#00ffff", "fontStyle": "" } },
        { "scope": "punctuation.definition.string", "settings": { "foreground": "#c17df8", "fontStyle": "" } },
        { "scope": "constant.language", "settings": { "foreground": "#fd9c41", "fontStyle": "" } },
        { "scope": "entity.name.tag", "settings": { "foreground": "#61ff7b", "fontStyle": "" } },
        { "scope": "invalid", "settings": { "foreground": "#ff0000", "fontStyle": "underline" } },
        { "scope": "keyword.operator.assignment", "settings": { "foreground": "#ff00b3", "fontStyle": "" } },
        { "scope": "punctuation.definition.parameters.begin", "settings": { "foreground": "#c17df8", "fontStyle": "" } },
        { "scope": "punctuation.definition.parameters.end", "settings": { "foreground": "#f1f500", "fontStyle": "" } },
        { "scope": "variable.other.constant", "settings": { "foreground": "#f5f1f7", "fontStyle": "" } },
        { "scope": "variable.language", "settings": { "foreground": "#aaaaaa", "fontStyle": "" } },
        { "scope": "entity.name.type", "settings": { "foreground": "#61ff7b", "fontStyle": "" } },
        { "scope": "support.type", "settings": { "foreground": "#ff00dd", "fontStyle": "" } },
        { "scope": "punctuation.section.group", "settings": { "foreground": "#f500fd", "fontStyle": "" } },
        { "scope": "punctuation.separator", "settings": { "foreground": "#ffccaa", "fontStyle": "" } },
        { "scope": "keyword.operator.arithmetic, keyword.operator.logical", "settings": { "foreground": "#ff00b3", "fontStyle": "" } },
        { "scope": "meta.brace.round", "settings": { "foreground": "#f700ff", "fontStyle": "" } },
        { "scope": "meta.brace.curly", "settings": { "foreground": "#ff0000", "fontStyle": "" } },
        { "scope": "meta.object-literal.key", "settings": { "foreground": "#c17df8", "fontStyle": "" } }
      ]
    }
  },

  "editor.colorCustomizations": {},
