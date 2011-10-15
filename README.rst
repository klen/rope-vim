Ropevim, rope in vim
======================

**Use https://github.com/klen/python-mode. It`s more new and powerful plugin.**

Ropevim is a vim mode that allows you to use the rope_ library in vim to provide
features like python refactorings and code-assists.

This vim plugin allow you use the rope library in vim very easily.
There is no need to install the rope_ library on your system.
This plugin also adds vim help for rope_ commands.


Installation
------------

Just copy the plugin folders into your ~/.vim directory.

Alternatively, if you are using pathogen_, clone the plugin into your ``bundle``
folder.


Settings
--------

By default, rope_ auto assist is mapped to Control+Space. You can remap it. For
example: ::

    imap <buffer><Tab> <M-/>


.. _rope: http://rope.sourceforge.net/
.. _pathogen: https://github.com/tpope/vim-pathogen
