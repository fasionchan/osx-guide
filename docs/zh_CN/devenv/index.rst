.. 开发环境
    FileName:   index.rst
    Author:     Fasion Chan
    Created:    2018-03-22 18:18:53
    @contact:   fasionchan@gmail.com
    @version:   $Id$

    Description:

    Changelog:

========
开发环境
========

“工欲善其事，必先利其器。”

本部分内容介绍如何将 `OSX` 打造成高效的编程利器，为开发工作打好基础。

首先是 `xcode` 。就算暂时还用不上，之后也极有可能需要用到。
因此，新机子拿到手后，不管三七二十一，先装上再说：

.. code-block:: shell-session

    $ xcode-select --install

:doc:`homebrew` 是 `OSX` 下的 **包管理工具** ，强烈推荐装上。

:doc:`iterm2` 是一个功能十分强大的 **终端** 软件，颜值也高，同样强烈推荐。

`coreutils <http://www.gnu.org/software/coreutils/>`_ 是
`GNU核心工具组 <https://zh.wikipedia.org/zh-hans/GNU%E6%A0%B8%E5%BF%83%E5%B7%A5%E5%85%B7%E7%BB%84>`_ ，
提供了大量常用命令。
装上 `coreutils` 后，那些熟悉的 `Linux` 命令便出现在 `OSX` 上！
借助 :doc:`homebrew` ，安装过程毫不费力：

.. code-block:: shell-session

    $ brew install coreutils

.. note::

    `OSX` 虽然也是一种 `Unix` 系统，与 `Linux` 还是有些差异。
    一方面，某些 `Linux` 命令， `OSX` 并没有提供；
    另一方面，有些命令行为跟 `Linux` 不太一样。

    例如， `ls` 这个非常常用的命令，行为就跟 `Linux` 不一样，用起来很不习惯。
    在学习一个 `OSX` 版本的 `ls` 命令显然没有必要，装上 `coreutils` 将 `Linux` 版的搬过来岂不更好？

    `coreutils` 提供的命令非常多，详细列表请查看：
    `coreutils文档 <http://www.gnu.org/software/coreutils/manual/html_node/index.html#toc-Operating-on-fields-1>`_ 。

下面是本部分内容的索引，请按需查阅：

.. toctree::
    :titlesonly:

    Homebrew <homebrew>
    iTerm2 <iterm2>
    Python <python>
