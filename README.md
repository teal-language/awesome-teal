# awesome-teal

This is a curated list of projects related to the [Teal programming language](http://teal-language.org)!
Teal is a dialect of [Lua](http://lua.org) which adds a static type system.

## Compiler and tools

* Run Teal
  * [**tl**](https://github.com/teal-language/tl) - the Teal compiler!
  * [**teal-playground**](https://github.com/teal-language/teal-playground) - try Teal right from your browser!
  * [**teal-cli**](https://github.com/euclidianAce/teal-cli) - "An unofficial command line interface interface to the Teal compiler", an experimental alternative CLI
  * [**cyan**](https://github.com/teal-language/cyan) - The Teal build system and project manager
  * [**tlcheck**](https://github.com/svermeulen/tlcheck) - Simple command line tool to type check a given teal file/directory
  * [**tluvit**](https://github.com/UrNightmaree/tluvit) - A Teal (.tl) runner for the [Luvit](https://luvit.io) Runtime

* Parsing
  * [**tree-sitter-teal**](https://github.com/euclidianAce/tree-sitter-teal) - A
    [tree-sitter](http://tree-sitter.github.io/tree-sitter/) parser for Teal
  * [**ltreesitter**](https://github.com/euclidianAce/ltreesitter) - Lua bindings to the [tree-sitter](http://tree-sitter.github.io/tree-sitter) parsing library api, complete with Teal type definitions.

## Language integrations

* Lua
  * [**teal-types**](https://github.com/teal-language/teal-types) - A collaborative archive of Teal type definitions
    of Lua libraries. This is similar to projects such as [typeshed](https://github.com/python/typeshed/) for Python
    and [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/) for TypeScript.
* Rust
  * [**tealr**](https://github.com/lenscas/tealr) - A wrapper around [rlua](https://crates.io/crates/rlua)
    to help generating definition files exposing types to Teal
* Postgres
  * [**tealsql**](https://github.com/lenscas/tealsql) - An SQL client build to come with autogenerated teal type definitions.
  * [**tealsql_cli**](https://github.com/lenscas/tealsql) - a CLI to turn sql files into teal code and types, similar to [pgtyped]("https://github.com/adelsz/pgtyped") but for teal.

## Editor support

* [**vscode-teal**](https://github.com/teal-language/vscode-teal) - Teal language support for Visual Studio Code
* [**vim-teal**](https://github.com/teal-language/vim-teal) - Teal support for Vim
* [**nvim-treesitter**](https://github.com/nvim-treesitter/nvim-treesitter) - Includes an installer for [tree-sitter-teal](https://github.com/euclidianAce/tree-sitter-teal) to use for high-performance syntax highlighting in NeoVim
* [**howl-teal**](https://github.com/ghsttwn/howl-teal) - Teal support for Howl

## Web

* [**Teal Pages**](https://github.com/exlunaproject/teal-pages) - Teal Pages Template Preprocessor,
  enables `<?teal` tag that executes Teal
* [**Algernon**](https://github.com/xyproto/algernon) - Small self-contained pure-Go web server with support for Teal scripting

## Neovim

* [**crates.nvim**](https://github.com/saecki/crates.nvim) - A neovim plugin that helps managing [crates.io](https://crates.io/) dependencies
* [**nvim-teal-maker**](https://github.com/svermeulen/nvim-teal-maker) - Neovim plugin that adds plugin support for teal language

## Your project here!

Are you using Teal? Do you have a project or know one using it? Send a pull request to this repository
or say hello at the [Gitter chat](https://gitter.im/teal-language/community) and let us know!
