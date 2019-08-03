# Vscode Settings

My vscode settings and customization

### Custom Title Bar

```json
  "window.titleBarStyle": "custom",
```

### Font Customization

```json
  "editor.fontSize": 17,
  "editor.fontFamily": "Fira Code iScript",
  "editor.fontLigatures": true,
  "terminal.integrated.fontFamily": "Fira Code iScript",
```

### Material Icon Theme

```json
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.saturation": 1,
  "dart.checkForSdkUpdates": false,
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.activeIconPack": "react_redux",
  "material-icon-theme.folders.color": "#90a4ae",
```

### Material Theme

```json
  "workbench.colorTheme": "Material Theme Palenight",
  "workbench.colorCustomizations": {
    "activityBarBadge.background": "#FF7042",
    "list.activeSelectionForeground": "#FF7042",
    "list.inactiveSelectionForeground": "#FF7042",
    "list.highlightForeground": "#FF7042",
    "scrollbarSlider.activeBackground": "#FF704250",
    "editorSuggestWidget.highlightForeground": "#FF7042",
    "textLink.foreground": "#FF7042",
    "progressBar.background": "#FF7042",
    "pickerGroup.foreground": "#FF7042",
    "tab.activeBorder": "#FF7042",
    "notificationLink.foreground": "#FF7042",
    "editorWidget.resizeBorder": "#FF7042",
    "editorWidget.border": "#FF7042",
    "settings.modifiedItemIndicator": "#FF7042",
    "settings.modifiedItemForeground": "#AB47BC",
    "settings.headerForeground": "#FF7042",
    "panelTitle.activeBorder": "#FF7042",
    "breadcrumb.activeSelectionForeground": "#FF7042",
    "menu.selectionForeground": "#FF7042",
    "menubar.selectionForeground": "#FF7042",
    "editor.findMatchBorder": "#FF7042",
    "selection.background": "#FF704240"
  },
  "materialTheme.accent": "Orange",
```

### Disable Minimap

```json
"editor.minimap.enabled": false,
```

### Enable Format on Save

```json
"editor.formatOnSave": true,
```

### Git as Terminal

```json
"terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
"terminal.integrated.rendererType": "dom",
```

### Tab Settings

```json
"[html]": {
  "editor.tabSize": 4,
  "editor.insertSpaces": true,
  "editor.detectIndentation": false
},
"editor.tabSize": 2,
```

### Gitlens

```json
"gitlens.advanced.messages": {
  "suppressShowKeyBindingsNotice": true,
  "gitlens.views.repositories.files.layout": "list",
},
```

### Emment in jsx

```json
"emmet.includeLanguages": {
  "javascript": "javascriptreact"
},
```

### Emojisense settings

```json
"emojisense.languages": {
  "markdown": true,
  "plaintext": {
    "markupCompletionsEnabled": false,
    "emojiDecoratorsEnabled": false
  },
  "html": true,
  "javascript": true,
  "typescript": true,
  "git-commit": true
},
"emojisense.unicodeCompletionsEnabled": true,
"emojisense.showOnColon": true,
```

### Others

```json
"editor.renderIndentGuides": false,
"editor.wordWrap": "on",
"editor.cursorSmoothCaretAnimation": true
"liveServer.settings.donotShowInfoMsg": true,
"liveServer.settings.donotVerifyTags": true,
"prettier.singleQuote": true,
"explorer.confirmDragAndDrop": false,
"dart.flutterSdkPath": "C:\\flutter",
"testExplorer.showCollapseButton": true,
"window.zoomLevel": 0,
```

### Peacock settings

```json
"peacock.favoriteColors": [
  {
    "name": "Angular Red",
    "value": "#b52e31"
  },
  {
    "name": "Auth0 Orange",
    "value": "#eb5424"
  },
  {
    "name": "Azure Blue",
    "value": "#007fff"
  },
  {
    "name": "C# Purple",
    "value": "#68217A"
  },
  {
    "name": "Gatsby Purple",
    "value": "#639"
  },
  {
    "name": "Go Cyan",
    "value": "#5dc9e2"
  },
  {
    "name": "Java Blue-Gray",
    "value": "#557c9b"
  },
  {
    "name": "JavaScript Yellow",
    "value": "#f9e64f"
  },
  {
    "name": "Mandalorian Blue",
    "value": "#1857a4"
  },
  {
    "name": "Node Green",
    "value": "#215732"
  },
  {
    "name": "React Blue",
    "value": "#00b3e6"
  },
  {
    "name": "Something Different",
    "value": "#832561"
  },
  {
    "name": "Vue Green",
    "value": "#42b883"
  }
],
```

### Customization of Syntax

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "Variables",
      "scope": ["variable", "string constant.other.placeholder", "source"],
      "settings": {
        "foreground": "#c1c6d1"
      }
    },
    {
      "name": "Colors",
      "scope": [
        "constant.other.color",
        "punctuation.definition.entity",
        "constant.character.entity",
        "punctuation.definition.template-expression"
      ],
      "settings": {
        "foreground": "#c3a6ff"
      }
    },
    {
      "name": "Invalid",
      "scope": ["invalid", "invalid.illegal"],
      "settings": {
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "Keyword, Storage, Number, Constant",
      "scope": [
        "keyword",
        "storage.type",
        "storage.modifier",
        "constant.numeric",
        "constant.language",
        "support.constant",
        "constant.character",
        "constant.escape"
      ],
      "settings": {
        "foreground": "#c3a6ff"
      }
    },
    {
      "name": "Operator, Misc",
      "scope": [
        "punctuation",
        "punctuation.definition.tag",
        "punctuation.separator.inheritance.php",
        "punctuation.definition.tag.html",
        "punctuation.section.embedded",
        "keyword.other.template",
        "keyword.other.substitution",
        "meta.brace",
        "meta.block",
        "meta.jsx",
        "meta.embedded.expression",
        "meta.template.expression"
      ],
      "settings": {
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "Attribute Equal Signs, handlebars operators",
      "scope": [
        "punctuation.separator.key-value.html",
        "meta.tag",
        "keyword.control",
        "keyword.operator",
        "constant.other.color",
        "punctuation.definition.constant",
        "meta.function.block.start.handlebars",
        "meta.function.inline.other",
        "meta.property-value",
        "support.constant.mathematical-symbols",
        "support.constant.vendored.property-value",
        "punctuation.definition.keyword",
        "punctuation.accessor",
        "punctuation.separator.property"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "Tag",
      "scope": [
        "entity.name.tag",
        "meta.tag.sgml",
        "markup.deleted.git_gutter",
        "support.variable.dom",
        "meta.import",
        "meta.export",
        "meta.export.default",
        "support.class.builtin",
        "support.class.component"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Function, Special Method",
      "scope": [
        "entity.name.function",
        "variable.function",
        "support.function",
        "keyword.other.special-method",
        "meta.function-call"
      ],
      "settings": {
        "foreground": "#ffd580"
      }
    },
    {
      "name": "Block Level Variables",
      "scope": ["meta.block variable.other"],
      "settings": {
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "Other Variable, String Link",
      "scope": ["support.other.variable", "string.other.link"],
      "settings": {
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "Function Argument, Tag Attribute, Embedded, Things that should be grey",
      "scope": [
        "variable.parameter",
        "text.html",
        "punctuation.section.property-list",
        "meta.property-value.scss punctuation",
        "meta.property-list",
        "keyword.operator.type.annotation"
      ],
      "settings": {
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "String, Symbols, Inherited Class, Markup Heading",
      "scope": [
        "string",
        "constant.other.symbol",
        "constant.other.key",
        "markup.heading",
        "markup.inserted.git_gutter",
        "meta.group.braces.curly constant.other.object.key.js string.unquoted.label.js",
        "punctuation.definition.string",
        "entity.name.section.markdown",
        "meta.attribute-selector"
      ],
      "settings": {
        "foreground": "#bae67e"
      }
    },
    {
      "name": "Class, Support",
      "scope": [
        "entity.name",
        "support.type",
        "support.class",
        "support.orther.namespace.use.php",
        "meta.use.php",
        "support.other.namespace.php",
        "markup.changed.git_gutter",
        "support.type.sys-types",
        "meta.object-literal.key"
      ],
      "settings": {
        "foreground": "#ffd580"
      }
    },
    {
      "name": "Entity Types",
      "scope": [
        "support.type",
        "support.class.console",
        "keyword.other.debugger",
        "entity.other.inherited-class",
        "meta.property-name",
        "punctuation.definition.raw.markdown"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "CSS Class and Support",
      "scope": [
        "source.css support.type.property-name",
        "source.sass support.type.property-name",
        "source.scss support.type.property-name",
        "source.less support.type.property-name",
        "source.stylus support.type.property-name",
        "source.postcss support.type.property-name",
        "support.type.property-name",
        "support.variable.object.node",
        "support.variable.object.process"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Sub-methods",
      "scope": ["entity.name.module.js", "variable.import.parameter.js"],
      "settings": {
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "Language methods",
      "scope": ["variable.language"],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "entity.name.method.js",
      "scope": ["entity.name.method.js"],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "meta.method.js",
      "scope": [
        "meta.class-method.js entity.name.function.js",
        "variable.function.constructor"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Attributes",
      "scope": ["entity.other.attribute-name"],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "HTML Attributes",
      "scope": [
        "text.html.basic entity.other.attribute-name.html",
        "text.html.basic entity.other.attribute-name"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "CSS Classes",
      "scope": [
        "entity.other.attribute-name.class",
        "punctuation.definition.entity.css"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "CSS ID's",
      "scope": ["source.sass keyword.control"],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Inserted",
      "scope": ["markup.inserted"],
      "settings": {
        "foreground": "#bae67e"
      }
    },
    {
      "name": "Deleted",
      "scope": ["markup.deleted"],
      "settings": {
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "Changed",
      "scope": ["markup.changed"],
      "settings": {
        "foreground": "#c3a6ff"
      }
    },
    {
      "name": "Regular Expressions",
      "scope": ["string.regexp"],
      "settings": {
        "foreground": "#bae67e"
      }
    },
    {
      "name": "Escape Characters",
      "scope": ["constant.character.escape"],
      "settings": {
        "foreground": "#bae67e"
      }
    },
    {
      "name": "URL",
      "scope": ["*url*", "*link*", "*uri*"],
      "settings": {
        "fontStyle": "underline"
      }
    },
    {
      "name": "Decorators",
      "scope": [
        "meta.decorator",
        "tag.decorator.js entity.name.tag",
        "tag.decorator.js punctuation.definition.tag"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "ES7 Bind Operator",
      "scope": [
        "source.js constant.other.object.key.js string.unquoted.label.js"
      ],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "JSON Key - Level 0",
      "scope": [
        "source.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "JSON Key - Level 1",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "JSON Key - Level 2",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "JSON Key - Level 3",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "JSON Key - Level 4",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "JSON Key - Level 5",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "JSON Key - Level 6",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "JSON Key - Level 7",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "JSON Key - Level 8",
      "scope": [
        "source.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json meta.structure.dictionary.value.json meta.structure.dictionary.json support.type.property-name.json"
      ],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "Markup - Italic",
      "scope": ["markup.italic"],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "Markup - Bold",
      "scope": ["markup.bold"],
      "settings": {
        "fontStyle": "bold",
        "foreground": "#ef6b73"
      }
    },
    {
      "name": "Markup - Underline",
      "scope": ["markup.underline"],
      "settings": {
        "fontStyle": "underline",
        "foreground": "#c3a6ff"
      }
    },
    {
      "name": "Markup - Strike",
      "scope": ["markup.strike"],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#ffcc66"
      }
    },
    {
      "name": "Markup - Quote",
      "scope": ["markup.quote"],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Markup - Raw Block",
      "scope": ["markup.raw.block"],
      "settings": {
        "foreground": "#ffae57"
      }
    },
    {
      "name": "Markup - Table",
      "scope": ["markup.table"],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Markdown - Plain",
      "scope": [
        "text.html.markdown",
        "punctuation.definition.list_item.markdown"
      ],
      "settings": {
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "Markdown - Markup Raw Inline",
      "scope": [
        "text.html.markdown markup.raw.inline",
        "text.html.markdown markup.inline.raw.string.markdown"
      ],
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Markdown - Line Break",
      "scope": ["text.html.markdown meta.dummy.line-break"],
      "settings": {
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "Markdown - Heading",
      "scope": [
        "markdown.heading",
        "markup.heading",
        "markup.heading entity.name",
        "markup.heading.markdown",
        "punctuation.definition.heading.markdown"
      ],
      "settings": {
        "foreground": "#bae67e"
      }
    },
    {
      "name": "Markdown - Blockquote",
      "scope": ["markup.quote", "punctuation.definition.blockquote.markdown"],
      "settings": {
        "fontStyle": "italic",
        "foreground": "#5ccfe6"
      }
    },
    {
      "name": "Markdown - Link",
      "scope": ["string.other.link.title.markdown"],
      "settings": {
        "fontStyle": "underline",
        "foreground": "#ffcc66"
      }
    },
    {
      "name": "Markdown - Raw Block Fenced",
      "scope": ["markup.raw.block.fenced.markdown"],
      "settings": {
        "foreground": "#d7dce2"
      }
    },
    {
      "name": "Markdown - Fenced Bode Block",
      "scope": [
        "punctuation.definition.fenced.markdown",
        "variable.language.fenced.markdown"
      ],
      "settings": {
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "Markdown - Fenced Language",
      "scope": ["variable.language.fenced.markdown"],
      "settings": {
        "fontStyle": "",
        "foreground": "#a2aabc"
      }
    },
    {
      "name": "Markdown - Separator",
      "scope": ["meta.separator"],
      "settings": {
        "fontStyle": "",
        "foreground": "#a2aabc"
      }
    },
    {
      "scope": "token.info-token",
      "settings": {
        "foreground": "#5ccfe6"
      }
    },
    {
      "scope": "token.warn-token",
      "settings": {
        "foreground": "#ffcc66"
      }
    },
    {
      "scope": "token.error-token",
      "settings": {
        "foreground": "#ef6b73"
      }
    },
    {
      "scope": [
        "keyword.control",
        "meta.type",
        "storage.modifier", //static keyword
        // "storage.type",
        "entity.other.attribute-name"
      ],
      "settings": {
        "fontStyle": "italic"
      }
    },
    {
      "scope": [
        //following will be excluded from italics (VSCode has some defaults for italics)
        "invalid",
        "keyword.operator",
        "constant.numeric.css",
        "keyword.other.unit.px.css",
        "constant.numeric.decimal.js",
        "constant.numeric.json",
        "storage.type.function"
      ],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
},
```
