# ruby-snippet

This VS Code snippet extension is converted from the TextMate Ruby bundle
Original tmbundle: https://github.com/textmate/ruby.tmbundle
Mirror project: https://github.com/magicwhite/ruby-snippet

## Extension Contents
- `package.json` — extension manifest that contributes `snippets/snippets.json` for the `ruby` language.
- `snippets/snippets.json` — 106 Ruby snippets covering class/module scaffolding, Enumerable helpers, file/IO patterns, testing utilities, and metadata headers.
- `.vscode/launch.json` — debug profile to launch the extension host with this workspace.
- `vsc-extension-quickstart.md` — stock guide from the VS Code extension generator.

## Highlights
- **Scaffolding**: quick templates for classes, modules, `def` blocks, attribute accessors, and struct wrappers.
- **Enumerable idioms**: ready-made blocks for `each`, `map`, `select`, `inject`, `zip`, and other iterator helpers.
- **IO & serialization**: snippets for `File.read/foreach`, YAML and Marshal dump/load, globbing, and Forwardable setup.
- **Testing & tooling**: Benchmark harnesses, Test::Unit stubs, Rake tasks, and command-line usage guards.
- **File headers**: shebang, UTF-8 encoding pragma, and `:yields:` documentation helper with targeted scopes.

## Developing the Extension
1. Open the project in VS Code and press `F5` to start a new Extension Development Host window.
2. Create or open a `.rb` file and trigger snippet completions through IntelliSense.
3. Reload the window (`Cmd+R`/`Ctrl+R`) after editing snippets to pick up changes.

To install manually, copy the folder into `~/.vscode/extensions` and restart VS Code. For publishing guidance, see https://code.visualstudio.com/docs.
