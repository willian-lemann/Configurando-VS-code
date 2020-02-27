# Configurando-VS-code
> Tutorial para configuração do visual studio code (Diego Fernandes - Rocketseat)
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
    "sync.removeExtensions": false,
    "workbench.startupEditor": "newUntitledFile",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Dracula",
    "editor.fontFamily": "Fira Code",
    "editor.fontSize": 14,
    "editor.fontLigatures": true,
    "emmet.syntaxProfiles": {
        "javascript":"jsx",
    },
    "emmet.includeLanguages": {
        "javascript":"javascriptreact",
    },
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "explorer.confirmDelete": false,
    "window.zoomLevel": 0
}


