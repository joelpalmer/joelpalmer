![Neovim version](https://img.shields.io/badge/Neovim-0.6.x-57A143?style=plastic&logo=neovim)
![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
## Neovim + 🔭 = 💪 (Updated Oct 20, 2021)
**_News:_ [virtual vim conf live October 29th/30th](https://www.vimconf.live/) is almost here. Click the link to see the agenda and register. It's free! Tons of scheduled goodness!**


**Keymap to try:** _Grep through open files/buffers:_
```lua
-- Telescopic version of FZF's :Lines 🔭
vim.api.nvim_set_keymap(
  "n",
  ",l",
  [[<Cmd>lua require('telescope.builtin').live_grep({grep_open_files=true})<CR>]],
  { noremap = true, silent = true }
)
```
(Also, Telescope's Live Grep is _now_ **blazing** fast 🔥 🔭)
<details>
  <summary>Stats</summary>
  
![Metrics](https://github.com/joelpalmer/joelpalmer/blob/main/github-metrics.svg)
  
</details>

