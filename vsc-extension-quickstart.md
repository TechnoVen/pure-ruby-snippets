# Welcome to Pure Ruby Snippets (2025 refresh)

## What's in this folder
* `package.json` – extension manifest that points to the snippet folders under `pure-ruby-snippets/`.
* `pure-ruby-snippets/snippets/` – Ruby, testing, Rails bridge, and deprecated snippet JSON files.
* `pure-ruby-snippets/MIGRATION.md` – quick guide for moving away from the legacy bundle.
* `README.md` – overview of the project plus testing steps.
* `LICENSE.md` – MIT license for the 2025 release.

## Get up and running
* Press `F5` to launch a new Extension Development Host window in VS Code.
* Create a file that ends in `.rb` and trigger IntelliSense (`Ctrl+Space` / `Cmd+Space`) to see the snippets.
* Reload the dev window (`Cmd+R` / `Ctrl+R`) whenever you edit the snippet files.

## Make changes safely
* Update snippet JSON files, then run `npx @vscode/vsce package` to confirm they still package.
* Use the upcoming `validate-snippets.js` script (or `npx @vscode/test-cli`) to lint snippet JSON before publishing.

## Install or publish
* Local install: run `npx @vscode/vsce package` and install the generated `.vsix` through the VS Code Extensions view.
* Marketplace: follow the latest guide at https://code.visualstudio.com/api/working-with-extensions/publishing-extension and use `@vscode/vsce` (2025 recommended) with a Personal Access Token.
