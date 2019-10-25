# Configurando-VS-code
> Tutorial para configuração do visual studio code 
#
##### Fira Code
- Baixe o FiraCode no link https://github.com/tonsky/FiraCode/releases/download/2/FiraCode_2.zip

- Instale os arquivos da pasta <b>TTF<b>
# 
##### Configurações no VS Code
- Com seu VS Code aberto, aperte "CTRL + SHIFT + P".
- Digite "open settings" aperte ENTER.
- Cole o JSON abaixo em todo o arquivo.
- Feche e abra novamente o VS Code.
> {
    "workbench.startupEditor": "newUntitledFile",
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe", 
    "files.autoSave": "afterDelay",
    "terminal.explorerKind": "external",
    "editor.fontFamily": "'Fira Code'",
    "editor.fontLigatures": true,
    "editor.fontSize": 14,
    "window.zoomLevel": 0,
    "workbench.colorTheme": "Dracula",
    "workbench.iconTheme": "material-icon-theme",
    "javascript.updateImportsOnFileMove.enabled": "always",
    "[css]": {
        "editor.defaultFormatter": "aeschli.vscode-css-formatter"
    },
    "explorer.confirmDragAndDrop": false,
}


