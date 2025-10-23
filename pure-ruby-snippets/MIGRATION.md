# Move from Legacy Snippets
- Use the `core` folder first. It holds Ruby 3 code like pattern matching, keyword hashes, data classes, and fibers.
- Leave the `deprecated/legacy.json` file for old files only. Every entry is tagged so you know it is risky.
- For Rails work, add the future `rails-snippets` pack when it launches so you get fresh patterns.
- For tests, switch to the RSpec or Minitest snippets instead of the old Test::Unit blocks.
- Replace any `:key => value` hashes with `key: value` as you go.
- Remove the legacy snippets once your project is fully on the new packs.
