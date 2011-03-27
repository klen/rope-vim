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
" The maximum number of syntax errors to fix for code assists::
    let g:ropevim_codeassist_maxfixes=10

" If non-zero, ropevim tries to guess and
" open the project that contains the file on which a ropevim command
" is performed when no project is already open.::
    let g:ropevim_guess_project=1

" Tell ropevim to use vim's complete function in insert mode::
    let g:ropevim_vim_completion=1

" Shows whether to enable autoimport:: 
    let g:ropevim_enable_autoimport=1
    let g:ropevim_autoimport_modules = ["os", "shutil"]


Note
-----

Rope auto assist mapped in Control+Space keys. You can remap it. Example: ::

    imap <buffer><Tab> <M-/>


.. _rope: http://rope.sourceforge.net/
.. _pathogen: https://github.com/tpope/vim-pathogen
