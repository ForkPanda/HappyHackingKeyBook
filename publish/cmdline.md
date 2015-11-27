# 推荐命令行组合：iTerm2 & 插件 & Zsh & Oh-My-Zsh

你能看到这里，默认你是这一套组合的用户。废话诸如 iTerm2 vs. Terminal 、 Zsh vs. Bash 就不费话了。

**另外，假设你是 Mac 用户。**

##0xFF  一键安装下面的东西

`curl -s 我还没有写这个脚本你敢信？| sh`

该脚本完成以下功能:

* 检查环境
* 安装 Homebrew
* 安装 Homebrew-Cask
* 安装 iTerm2
* 安装 Git
* 安装 Zsh
* 安装 Oh-My-Zsh
* 安装 Autojump
* Oh-My-Zsh 常用个人配置

##0x0 安装 [Homebrew](http://brew.sh/index_zh-cn.html)

> "Google:90% of our engineers use the software you wrote(Homebrew),but you can't invert a binary tree on a whiteboard so fuck off. --Max Howell"

#####依赖

* Xcode Commend Line

#####安装

命令行输入：

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

ps:各种卡顿见怪不怪，多试几次吧。

#####其他命令

* 帮助 `brew -help`
* 更新brew `brew update`
* 自检查 `brew doctor`
* 安装 `brew install PACKAGE_NAME`
* 卸载 `brew uninstall PACKAGE_NAME`
* 搜索 `brew search PACKAGE_NAME`
* 已安装列表 `brew list`
* 检查包更新 `brew outdated`
* 更新具体包 `brew upgrade [PACKAGE_NAME]`
* 打开主业 `brew home PACKAGE_NAME`
* 包信息 `brew info PACKAGE_NAME`
* 包依赖 `brew deps PACKAGE_NAME`


## 0x1 安装 [Homebrew-cask](https://github.com/caskroom/homebrew-cask)

> “To install, drag this icon…” no more!

##### 依赖

* Homebrew 最低版本 0.9.5 `$ brew --version` 

##### 安装

命令行输入：

`brew tap caskroom/cask && brew install caskroom/cask/brew-cask`

##0x2 安装 [iTerm2](https://www.iterm2.com/)

##### 依赖

* Homebrew-Cask

命令行运行：

`brew cask install iterm2`

##0x3 安装 [Zsh]()

#####依赖

* Homebrew
* Git

#####安装

命令行运行：

`brew install zsh zsh-completions`

## 0x4 安装 [Oh-My-Zsh](http://ohmyz.sh/)

#####安装

命令行运行：

`sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

## 0x5 [安装插件](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins)

#####插件包含 以 Autojump 为例子

命令行运行：

`brew autojump` 

