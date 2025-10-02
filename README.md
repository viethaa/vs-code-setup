**Paste this into your OWN settings.json in VS Code**
<br>
`Cmd + Shift + P` --> Open Settings (JSON)

{
  "workbench.colorTheme": "Tokyo Night Storm",
  "workbench.activityBar.location": "left",
  "workbench.editor.showTabs": "single",
  "workbench.startupEditor": "none",
  "workbench.tips.enabled": false,
  "editor.minimap.enabled": false,
  "breadcrumbs.enabled": false,
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.hidesExplorerArrows": true,
  "workbench.tree.enableStickyScroll": false,
  "workbench.tree.renderIndentGuides": "none",
  "workbench.tree.indent": 8,
  "explorer.compactFolders": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "explorer.decorations.badges": false,
  "git.decorations.enabled": false,

  "window.zoomLevel": 0,
  "window.titleBarStyle": "custom",

  "custom-ui-style.stylesheet": {
    ".monaco-workbench .titlebar": "display: none !important",
    ".monaco-workbench .part.titlebar": "display: none !important",
    ".monaco-workbench .part.editor > .content": "top: 0 !important",
    ".notification-toast": "box-shadow: none !important",
    ".quick-input-widget.show-file-icons": "box-shadow: none !important",
    ".quick-input-widget": "top: 25vh !important",
    ".quick-input-list .scrollbar": "display: none",
    ".monaco-action-bar.quick-input-inline-action-bar": "display: none",
    ".editor-widget.find-widget": "box-shadow: none; border-radius: 4px",
    ".quick-input-titlebar": "background: #100B15 !important",
    ".monaco-scrollable-element > .shadow.top": "display: none",
    ".sidebar .title-label": "padding: 0 !important",
    ".sidebar": "border: none !important",
    ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "outline: none !important",
    ".monaco-list-row.focused": "outline: none !important",
    ".monaco-editor .scroll-decoration": "display: none",
    ".title.show-file-icons .label-container .monaco-icon-label.file-icon": "justify-content: center; padding: 0 !important",
    ".title .monaco-icon-label:after": "margin-right: 0",
    ".monaco-workbench .part.editor > .content .editor-group-container > .title > .label-container > .title-label": "padding-left: 60px",
    ".monaco-editor .cursors-layer .cursor": "background-image: linear-gradient(135deg, #ffaffc 10%, #DA70D6 100%)"
  },

  "custom-ui-style.font.sansSerif": "Dank Mono",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.cursorBlinking": "solid",
  "editor.cursorStyle": "block",

  "workbench.colorCustomizations": {
    "editorCursor.background": "#000000",
    "editorOverviewRuler.wordHighlightStrongForeground": "#0000",
    "editorOverviewRuler.selectionHighlightForeground": "#0000",
    "editorOverviewRuler.rangeHighlightForeground": "#0000",
    "editorOverviewRuler.wordHighlightForeground": "#0000",
    "editorOverviewRuler.bracketMatchForeground": "#0000",
    "editorOverviewRuler.findMatchForeground": "#0000",
    "editorOverviewRuler.modifiedForeground": "#0000",
    "editorOverviewRuler.deletedForeground": "#0000",
    "editorOverviewRuler.warningForeground": "#0000",
    "editorOverviewRuler.addedForeground": "#0000",
    "editorOverviewRuler.errorForeground": "#0000",
    "editorOverviewRuler.infoForeground": "#0000",
    "editorOverviewRuler.border": "#0000",
    "[Aura Dracula Spirit (Soft)]": {
      "editorSuggestWidget.selectedBackground": "#3A334B",
      "sideBar.background": "#191521"
    }
  },

  "editor.fontFamily": "Dank Mono",
  "editor.fontSize": 12,
  "editor.fontLigatures": true,
  "editor.lineHeight": 18,

  "editor.tokenColorCustomizations": {
    "textMateRules": [
      { "scope": "comment", "settings": { "fontStyle": "italic" } }
    ]
  },

  "editor.stickyScroll.enabled": false,
  "editor.colorDecorators": false,
  "editor.codeLens": false,
  "editor.links": false,
  "editor.matchBrackets": "never",
  "editor.parameterHints.enabled": false,
  "editor.lightbulb.enabled": "off",
  "editor.hover.enabled": false,

  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,

  "scm.diffDecorations": "none",

  "editor.lineNumbers": "on",    
  "editor.tabSize": 2,
  "editor.detectIndentation": false,
  "editor.showFoldingControls": "never",
  "editor.guides.indentation": false,
  "editor.renderWhitespace": "none",
  "editor.renderLineHighlight": "none",
  "editor.occurrencesHighlight": "off",
  "editor.selectionHighlight": false,
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "editor.overviewRulerBorder": false,
  "editor.hideCursorInOverviewRuler": true,

  "editor.quickSuggestions": { "other": "off" },
  "editor.suggestOnTriggerCharacters": false,
  "editor.tabCompletion": "on",
  "editor.snippetSuggestions": "top",
  "emmet.triggerExpansionOnTab": true,

  "files.autoSave": "afterDelay",
  "update.mode": "none",
  "extensions.ignoreRecommendations": true,

  "workbench.statusBar.visible": false
}
