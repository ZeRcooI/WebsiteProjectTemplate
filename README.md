# Готовый начальный шаблон для любого проекта.

- Разрешена проблема конфликта Prettier  и EsList
- Правильно собрана архитектруа проекта
- В терминале изначально после создания проекта нужно прописать "npm i"

Мой json. 
{
  "explorer.confirmDelete": false,
  "git.ignoreMissingGitWarning": true,
  "workbench.iconTheme": "material-icon-theme",
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "liveServer.settings.donotVerifyTags": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "files.autoSave": "onFocusChange",
  "workbench.colorTheme": "dccomics",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "eslint.validate": ["javascript"],
  "prettier.documentSelectors": ["tsx", "ts", "js", "html", "css", "scss"],
  "prettier.jsxSingleQuote": true,
  "prettier.proseWrap": "preserve",
  "prettier.useTabs": false,
  "editor.renderWhitespace": "none",
  "window.density.editorTabHeight": "compact",
  "window.zoomLevel": 1,
  "explorer.confirmDragAndDrop": false,
  "editor.mouseWheelZoom": true,
  "workbench.editorAssociations": {
    "*.fig": "default"
  },
  "editor.stickyScroll.enabled": false,
  "liveSassCompile.settings.forceBaseDirectory": "",
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "~/../css"
    }
  ],
  "liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"]
}
