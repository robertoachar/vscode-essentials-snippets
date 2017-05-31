# VSCode Essentials Snippets

> A collection of essentials snippets for Visual Studio Code.

![Preview](images/preview.gif)

# Installation

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Launch Visual Studio Code
3. Choose **Extensions** from menu
4. Search for `vscode-essentials-snippets`
5. Click **Install** to install it
6. Click **Reload** to reload the Code

# Usage

Type part of a snippet, press `enter` and the snippet unfolds. For snippets in markdown format you need to press `ctrl+space` (Windows / Linux) or `cmd+space` (OSX).

## Angular snippets

| Snippet | Content |
| ------- | ------- |
| `ng-class` | Angular Class |
| `ng-component` | Angular Component |
| `ng-directive` | Angular Directive |
| `ng-enum` | Angular Enum |
| `ng-guard` | Angular Guard |
| `ng-interface` | Angular Interface |
| `ng-module` | Angular Module |
| `ng-pipe` | Angular Pipe |
| `ng-service` | Angular Service |

## Continuous Integration snippets

| Snippet | Content |
| ------- | ------- |
| `ci-appveyor` | AppVeyor configuration file |
| `ci-circle` | Circle configuration file |
| `ci-travis` | Travis configuration file |

## Git snippets

| Snippet | Content |
| ------- | ------- |
| `gitattributes` | .gitattributes file with eol=lf |
| `gitattributes-archives` | Set archives as binary |
| `gitattributes-documents` | Set documents as binary |
| `gitattributes-executables` | Set executables as binary |
| `gitattributes-fonts` | Set fonts as binary |
| `gitattributes-graphics` | Set graphics as binary |
| `CHANGELOG` | A CHANGELOG.md template |
| `README` | A README.md template |

## Lint snippets

| Snippet | Content |
| ------- | ------- |
| `eslint` | ESLint configuration file |
| `eslintignore` | ESLint ignore file |

## Project snippets

| Snippet | Content |
| ------- | ------- |
| `editorconfig` | EditorConfig file |
| `npmrc` | npm configuration file |
| `package` | package.json file |

# Development

## Install dependencies

1. Install [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)
2. Install [Visual Studio Code](https://code.visualstudio.com/)

## Run

Clone the repo

```bash
$ git clone https://github.com/robertoachar/vscode-essentials-snippets.git
```

Install vsce

```bash
$ npm install -g vsce
```

Build the extension file

```bash
$ vsce package

# or

$ npm run build
```

Install the extension from a package file (.vsix)

1. Launch Visual Studio Code
2. Choose **Extensions** from menu
3. Click **More** > **Install from VSIX...**
4. Select the file `vscode-essentials-snippets-x.x.x.vsix`
6. Click **Reload Now** to reload the Code

## Publish

Install vsce

```bash
$ npm install -g vsce
```

Create a publisher

```bash
$ vsce create-publisher <publisher-name>
```

Login

```bash
$ vsce login <publisher-name>
```

Publish

```bash
$ vsce publish
```

For more detailed information about publish: [Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension).

# Author

[Roberto Achar](https://twitter.com/RobertoAchar)

# License

[MIT](https://github.com/robertoachar/vscode-essentials-snippets/blob/master/LICENSE)
