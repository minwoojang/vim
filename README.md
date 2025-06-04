# vim
vim setting

my vim version 9.1




" Vim-Plug 초기화
call plug#begin('~/.vim/plugged')

" NERDTree 플러그인
Plug 'preservim/nerdtree'

" YouCompleteMe 플러그인
Plug 'ycm-core/YouCompleteMe'

Plug 'mattn/emmet-vim'

" Plug 'numirias/semshi'

" coc.nvim
" Plug 'neoclide/coc.nvim', {'branch': 'release'}


" 플러그인 설치 종료
call plug#end()

" NERDTree 기본 설정
nmap <C-n> :NERDTreeToggle<CR>

let g:ycm_python_binary_path = '/usr/bin/python3'
let g:ycm_auto_trigger = 1
set number
set backspace=indent,eol,start
set t_TI=
set t_TE=
set tabstop=4
set shiftwidth=4
set expandtab
set softtabstop=4
set t_8f=
set keyprotocol=
let &term=&term
let g:semshi_enable_insertion = 1
let g:semshi_auto_select = 1
syntax on
colorscheme default
