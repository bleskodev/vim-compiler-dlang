# Vim compiler file for D (dlang)

Executes dub to compile Dub-based D projects when executing :make.

## Instalation:

### Manual installation

Drop dub.vim in ~/.vim/compiler directory.

Add the following line to .vimrc:

``` autocmd FileType d compiler dub```

## Usage:

Use standard :make command as with every other compiler.
