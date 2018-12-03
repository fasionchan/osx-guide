.. RAR文件解压
    FileName:   unrar.rst
    Author:     Fasion Chan
    Created:    2018-12-03 17:49:16
    @contact:   fasionchan@gmail.com
    @version:   $Id$

    Description:

    Changelog:

.. meta::
    :description lang=zh:
        macOS自带的归档工具不支持rar格式，因此不能解压缩RAR文件。
        作为一枚程序猿，可以通过在终端中执行unrar命令来解决。
    :keywords: rar, unrar, osx, macos, osx unrar, macos unrar

===========
RAR文件解压
===========

`macOS` 自带的归档工具不支持 `rar` 格式，因此不能解压缩 `RAR` 文件。

unrar命令
=========

作为一枚程序猿，可以通过在终端中执行 `unrar` 命令来解决。
`unrar` 命令可通过包管理工具 :doc:`../devenv/homebrew` 进行安装：

.. code-block:: shell-session

    $ brew install unrar

命令安装完毕后， `cd` 至 `RAR` 文件所在目录并执行以下命令即可解压：

.. code-block:: shell-session

    $ unrar x xxxx.rar

还有另一种解压模式：

.. code-block:: shell-session

    $ unrar e xxxx.rar

这两种模式的区别是： `x` 模式保持文件路径；而 `e` 则不保持文件路径。
在压缩包有多个子目录而子目录内有同名文件的情况下，用 `e` 模式解压会产生冲突。
因此，一般更推荐使用前者进行解压。

下一步
======

.. include:: /_fragments/next-step-to-wechat-mp.rst

.. include:: /_fragments/wechat-reward.rst

.. include:: /_fragments/disqus.rst

.. comments
    comment something out below

