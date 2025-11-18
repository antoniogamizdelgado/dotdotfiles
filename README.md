
## Color palette

If you ever need the catppuccin color scheme in any platform, you can download it from [here](https://catppuccin.com/).

## Font

We use the [JetBrains Mono font](https://www.jetbrains.com/lp/mono/).

You can run

```
brew install --cask font-jetbrains-mono
```

To install them manually on MacOS, you need to add the ttf files to the `fonts` folder:

```
cp ~/Desktop/JetBrainsMono-2.304/fonts/ttf/* ~/Library/Fonts/
```

## Shell

Zsh.

## Terminal: Ghostty

- The terminal emulator is [Ghostty](https://ghostty.org/).
- Config can be found at `.config/ghostty`.
- Theme was taken from [here](https://github.com/catppuccin/ghostty/blob/main/themes/catppuccin-mocha.conf)
- With Oh My Zsh installed.
- Starship as prompt.


## Terminal multiplexer: Tmux

```
brew install tmux
```

We use [tmux tpm plugin manager](https://github.com/tmux-plugins/tpm). For that you need to run:

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Neovim

```
brew install neovim
brew install fzf
brew install lazygit
brew install ripgrep
brew install fd
```
