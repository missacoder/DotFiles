<div align="center">

# DotFiles
**NVIM setup tailored my own coding style and needs**

[![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://www.lua.org)
[![NeoVim](https://img.shields.io/badge/NeoVim-57A143?style=for-the-badge&logo=neovim&logoColor=white)](https://neovim.io)

</div>

---

## 📋 Overview

This repository contains my personal **.dotfiles configuration**, crafted for my own dev experience. It features my configurations for things such as my window-manager, neovim, etc. It includesseveral plugins and a modern minimal and efficient aesthetic that enhances my productivity.

<div align="center">
  <img src="https://via.placeholder.com/800x400?text=NeoVim+Config+Screenshot" alt="NeoVim Config" />
</div>

---

## 📦 Plugin List Nvim

<details>
<summary><b>Core Plugins</b> (Click to expand)</summary>

- **lazy.nvim** - Plugin manager
- **nvim-lspconfig** - LSP client configuration
- **mason.nvim** - LSP installer
- **nvim-treesitter** - Syntax parsing
- **telescope.nvim** - Fuzzy finder
- **nvim-cmp** - Completion engine

</details>

<details>
<summary><b>UI & Navigation</b> (Click to expand)</summary>

- **nvim-tree.lua** - File explorer
- **lualine.nvim** - Status line
- **bufferline.nvim** - Buffer tabs
- **which-key.nvim** - Keybinding helper
- **indent-blankline.nvim** - Indentation guides

</details>

<details>
<summary><b>Editing & Productivity</b> (Click to expand)</summary>

- **vim-surround** - Surround operations
- **vim-commentary** - Easy commenting
- **nvim-autopairs** - Auto bracket pairing
- **gitsigns.nvim** - Git integration
- **vim-fugitive** - Git commands

</details>

---

## 🎨 Customization

### Themes
#### Sway
#### Nvim

Edit `lua/plugins/ui.lua`:

```lua
return {
  {
    "folke/tokyonight.nvim",
    lazy = false,
    priority = 1000,
    config = function()
      vim.cmd.colorscheme("tokyonight-night")
    end,
  },
}
```
---

## 🤝 Contributing

Feel free to fork this repository and customize it to your needs. If you have suggestions feel free to submit a pull request or message me directly!
