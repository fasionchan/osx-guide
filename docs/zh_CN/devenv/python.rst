.. Python
    FileName:   python.rst
    Author:     Fasion Chan
    Created:    2018-11-20 10:50:36
    @contact:   fasionchan@gmail.com
    @version:   $Id$

    Description:

    Changelog:

======
Python
======

大多数(类) `Unix` 系统均自带 `Python <https://python-book.readthedocs.io/zh_CN/latest/>`_ 环境：

.. code-block:: shell-session

    $ python
    Python 2.7.10 (default, Aug 17 2018, 17:41:52)
    [GCC 4.2.1 Compatible Apple LLVM 10.0.0 (clang-1000.0.42)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

系统自带 `Python` 环境比较老旧，一般都是 `2.7` 。
因此，想用新特性，必须按照新版本 `Python` 。
`Python官网` 提供了安装指引，但是 `OSX` 下使用 `Homebrew` 安装更为便捷。

安装Python3
===========

安装新 `Python` 前，需要先确保 `xcode` 已经安装就绪：

.. code-block:: shell-session

    $ xcode-select --install

之后运行以下两行命令即可：

.. code-block:: shell-session

    $ brew update
    $ brew install python

如果安装结果显示 `python` 未链接，则需要再运行以下命令：

.. code-block:: shell-session

    $ brew link python

至此， `Python` 安装完毕，可以用起来了：

.. code-block:: shell-session

    $ python3
    Python 3.7.1 (default, Nov  6 2018, 18:46:03)
    [Clang 10.0.0 (clang-1000.11.45.5)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>>
