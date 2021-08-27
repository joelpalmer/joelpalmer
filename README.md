![Neovim](https://img.shields.io/badge/editor-Neovim-green?logo=neovim&style=plastic)
## Neovim + 🔭 = 💪 (Updated Aug 6, 2021)

The Neovim command that you need if you love to work on your configs (you know you do) is:
```lua
-- The greatest neovim command ever (other than :Telescope).
-- https://github.com/nvim-treesitter/playground#show-treesitter-and-syntax-highlight-groups-under-the-cursor
vim.api.nvim_set_keymap("n", ",t", ":TSHighlightCapturesUnderCursor<CR>", { noremap = true, silent = true })
```
![Metrics](https://github.com/joelpalmer/joelpalmer/blob/main/github-metrics.svg)
