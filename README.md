concrete5 VimDict
-----------------

concrete5 dictionary file for vim
=================================

Copy concrete5.dict to

    ~/.vim/dict/concrete5.dict

Add to .vimrc

    autocmd FileType php set dictionary+=$HOME/.vim/dict/concrete5.dict

For Supertab you might need

    autocmd FileType php set complete+=k$HOME/.vim/dict/concrete5.dict
