![Neovim version](https://img.shields.io/badge/Neovim-0.7.x-57A143?style=plastic&logo=neovim)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=plastic&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=plastic&logo=Brave&logoColor=white)
## Neovim with Lua + 🔭 = 🎉 (Updated Nov 30, 2021)

### NeoNews:
- [Neovim 0.6 has released](https://github.com/neovim/neovim/releases/tag/v0.6.0)
- 🔭 [Telescope's `builtin.file_browser` will be removed December 19th](https://github.com/nvim-telescope/telescope.nvim/issues/1470#issuecomment-974147513)
### RustyNews:
- [Rust 1.57.0 Stable Released](https://blog.rust-lang.org/2021/12/02/Rust-1.57.0.html) *_you should use nightly though_

<br>

**Keymap to try:** _Toggle `gitsigns` current line blame_
```lua
-- toogle virtual current line blame → <leader>hb for Full line blame
key_map("n", ",tb", [[<Cmd>lua require'gitsigns'.toggle_current_line_blame()<CR>]], { noremap = true, silent = true })
```
(Also, Telescope's Live Grep is _now_ **blazing** fast 🔥 🔭)
<details>
  <summary>Stats</summary>
  
![Metrics](https://github.com/joelpalmer/joelpalmer/blob/main/github-metrics.svg)
  
</details>

