TODO - README is work in progress

INSTALL
-------
	clone to ~/.vim
	ln -s .vimrc ~/.vim/.vimrc
	run :BundleInstall to setup plugins


plugins managed with vundle - https://github.com/gmarik/vundle
	:help vundle

:scriptnames - list all sourced scripts

file type settings
:help vimfiles
:help ftplugin-overrule
:help after-directory
modify .vim/ftplugin/LANGUAGE.vim with settings

NerdTree - https://github.com/scrooloose/nerdtree.git
:NERDTree /path
ctrl+ww - change focus

folding
:help folding
za - expand/collapse

find/replace
:1,$s/SEARCH/REPLACE/g

reload vimrc
:so %	" % is currentfile
:so $MYVIMRC
