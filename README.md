# Pure Ruby Snippets

Forked and updated from Ruby Snippets by https://github.com/magicwhite/ruby-snippet.
That project came from the TextMate Ruby bundle at https://github.com/textmate/ruby.tmbundle.
It stayed frozen for 9 years. I forked it, cleaned it up, and shipped it again under the MIT license so everyone can keep using it.

## What You Get
- Modern Ruby 3 examples for hashes, pattern matching, data classes, fibers, and lazy enums.
- Testing helpers for RSpec and Minitest with clear tab stops.
- A deprecated bundle that keeps every classic snippet, each one marked so you know it is old code.
- Notes that point you to new Rails, Sinatra, and Hanami packs when they are ready.

## Folder Guide
- `pure-ruby-snippets/snippets/core/core.json` – modern Ruby helpers you should use today.
- `pure-ruby-snippets/snippets/testing/testing.json` – ready blocks for RSpec and Minitest.
- `pure-ruby-snippets/snippets/rails/rails.json` – short bridge snippets plus reminders to install the Rails pack later.
- `pure-ruby-snippets/snippets/deprecated/legacy.json` – every legacy snippet with a clear DEPRECATED tag.
- `pure-ruby-snippets/MIGRATION.md` – quick steps for moving away from the old bundle.

## How To Test
1. Open this folder in VS Code.
2. Press `F5` to launch a new Extension Development Host.
3. Create a Ruby file and trigger snippets from IntelliSense.
4. Reload the dev window after you edit a snippet file.

## License
Released under the MIT license. See `LICENSE.md` for the full text.
