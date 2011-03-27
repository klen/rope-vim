Ropevim, rope in vim
======================

Ropevim is a vim mode that uses rope_ library to provide features like
python refactorings and code-assists.

This vim plugin allow you use rope library in vim very easy.
Now you dont needed install rope libs in system.
Also this plugin add vim help with rope commands.


Installation
------------

Just copy plugin folders in your ~/.vim directory.

Or with pathogen_ clone plugin in your ``bundle`` folder


Settings
--------

Rope auto assist mapped in Control+Space keys. You can remap it. Example: ::

    imap <buffer><Tab> <M-/>


.. _rope: http://rope.sourceforge.net/
.. _pathogen: https://github.com/tpope/vim-pathogen
