# The [ltreesitter](https://github.com/euclidianace/ltreesitter) module now includes the tree-sitter library so this is no longer needed!

# ltreesitter-ts
This library simply combines the excellent [ltreesitter](https://github.com/euclidianace/ltreesitter) with the [tree-sitter library](https://github.com/tree-sitter/tree-sitter/tree/master/lib) code in one nice package to be easily installable via LuaRocks.

- Current ltreesitter version: v0.0.7
- Current tree-sitter version: v0.24.4

## Install
It can be installed via LuaRocks:

```bash
luarocks install ltreesitter-ts
```

## Usage
It ends up being a drop-in replacement for `ltreesitter` after install:

```lua
local ltreesitter = require("ltreesitter")
```
