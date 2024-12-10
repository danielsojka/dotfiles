# dotfiles

## How to run

1. Install chezmoi, for MacOS: `brew install chezmoi`
2. Setup personal chezmoi configuration file under `~/.config/chezmoi/chezmoi.toml` with following structure:

```toml
[data]
email = "your@email.com"
home = "/Users/your-user"
device-type = "personal | work"
```

3. Run `chezmoi init https://github.com/daniel.sojka/dotfiles.git`

