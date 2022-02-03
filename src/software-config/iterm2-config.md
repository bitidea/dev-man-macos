# iTerm2 配置

## 1

https://github.com/ohmyzsh/ohmyzsh#basic-installation

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## 2

`Preferences` -> `Appearance` -> `General` -> `Theme` -> `Minimal`

## 3

`Preferences`  -> `Profiles` -> `Colors` -> `Color Presets` -> `Import` -> https://draculatheme.com/iterm

## 4

`Preferences` -> `Profiles` -> `Session` -> `Status bar Enabled` -> `Configure Status Bar`

## 5

https://github.com/denysdovhan/spaceship-prompt#oh-my-zsh

```bash
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
```

```bash
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
```

将 `~/.zshrc` 中的 `ZSH_THEME` 改成 `spaceship`
