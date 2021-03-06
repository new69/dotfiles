# My .dotfiles colection :gem:

[![Dotfiles](https://img.shields.io/badge/dot-files-green.svg)](https://dotfiles.github.io/)

![My Terminal Colors](http://i.imgur.com/oxyVDqE.png)


## Typeface

I use the open typeface  [Hack](http://sourcefoundry.org/hack/)


## OSX defaults

To configurate a new Mac with my default settings

```
$ source osx.sh
```

## Git

Remember to update your user **name** and **email** in the file `.gitconfig`.


## Vim, Bash

To config my [Vim](http://www.vim.org/) and [Bash](http://en.wikipedia.org/wiki/Bash_(Unix_shell)) settings just run the **install.sh**

It will copy all the **dot (.)** files for you

```
$ source install.sh
```

After that you can install the **Vim** plugins using [Vundle](https://github.com/gmarik/Vundle.vim)

```
$ vim +PluginInstall +qall
```


## Homebrew

To install all my commandline apps using [homebrew](http://brew.sh/)

```
$ source brew.sh
```


## Homebrew Cask

To install all my apps using [Homebrew Cask](http://caskroom.io/)

```
$ source cask.sh
```


## NPM

To install the [NPM](http://npmjs.com) global modules

```
$ source npm.sh
```


## Terminal Colors

The file **my.terminal** has the color settigns to use in the Mac's **Terminal** app

In terminal app go to **Preferences** > **Import** and choose the file to import. After that set it as **default**


## Author

| [![twitter/vitorleal](http://gravatar.com/avatar/e133221d7fbc0dee159dca127d2f6f00?s=80)](http://twitter.com/vitorleal "Follow @vitorleal on Twitter") |
|---|
| [Vitor Leal](http://vitorleal.com) |

