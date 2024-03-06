
# `bracket_ratatui`

[![Crates.io](https://img.shields.io/crates/v/bracket_ratatui.svg)](https://crates.io/crates/bracket_ratatui)
[![Documentation](https://docs.rs/bracket_ratatui/badge.svg)](https://docs.rs/bracket_ratatui/0.1.2/bracket_ratatui/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/bracketengine/bracket/blob/master/LICENSE)
[![Downloads](https://img.shields.io/crates/d/bracket_ratatui.svg)](https://crates.io/crates/bracket_ratatui)
[![Rust](https://github.com/gold-silver-copper/bracket_ratatui/workflows/CI/badge.svg)](https://github.com/gold-silver-copper/bracket_ratatui/actions)

This crate provides an [Ratatui](https://github.com/ratatui-org/ratatui) integration for  [bracket-lib](https://github.com/amethyst/bracket-lib) , a roguelike and terminal library for rust.
Very WIP, bracket-lib is currently unmaintained and does not support all the features needed for a good ratatui integration. But this is a good proof of concept. 


## Dependencies

Just bracket and ratatui

## Usage

See the examples hello_bracket and demo (demo currently uses some weird unsafe stuff so its not very good to learn from)

`cargo run --example hello_bracket --release`
`cargo run --example demo --release`

## See also

For extra widgets:

https://github.com/ratatui-org/awesome-ratatui

