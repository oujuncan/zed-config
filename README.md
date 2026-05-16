# Zed Editor Configuration

My personal [Zed](https://zed.dev) editor configuration.

## Features

- Base keymap: JetBrains
- Theme: Catppuccin Mocha - No Italics
- Font: JetBrainsMono Nerd Font + Sarasa Gothic SC (Chinese fallback)
- AI: GitHub Copilot Chat (GPT-4.1) + Claude + Codex
- Languages: Python (ruff/ty), Rust (rust-analyzer), TypeScript, JavaScript
- Auto-save (1s delay) + Format on save
- Telemetry disabled

## Usage

```bash
# Clone and symlink
git clone https://github.com/oujuncan/zed-config.git
ln -sf $(pwd)/zed-config/settings.json ~/.config/zed/settings.json
```

## Credits

Merged from:
- [WangWindow/dotfiles](https://github.com/WangWindow/dotfiles/blob/main/zed/settings.json)
- [jellydn/zed-101-setup](https://github.com/jellydn/zed-101-setup)
