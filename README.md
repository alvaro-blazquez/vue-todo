# vue-todo

## Development container
This project provides a development container. The conatiner image is defined in a [Dockerfile](.devcontainer/Dockerfile) based on node:lts. It also provides devcontainer configuration of vscode. [https://code.visualstudio.com/docs/remote/containers]
All this container configuration can be found in [this file](.devcontainer/devcontainer.json) of the project

## Code format
The prettier configuration of this project enforces [Vue style guide](https://vuejs.org/v2/style-guide/)

## Keybinding suggestion
This keybing is to apply eslint autofix.
// Add this keybinding manually to keybinding.json

```json
{
  "key": "shift+alt+s",
  "command": "eslint.executeAutofix"
}
```

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn run serve
```

### Compiles and minifies for production

```
yarn run build
```

### Run your tests

```
yarn run test
```

### Lints and fixes files

```
yarn run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
