# Ludtwig-Parser
Rust crate that parses twig / html / vue.js templating syntax into an AST (abstract syntax tree).
It does not conform to any spec and the input is required to be as idiomatic as possible.
For example missing closing tags in html result in a parsing error (even if browsers can interpret the html and reconstruct the closing tag).
This makes it possible to represent the template in a hierarchical AST.

## Disclaimer
This crate is still in early development and the API can break with any release until it reaches a stable v1.0.0 version (semantic versioning).
It is developed together with the [ludtwig](https://github.com/MalteJanz/ludtwig) CLI application for formatting and analyzing templating files.

## License
MIT - see LICENSE file.
