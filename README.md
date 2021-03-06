> ## to-vscode

### Plugin

主题

- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [background](https://marketplace.visualstudio.com/items?itemName=shalldie.background)

语法提示

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [Indenticator](https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator)

风格控制

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

文件导入

- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

正则

- [any-rule](https://marketplace.visualstudio.com/items?itemName=russell.any-rule)

浏览器

- [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)

版本管理

- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

时间管理

- [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)

调试

- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

### Debugger

调试应用

```JSON
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "chrome",
      "request": "launch",
      "name": "Launch Chrome against localhost",
      "url": "http://localhost:8000",
      "webRoot": "${workspaceFolder}"
    }
  ]
}
```

调试 ts

```JSON
{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "Launch",
      "type": "node",
      "request": "launch",
      "runtimeExecutable": "npx",
      "args": ["ts-node", "${file}"],
      "skipFiles": ["<node_internals>/**"]
    }
  ]
}
```
