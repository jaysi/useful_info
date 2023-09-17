# useful_info
++ in ~/.vimrc [~/.config/nvim/init.vim]
set tabstop=4
syntax on " Syntax highlighting
set showmatch " Shows matching brackets
set ruler " Always shows location in file (line#)
set smarttab " Autotabs for certain code
set shiftwidth=4

++ arguments in bash shell
"$1" "$2" ...
"$@" -> all args

++ linux kernel style code formatting using indent
indent -nbad -bap -nbc -bbo -hnl -br -brs -c33 -cd33 -ncdb -ce -ci4 -cli0 -d0 -di1 -nfc1 -i8 -ip0 -l80 -lp -npcs -nprs -npsl -sai -saf -saw -ncs -nsc -sob -nfca -cp33 -ss -ts8 -il1 "$@"
