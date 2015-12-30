# umake

A zsh plugin that enables shell completion for [Ubuntu Make](https://github.com/ubuntu/ubuntu-make).

## Installation

### For [oh-my-zsh](http://ohmyz.sh/) users

First, clone this repository into your oh-my-zsh custom plugins directory.

```shell
mkdir -p ~/.oh-my-zsh/custom/plugins
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/zlsun/umake.git
```

Then, configure the plugin in your **~/.zshrc** file:

```shell
plugins+=(umake)
```

### For [Antigen](https://github.com/zsh-users/antigen) users

Add the following line to your **~/.zshrc**.

```shell
antigen bundle zlsun/umake
```

### For [zgen](https://github.com/tarjoilija/zgen) users

Add the following line to your **~/.zshrc**.

```shell
zgen load zlsun/umake
```

## License

[MIT License](LICENSE)

