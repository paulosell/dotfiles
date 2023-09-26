# oh-my-zsh

Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.

## Requisites

- A Unix-like operating system: macOS, Linux, BSD. On Windows: WSL2 is preferred, but cygwin or msys also mostly work.
- [Zsh](https://www.zsh.org) should be installed (v4.3.9 or more recent is fine but we prefer 5.0.8 and newer). If not pre-installed (run `zsh --version` to confirm), check the following wiki instructions here: [Installing ZSH](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
- `curl` or `wget` should be installed
- `git` should be installed (recommended v2.4.11 or higher)

## Instalation

- Install zsh
```shell
$ apt-get install zsh
$ zsh --version   
zsh 5.8.1 (x86_64-ubuntu-linux-gnu)
```
- Set zsh as default shell
```shell
$ chsh -s $(which zsh)
```
- Log out and log back in again to use your new default shell
- Test if zsh is the new default shell
```shell
$ echo $SHELL
/usr/bin/zsh
```
- Install oh-my-zsh

| Method    | Command                                                                                           |
| :-------- | :------------------------------------------------------------------------------------------------ |
| **curl**  | `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |
| **wget**  | `sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`   |
| **fetch** | `sh -c "$(fetch -o - https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |

## Plugins

I'm currently using only [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) and [sudo](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/sudo) for plugins and [awsomepanda](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#awesomepanda) as theme. :smile:
