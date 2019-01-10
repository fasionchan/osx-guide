.. Homebrew安装详情
    FileName:   homebrew-install-detail.rst
    Author:     Fasion Chan
    Created:    2018-03-22 19:46:42
    @contact:   fasionchan@gmail.com
    @version:   $Id$

    Description:

    Changelog:

.. meta::
    :description lang=zh:
        /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
        brew update
        brew --help
    :keywords: osx, macos, mac, homebrew, brew, install

================
Homebrew安装详情
================

.. code-block:: shell-session

    fasion@MacKhaos:~$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ==> This script will install:
    /usr/local/bin/brew
    /usr/local/share/doc/homebrew
    /usr/local/share/man/man1/brew.1
    /usr/local/share/zsh/site-functions/_brew
    /usr/local/etc/bash_completion.d/brew
    /usr/local/Homebrew
    ==> The following new directories will be created:
    /usr/local/Cellar
    /usr/local/Homebrew
    /usr/local/Frameworks
    /usr/local/bin
    /usr/local/etc
    /usr/local/include
    /usr/local/lib
    /usr/local/opt
    /usr/local/sbin
    /usr/local/share
    /usr/local/share/zsh
    /usr/local/share/zsh/site-functions
    /usr/local/var
    ==> The Xcode Command Line Tools will be installed.

    Press RETURN to continue or any other key to abort
    ==> /usr/bin/sudo /bin/mkdir -p /usr/local/Cellar /usr/local/Homebrew /usr/local/Frameworks /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/opt /usr/local/sbin /usr/local/share /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var
    Password:
    ==> /usr/bin/sudo /bin/chmod g+rwx /usr/local/Cellar /usr/local/Homebrew /usr/local/Frameworks /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/opt /usr/local/sbin /usr/local/share /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var
    ==> /usr/bin/sudo /bin/chmod 755 /usr/local/share/zsh /usr/local/share/zsh/site-functions
    ==> /usr/bin/sudo /usr/sbin/chown fasion /usr/local/Cellar /usr/local/Homebrew /usr/local/Frameworks /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/opt /usr/local/sbin /usr/local/share /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var
    ==> /usr/bin/sudo /usr/bin/chgrp admin /usr/local/Cellar /usr/local/Homebrew /usr/local/Frameworks /usr/local/bin /usr/local/etc /usr/local/include /usr/local/lib /usr/local/opt /usr/local/sbin /usr/local/share /usr/local/share/zsh /usr/local/share/zsh/site-functions /usr/local/var
    ==> /usr/bin/sudo /bin/mkdir -p /Users/fasion/Library/Caches/Homebrew
    ==> /usr/bin/sudo /bin/chmod g+rwx /Users/fasion/Library/Caches/Homebrew
    ==> /usr/bin/sudo /usr/sbin/chown fasion /Users/fasion/Library/Caches/Homebrew
    ==> /usr/bin/sudo /bin/mkdir -p /Library/Caches/Homebrew
    ==> /usr/bin/sudo /bin/chmod g+rwx /Library/Caches/Homebrew
    ==> /usr/bin/sudo /usr/sbin/chown fasion /Library/Caches/Homebrew
    ==> Searching online for the Command Line Tools
    ==> /usr/bin/sudo /usr/bin/touch /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
    ==> Installing Command Line Tools (macOS High Sierra version 10.13) for Xcode-9.2
    ==> /usr/bin/sudo /usr/sbin/softwareupdate -i Command\ Line\ Tools\ (macOS\ High\ Sierra\ version\ 10.13)\ for\ Xcode-9.2
    Software Update Tool


    Downloading Command Line Tools (macOS High Sierra version 10.13) for Xcode
    Downloaded Command Line Tools (macOS High Sierra version 10.13) for Xcode
    Installing Command Line Tools (macOS High Sierra version 10.13) for Xcode
    Done with Command Line Tools (macOS High Sierra version 10.13) for Xcode
    Done.
    ==> /usr/bin/sudo /bin/rm -f /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
    ==> /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
    ==> Downloading and installing Homebrew...
    remote: Counting objects: 98632, done.
    remote: Total 98632 (delta 0), reused 0 (delta 0), pack-reused 98632
    Receiving objects: 100% (98632/98632), 22.49 MiB | 380.00 KiB/s, done.
    Resolving deltas: 100% (71684/71684), done.
    From https://github.com/Homebrew/brew
     * [new branch]          master     -> origin/master
     * [new tag]             0.1        -> 0.1
     * [new tag]             0.2        -> 0.2
     * [new tag]             0.3        -> 0.3
     * [new tag]             0.4        -> 0.4
     * [new tag]             0.5        -> 0.5
     * [new tag]             0.6        -> 0.6
     * [new tag]             0.7        -> 0.7
     * [new tag]             0.7.1      -> 0.7.1
     * [new tag]             0.8        -> 0.8
     * [new tag]             0.8.1      -> 0.8.1
     * [new tag]             0.9        -> 0.9
     * [new tag]             0.9.1      -> 0.9.1
     * [new tag]             0.9.2      -> 0.9.2
     * [new tag]             0.9.3      -> 0.9.3
     * [new tag]             0.9.4      -> 0.9.4
     * [new tag]             0.9.5      -> 0.9.5
     * [new tag]             0.9.8      -> 0.9.8
     * [new tag]             0.9.9      -> 0.9.9
     * [new tag]             1.0.0      -> 1.0.0
     * [new tag]             1.0.1      -> 1.0.1
     * [new tag]             1.0.2      -> 1.0.2
     * [new tag]             1.0.3      -> 1.0.3
     * [new tag]             1.0.4      -> 1.0.4
     * [new tag]             1.0.5      -> 1.0.5
     * [new tag]             1.0.6      -> 1.0.6
     * [new tag]             1.0.7      -> 1.0.7
     * [new tag]             1.0.8      -> 1.0.8
     * [new tag]             1.0.9      -> 1.0.9
     * [new tag]             1.1.0      -> 1.1.0
     * [new tag]             1.1.1      -> 1.1.1
     * [new tag]             1.1.10     -> 1.1.10
     * [new tag]             1.1.11     -> 1.1.11
     * [new tag]             1.1.12     -> 1.1.12
     * [new tag]             1.1.13     -> 1.1.13
     * [new tag]             1.1.2      -> 1.1.2
     * [new tag]             1.1.3      -> 1.1.3
     * [new tag]             1.1.4      -> 1.1.4
     * [new tag]             1.1.5      -> 1.1.5
     * [new tag]             1.1.6      -> 1.1.6
     * [new tag]             1.1.7      -> 1.1.7
     * [new tag]             1.1.8      -> 1.1.8
     * [new tag]             1.1.9      -> 1.1.9
     * [new tag]             1.2.0      -> 1.2.0
     * [new tag]             1.2.1      -> 1.2.1
     * [new tag]             1.2.2      -> 1.2.2
     * [new tag]             1.2.3      -> 1.2.3
     * [new tag]             1.2.4      -> 1.2.4
     * [new tag]             1.2.5      -> 1.2.5
     * [new tag]             1.2.6      -> 1.2.6
     * [new tag]             1.3.0      -> 1.3.0
     * [new tag]             1.3.1      -> 1.3.1
     * [new tag]             1.3.2      -> 1.3.2
     * [new tag]             1.3.3      -> 1.3.3
     * [new tag]             1.3.4      -> 1.3.4
     * [new tag]             1.3.5      -> 1.3.5
     * [new tag]             1.3.6      -> 1.3.6
     * [new tag]             1.3.7      -> 1.3.7
     * [new tag]             1.3.8      -> 1.3.8
     * [new tag]             1.3.9      -> 1.3.9
     * [new tag]             1.4.0      -> 1.4.0
     * [new tag]             1.4.1      -> 1.4.1
     * [new tag]             1.4.2      -> 1.4.2
     * [new tag]             1.4.3      -> 1.4.3
     * [new tag]             1.5.0      -> 1.5.0
     * [new tag]             1.5.1      -> 1.5.1
     * [new tag]             1.5.10     -> 1.5.10
     * [new tag]             1.5.11     -> 1.5.11
     * [new tag]             1.5.12     -> 1.5.12
     * [new tag]             1.5.2      -> 1.5.2
     * [new tag]             1.5.3      -> 1.5.3
     * [new tag]             1.5.4      -> 1.5.4
     * [new tag]             1.5.5      -> 1.5.5
     * [new tag]             1.5.6      -> 1.5.6
     * [new tag]             1.5.7      -> 1.5.7
     * [new tag]             1.5.8      -> 1.5.8
     * [new tag]             1.5.9      -> 1.5.9
    HEAD is now at 2ec684a12 Merge pull request #3962 from commitay/cask-doctor
    ==> Tapping homebrew/core
    Cloning into '/usr/local/Homebrew/Library/Taps/homebrew/homebrew-core'...
    remote: Counting objects: 4696, done.
    remote: Compressing objects: 100% (4495/4495), done.
    remote: Total 4696 (delta 53), reused 633 (delta 16), pack-reused 0
    Receiving objects: 100% (4696/4696), 3.81 MiB | 508.00 KiB/s, done.
    Resolving deltas: 100% (53/53), done.
    Tapped 4494 formulae (4,738 files, 11.9MB)
    ==> Cleaning up /Library/Caches/Homebrew...
    ==> Migrating /Library/Caches/Homebrew to /Users/fasion/Library/Caches/Homebrew.
    ==> Deleting /Library/Caches/Homebrew...
    Already up-to-date.
    ==> Installation successful!

    ==> Homebrew has enabled anonymous aggregate user behaviour analytics.
    Read the analytics documentation (and how to opt-out) here:
      https://docs.brew.sh/Analytics.html

    ==> Next steps:
    - Run `brew help` to get started
    - Further documentation:
        https://docs.brew.sh

    fasion@MacKhaos:~$ brew update
    Already up-to-date.

    fasion@MacKhaos:~$ brew --help
    Example usage:
      brew search [TEXT|/REGEX/]
      brew (info|home|options) [FORMULA...]
      brew install FORMULA...
      brew update
      brew upgrade [FORMULA...]
      brew uninstall FORMULA...
      brew list [FORMULA...]

    Troubleshooting:
      brew config
      brew doctor
      brew install -vd FORMULA

    Developers:
      brew create [URL [--no-fetch]]
      brew edit [FORMULA...]
      https://docs.brew.sh/Formula-Cookbook

    Further help:
      man brew
      brew help [COMMAND]
      brew home

下一步
======

.. include:: /_fragments/next-step-to-wechat-mp.rst

.. include:: /_fragments/wechat-reward.rst

.. include:: /_fragments/disqus.rst

.. comments
    comment something out below

