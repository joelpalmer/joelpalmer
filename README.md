![Neovim version](https://img.shields.io/badge/Neovim-0.6.x-57A143?style=plastic&logo=neovim)
![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
## Neovim with Lua + 🔭 = 🎉 (Updated Nov 19, 2021)


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

