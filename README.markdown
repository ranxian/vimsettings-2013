A wonderful vim configuration 
==========================

Requirements:
--------------------------

For taglist, you need ctags, which is included in cscope package in most linux distributions 


Install:
--------------------------

clone the repo to your ~/.vim 
	
	git clone https://github.com/yyk/vimsettings-2013.git ~/.vim

write just one line into your ~/.vimrc containing:

	echo "source ~/.vim/vimrc" >> ~/.vimrc

run ~/.vim/updateall.sh to update submodules from other external git repos.

	sh ~/.vim/updateall.sh 

you may also copy the content of ~/.vim/bashrcforvim to ~/.bashrc in case you need those features.
	
	cat ~/.vim/bashrcforvim >> ~/.bashrc
