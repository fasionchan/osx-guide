.. homebrew
    FileName:   brew.rst
    Author:     Fasion Chan
    Created:    2018-03-22 19:46:42
    @contact:   fasionchan@gmail.com
    @version:   $Id$

    Description:

    Changelog:

.. meta::
    :description lang=zh:
        Homebrew是OSX下非常好用的装包工具，安装只需要一条命令：
        /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
        通过brew安装软件包，也只需要一条命令：
        brew install git
        为避免因Github限制而失败，可以申请一个Github API Token。
    :keywords: homebrew, brew, brew install, brew失败

========
Homebrew
========

在 `OSX` ，主要通过 `App Store` 购买并安装应用软件。
这对普通用户来说，已经够用。

然而，做程序开发，需要安装很多工具以及软件库， `App Store` 就爱莫能助了。
这时，便要借助于本文的主角—— `Homebrew <https://brew.sh/>`_ 。

.. figure:: /_images/devenv/homebrew/485fd1b18f2335969fca0e16f7f69193.png
    :width: 64px

`Homebrew <https://brew.sh/>`_ 号称 `OSX` 缺失的包管理工具，
其功能及用法类似于 `Debian` 下的 `apt` 以及 `CentOS` 下的 `yum` 。
通过 `Homebrew <https://brew.sh/>`_ ， `OSX` 用户可以非常方便地管理软件包。
以安装 `git` 为例：

.. code-block:: shell-session

    fasion@MacKhaos:~ $ brew install git

安装
====

打开终端，运行以下命令即可完成安装：

.. code-block:: shell

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

安装过程中需按提示输入密码。

使用
====

以安装 `Git` 为例：

.. code-block:: shell-session

    fasion@MacKhaos:~$ brew install git
    Updating Homebrew...
    ==> Auto-updated Homebrew!
    Updated 1 tap (homebrew/core).
    ==> Updated Formulae
    chamber             heroku              lmod                mypy

    ==> Downloading https://homebrew.bintray.com/bottles/git-2.16.3.high_sierra.bott
    [#######################################################################] 100.0%
    ==> Pouring git-2.16.3.high_sierra.bottle.tar.gz
    ==> Caveats
    Bash completion has been installed to:
      /usr/local/etc/bash_completion.d

    zsh completions and functions have been installed to:
      /usr/local/share/zsh/site-functions

    Emacs Lisp files have been installed to:
      /usr/local/share/emacs/site-lisp/git
    ==> Summary
    🍺  /usr/local/Cellar/git/2.16.3: 1,497 files, 34.5MB

    fasion@MacKhaos:~$ git --version
    git version 2.16.3

使用强大的 `Homebrew <https://brew.sh/>`_ ，一行代码便搞定了 `Git` 的安装！

高级配置
========

Github API Token
----------------

`Homebrew` 依赖 `Github <https://github.com/>`_ 提供服务。
频繁操作时，可能会因为 `Github` 限制而失败。

解决方案是申请一个 `API Token` ，并设置到环境变量 ``HOMEBREW_GITHUB_API_TOKEN`` ：

.. code-block:: shell

    export HOMEBREW_GITHUB_API_TOKEN="xxxx"

点击 `New personal access token <https://github.com/settings/tokens/new>`_ 可申请新的 `Token` ：

.. figure:: /_images/devenv/homebrew/012e1effcd0c8e79a85723786765b6be.png
    :width: 380px

填好描述之后，点击生成即可。
`Token` 生成后，要保管好，忘记了只能重新生成。

.. note::

    如果新 Token 只用于 Homebrew ，无须勾选任何权限。

下一步
======

.. include:: /_fragments/next-step-to-wechat-mp.rst

.. include:: /_fragments/wechat-reward.rst
