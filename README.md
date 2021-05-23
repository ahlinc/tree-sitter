# tree-sitter

[![Build Status](https://github.com/tree-sitter/tree-sitter/workflows/CI/badge.svg)](https://github.com/tree-sitter/tree-sitter/actions)
[![Build status](https://ci.appveyor.com/api/projects/status/vtmbd6i92e97l55w/branch/master?svg=true)](https://ci.appveyor.com/project/maxbrunsfeld/tree-sitter/branch/master)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4777203.svg)](https://doi.org/10.5281/zenodo.4777203)

##### Versions
[![NPM](http://img.shields.io/npm/v/tree-sitter-cli.svg?label=CLI%20-%20npm&color=gray)](https://www.npmjs.org/package/tree-sitter-cli)
[![crates.io](https://img.shields.io/crates/v/tree-sitter-cli.svg?label=CLI%20-%20crate:&color=gray)](https://crates.io/crates/tree-sitter-cli)

[![crates.io](https://img.shields.io/crates/v/tree-sitter-tags.svg?label=TAGS%20-%20crate:&color=gray)](https://crates.io/crates/tree-sitter-tags)
[![crates.io](https://img.shields.io/crates/v/tree-sitter-highlight.svg?label=HIGHLIGHT%20-%20crate:&color=gray)](https://crates.io/crates/tree-sitter-highlight)

[![binding:wasm:npm](http://img.shields.io/npm/v/web-tree-sitter.svg?label=binding:%20WASM%20-%20npm:&color=gray)](https://www.npmjs.org/package/web-tree-sitter)
[![binding:rust](https://img.shields.io/crates/v/tree-sitter.svg?label=binding:%20Rust&color=gray)](https://crates.io/crates/tree-sitter)
[![binding:node](http://img.shields.io/npm/v/tree-sitter.svg?label=binding:%20Node&color=gray)](https://www.npmjs.org/package/tree-sitter)
[![binding:python](http://img.shields.io/pypi/v/tree-sitter.svg?label=binding:%20Python&color=gray)](https://pypi.org/project/tree-sitter)
[![binding:haskell](http://img.shields.io/hackage/v/tree-sitter.svg?label=binding:%20Haskell&color=gray)](http://hackage.haskell.org/package/tree-sitter)
[![binding:ruby](http://img.shields.io/gem/v/tree-sitter.svg?label=binding:%20Ruby&color=gray)](https://rubygems.org/gems/tree-sitter)

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

- **General** enough to parse any programming language
- **Fast** enough to parse on every keystroke in a text editor
- **Robust** enough to provide useful results even in the presence of syntax errors
- **Dependency-free** so that the runtime library (which is written in pure C) can be embedded in any application

## Links

- [Documentation](https://tree-sitter.github.io)
- [Rust binding](lib/binding_rust/README.md)
- [WASM binding](lib/binding_web/README.md)
- [Command-line interface](cli/README.md)
