vim-peepopen
=============

A plugin for the Vim text editor. PeepOpen provides fuzzy search of filenames and paths in a programming project.

### About this fork

The only difference with this fork is the folder structure to make it work with [Vundle][vundle].

Installation
------------

Get the PeepOpen.app and open it at least once to approve the Mac OS X security dialog.

[Vundle][vundle]:

Add `Bundle 'twe4ked/vim-peepopen'` to your `.vimrc` then start vim and run `:BundleInstall`.

Standard:

Copy `peepopen.vim` to your `~/.vim/plugin` directory.

With Tim Pope's [Pathogen](http://github.com/tpope/vim-pathogen):

Copy the entire `vim-peepopen` plugin directory to your `~/.vim/bundle` directory.

Usage
-----

`<Leader>p` opens the current project directory with the PeepOpen application.

Use the [vim-rooter](http://github.com/airblade/vim-rooter) plugin for automatic assignment of the current working directory for projects stored in Git.

(Leader is mapped to '\' by default)

Credits
-------

- Initial Vim Plugin by [Andrew Stewart](http://www.airbladesoftware.com/).
- Some plugin boilerplate from [Rein Henrichs](http://reinh.com/).

[vundle]: https://github.com/gmarik/vundle
