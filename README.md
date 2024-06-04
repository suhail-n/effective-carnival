# Rust Book Minigrep Project

This is an implementation of the minigrep project from the Rust book. It is a simple clone of the `grep` command.

## Commands

- `cargo run -- to poem.text` - case sensitive search
- `cargo run -- to poem.text --ignore-case` - case insensitive search
- `cargo run -- to poem.text -i` - case insensitive search
- `IGNORE_CASE=0 cargo run -- to poem.txt ` - case sensitive search using environment variable (env variable takes precendence)
- `IGNORE_CASE=1 cargo run -- to poem.txt ` - case insensitive search using environment variable (env variable takes precendence)
