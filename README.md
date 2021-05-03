# .vim
This is my .vim folder . With creating this repo I've backed up all of my plugins. This repo does not contain my .virmc 
because I've already uploaded it on the "dotfiles" repo and its visibility is private.

To install my vim evironment on your machine write the following commands on the terminal-
git clone git@github.com:Morpheus2023/.vim.git ~/.vim (if using ssh). 

Whil installing create a symlink of the UltiSnips folder(the name of the symlink should be UltiSnips) from dotfiles repo because in the this .vim folder the UltiSnips folder is actually a symlink ,so Git wont be able stash its changes . Infact it has not even added the snippets files which are present inside it (the html.snippets and python.snippets files).
