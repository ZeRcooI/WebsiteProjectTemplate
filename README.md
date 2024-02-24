# Готовый начальный шаблон для любого проекта.

- Разрешена проблема конфликта Prettier и EsList
- Подключены Gulp
- Правильно собрана архитектруа проекта
- Папку node, не нужно переносить как шаблон. Она появляется при написании npm i в терминал.(она тут для того, если что-то пойдет не так)

#настройка gulp

- npm i
- npm install gulp-cli -g
- npm install gulp-cli --save-dev
- npm install gulp --save-dev
- npm i gulp-sass --save-dev
- (sudo) npm install -g browser-sync
- npm i browser-sync --save-dev
- npm i gulp-autoprefixer --save-dev
- npm i gulp-clean-css --save-dev
- npm i sass -g
- npm i sass --save-dev

- globals: {
  $: true,
  require: true,
  process: true,
  }, //добавил это в eslintrc.js

- gulp - запуск сервера
- ctrl+c - остановка сервера

- npm i gulp-rename --save-dev
- npm i gulp-autoprefixer@8.0.0 --save-dev//исправит ошибку
- sudo npm i sass -g //может исправить ошибку

#########################################################################################################

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
"\*.fig": "default"
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
