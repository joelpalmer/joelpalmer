![Neovim version](https://img.shields.io/badge/Neovim-0.6.0-57A143?style=plastic&logo=neovim)
![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
## Neovim + 🔭 = 💪 (Updated Sep 21, 2021)
**News:** [galaxyline.nvim](https://github.com/NTBBloodbath/galaxyline.nvim) has a new and active maintainer!
**Grep through open files:**
```lua
-- Telescopic version of FZF's :Lines 🔭
vim.api.nvim_set_keymap(
  "n",
  ",l",
  [[<Cmd>lua require('telescope.builtin').live_grep({grep_open_files=true})<CR>]],
  { noremap = true, silent = true }
)
```

<details>
  <summary>Stats</summary>
  
![Metrics](https://github.com/joelpalmer/joelpalmer/blob/main/github-metrics.svg)
  
</details>

