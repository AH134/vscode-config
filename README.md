# My Custom VSCode configuration
![](assets\hello.png)

This VSCode custom configuration is acts as a base config. It is primarily used as a starting point for multiple profiles.

# Usage
### Recommended
1. Press `ctrl+,` and click on the first icon on the top right
	1. Copy and paste the `settings.json` from `.vscode` into yours
2. Press `ctrl+shift+p` and search keybind then click on the json one
	1. Copy and paste the `keybindings.json` from `.vscode` into yours

### Note
If you are planning to use the .vscode file for the workspace
Be sure to add ```window.titleBar.style: "custom"``` and `vim.normalModeKeyBindingsNonRecursive: [...]` manually to the user `settings.json` file.

# Features
- Highlighted Color Yanking/Copying
- VIm Keybinds
	- If you're not familiar with vim, you should check out  `vim tutor` extension

# Base Extensions
- [Catppuccin](https://github.com/catppuccin/) Icon + Theme
- [Material Icon](https://github.com/PKief/vscode-material-icon-theme) Theme
- [Remote](https://github.com/microsoft/vscode-remote-release) WSL/SSH
- [VSCodeVim](https://github.com/VSCodeVim/Vim)

# Custom Keybinds

### Navigation
| **Keybind** |  **Description**   |
| ----------- | ------------------ |
|  `h`        |    Left arrow      |
|  `j`        |    Down arrow      |
|  `k`        |    Up arrow        |
|  `l`        |    Right arrow     |

### Auto-Complete Menu Scrolling
- Most other menu will also use these keybinds
- eg. quickOpen `shift+p / ctrl+shift+p`

| **Keybind** | **Description**|
| ----------- | -------------- |
|  `Ctrl+j`   |  Down arrow    |
|  `Ctrl+k`   |   Up arrow     |

### Switch Between Buffers/Tabs
| **Keybind**    | **Description**    |
| -------------- | ------------------ |
|  `Tab`         | Go to next tab     |
|  `Shift Tab`   | Go to previous tab |

### LSP (Suggestions)
- When you use `gh` you can also use the navigation keybinds to scroll through the hover panel

| **Keybind** | **Description**   |
| ----------- | ----------------- |
|  `gd`   | Go to definition      |
|  `gpd`  | Peek definition       |
|  `gh`   | Show hover            |
|  `gi`   | Go to implementations |
|  `gpi`  | Peek implementations  |
|  `gq`   | Quick fix             |
|  `gr`   | Go to references      |
|  `gt`   | Go to type definition |
|  `gpt`  | Peek type definition  |

### File Explorer
| **Keybind** | **Description**|
| ----------- | -------------- |
|  `space+e`  |  Toggle file explorer   |
|  `space+f`  |  Focus editor without closing file explorer |
|  `j`        |     Down arrow           |
|  `k`        |     Up arrow             |
|  `a`        |     New file             |
|  `f`        |     New folder           |
|  `r`        |     Rename folder        |
|  `x`        |     Cut item             |
|  `y`        |     Copty item           |
|  `p`        |     Paste item           |

### Terminal
Coming soon...

# Extras
- Most of the keybinds are from this [post](https://dev.to/ansonh/10-vs-code-vim-tricks-to-boost-your-productivity-1b0n#1-smart-relative-line) by [Anson Heung](https://github.com/AnsonH)
