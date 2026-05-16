# Zed 编辑器配置

我的 [Zed](https://zed.dev) 编辑器个人配置。

## 特性

- 快捷键方案：JetBrains
- 主题：Catppuccin Mocha - No Italics
- 字体：JetBrainsMono Nerd Font + 更纱黑体 SC（中文回退）
- AI：Claude Sonnet 4.6（通过 claude-acp）+ Zed 自带代码预测
- 语言支持：Python (ruff/ty)、Rust (rust-analyzer)、TypeScript、JavaScript
- 自动保存（1 秒延迟）+ 保存时自动格式化
- 关闭遥测

## 使用方法

```bash
# 克隆仓库并创建符号链接
git clone https://github.com/oujuncan/zed-config.git
ln -sf $(pwd)/zed-config/settings.json ~/.config/zed/settings.json
```

## 依赖字体

```bash
brew install --cask font-jetbrains-mono-nerd-font font-sarasa-gothic
```

## 致谢

配置合并自：
- [WangWindow/dotfiles](https://github.com/WangWindow/dotfiles/blob/main/zed/settings.json)
- [jellydn/zed-101-setup](https://github.com/jellydn/zed-101-setup)
