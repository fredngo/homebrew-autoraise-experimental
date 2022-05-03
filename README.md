# Homebrew AutoRaise (Experimental)

Homebrew formula for the experimental focus-without-raise branch of https://github.com/sbmpost/AutoRaise

Install:

```zsh
brew tap fredngo/autoraise-experimental
brew install --HEAD fredngo/autoraise-experimental/autoraise
```

In order to suppress auto-raise, put the following in `~/.config/AutoRaise/config` (see [here](https://github.com/sbmpost/AutoRaise/issues/47#issuecomment-1115107566)):

```zsh
delay=0
```

Start the Service:

```zsh
brew services start autoraise
```

Stop the Service:

```zsh
brew services stop autoraise
```
