Tree-sitter CLI
===============

[![Build Status](https://github.com/tree-sitter/tree-sitter/workflows/CI/badge.svg)](https://github.com/tree-sitter/tree-sitter/actions)
[![Build status](https://ci.appveyor.com/api/projects/status/vtmbd6i92e97l55w/branch/master?svg=true)](https://ci.appveyor.com/project/maxbrunsfeld/tree-sitter/branch/master)

[![crates.io](https://img.shields.io/crates/v/tree-sitter-cli.svg)](https://crates.io/crates/tree-sitter-cli)
[![crates.io](https://img.shields.io/crates/dv/tree-sitter-cli.svg)](https://crates.io/crates/tree-sitter-cli)
[![crates.io](https://img.shields.io/crates/dr/tree-sitter-cli.svg)](https://crates.io/crates/tree-sitter-cli)

[![NPM Version](http://img.shields.io/npm/v/tree-sitter-cli.svg?style=flat)](https://www.npmjs.org/package/tree-sitter-cli)
[![NPM Downloads](https://img.shields.io/npm/dm/tree-sitter-cli.svg?style=flat)](https://npmcharts.com/compare/tree-sitter-cli?minimal=true)
[![Install Size](https://packagephobia.now.sh/badge?p=tree-sitter-cli)](https://packagephobia.now.sh/result?p=tree-sitter-cli)

The Tree-sitter CLI allows you to develop, test, and use Tree-sitter grammars from the command line. It works on MacOS, Linux, and Windows.

### Installation

You can install the `tree-sitter-cli` with `cargo`:

```sh
cargo install tree-sitter-cli
```

or with `npm`:

```sh
npm install tree-sitter-cli
```

You can also download a pre-built binary for your platform from [the releases page](https://github.com/tree-sitter/tree-sitter/releases/latest).

### Dependencies

The `tree-sitter` binary itself has no dependencies, but specific commands have dependencies that must be present at runtime:

* To generate a parser from a grammar, you must have [`node`](https://nodejs.org) on your PATH.
* To run and test parsers, you must have a C and C++ compiler on your system.

### Commands

* `generate` - The `tree-sitter generate` command will generate a Tree-sitter parser based on the grammar in the current working directory. See [the documentation](http://tree-sitter.github.io/tree-sitter/creating-parsers) for more information.

* `test` - The `tree-sitter test` command will run the unit tests for the Tree-sitter parser in the current working directory. See [the documentation](http://tree-sitter.github.io/tree-sitter/creating-parsers) for more information.

* `parse` - The `tree-sitter parse` command will parse a file (or list of file) using Tree-sitter parsers.
