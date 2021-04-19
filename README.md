# VSCODE_CONFIG


{
    //Tema do VsCode
    "workbench.colorTheme": "Omni",
    //Aumenta a fonte do Terminal
    "terminal.integrated.fontSize": 14,
    // Define o Tema dos Icones na sideBar
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    // Configura o Tamanho e Familia da Fonte
    "editor.tabSize": 2,
    "editor.fontSize": 18,
    "editor.lineHeight": 24,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "explorer.compactFolders": false,
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "extensions.ignoreRecommendations": true,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "breadcrumbs.enabled": false,
    "editor.parameterHints.enabled": false,
    "typescript.updateImportsOnFileMove.enabled": "never",
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "editor.rulers": [
        80,
        120
    ],
    //Code Runner
    "code-runner.clearPreviousOutput": true,
    "code-runner.ignoreSelection": true,
    "code-runner.saveFileBeforeRun": true,
    "code-runner.runInTerminal": true,
    "code-runner.preserveFocus": false,
    "code-runner.executorMap": {
        "python": "python3 -u",
        "typescript": "npx ts-node --files --transpile-only",
    },
    //Bracket Pair Colorizer 2:
    "bracket-pair-colorizer-2.colors": [
        "#8BE9FD",
        "#50FA7B",
        "#FFB86C",
        "#FF79C6",
        "#BD93F9",
        "#F1FA8C",
    ],
    "bracket-pair-colorizer-2.colorMode": "Consecutive",
    "bracket-pair-colorizer-2.forceUniqueOpeningColor": false,
    "bracket-pair-colorizer-2.forceIterationColorCycle": false,
    "bracket-pair-colorizer-2.showBracketsInGutter": true,
    "bracket-pair-colorizer-2.showBracketsInRuler": true,
    "bracket-pair-colorizer-2.showVerticalScopeLine": false,
    "bracket-pair-colorizer-2.showHorizontalScopeLine": false,
    "bracket-pair-colorizer-2.unmatchedScopeColor": "#FF5555",
    //CSspell
    "cSpell.enabled": true,
    "cSpell.language": "en,pt,pt_BR",
    //Colorize
    "colorize.hide_current_line_decorations": false,
    "colorize.include": [
        ".tsx",
        ".jsx",
        ".ts",
        ".js"
    ],
    "colorize.languages": [
        "typescriptreact",
        "javascriptreact",
        "javascript",
        "typescript",
        "css",
        "sass",
        "scss",
        "less",
        "pcss",
        "sss",
        "stylus",
        "xml",
        "svg",
        "json",
        "jsonc",
        "yaml"
    ],
    "colorize.colorized_colors": [
        "HEXA",
        "RGB",
        "HSL"
    ],
    "colorize.enable_search_variables": false,
}
