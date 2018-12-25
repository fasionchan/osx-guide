.. browsersync
    FileName:   browsersync.rst
    Author:     Fasion Chan
    Created:    2018-12-03 18:54:08
    @contact:   fasionchan@gmail.com
    @version:   $Id$

    Description:

    Changelog:

.. meta::
    :description lang=zh:
        browsersync启动一个小型服务器，以提供静态资源服务。
        通过browsersync提供的URL，用户可在浏览器中查看自己的网站，确认效果。
        此外，browsersync对静态文件进行监视，有变化时自动刷新浏览器。
        这样一来，任何代码修改都可实时反映到浏览器上，无需手动刷新，非常方便。
    :keywords: browsersync, osx, macos, 自动刷新, auto refresh

===========
browsersync
===========

进行前端开发时，有 **自动刷新工具** 辅助可以事半功倍。

很多前端框架和打包工具均提供自动刷新功能，无需额外配置。
如果只是做一些像编写静态网页之类的开发工作，就需要自己折腾一番了。

如果在某个目录下开发网页模板，编写 `html` 以及 `css` ，需要实时显示在浏览器上，如何实现呢？
答案是—— `browsersync`_ 。

`browsersync`_ 启动一个小型服务器，以提供静态资源服务。
通过 `browsersync`_ 提供的 `URL` ，用户可在浏览器中查看自己的网站，确认效果。
此外， `browsersync`_ 可对静态文件进行监视，有变化时自动刷新浏览器。
这样一来，任何代码修改均可实时反映到浏览器上，无需手动刷新，非常方便。

安装
====

`browsersync`_ 是一个 `npm` 包，安装方式非常简单：

.. code-block:: shell-session

    $ npm install -g browser-sync

.. code-block:: shell-session

    $ npm install --save-dev browser-sync

应用
====

.. code-block:: shell-session

    $ browser-sync start --server --files "css/*.css"

.. comments

    **

下一步
======

.. include:: /_fragments/next-step-to-wechat-mp.rst

参考文献
========

#. `省时的浏览器同步测试工具——browsersync <http://www.browsersync.cn/>`_

.. include:: /_fragments/wechat-reward.rst

.. include:: /_fragments/disqus.rst

.. _browsersync: https://www.browsersync.io/

.. comments
    comment something out below

