# useful_info
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
++ in ~/.vimrc [~/.config/nvim/init.vim]
set tabstop=4
syntax on " Syntax highlighting
set showmatch " Shows matching brackets
set ruler " Always shows location in file (line#)
set smarttab " Autotabs for certain code
set shiftwidth=4
set number
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.) Download a Nerd Font
2.) Unzip and copy to ~/.fonts
3.) Run the command fc-cache -fv to manually rebuild the font cache
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

++ arguments in bash shell
"$1" "$2" ...
"$@" -> all args
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

++ linux kernel style code formatting using indent
indent -nbad -bap -nbc -bbo -hnl -br -brs -c33 -cd33 -ncdb -ce -ci4 -cli0 -d0 -di1 -nfc1 -i8 -ip0 -l80 -lp -npcs -nprs -npsl -sai -saf -saw -ncs -nsc -sob -nfca -cp33 -ss -ts8 -il1 "$@"
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Remove CTRL-M characters from a file in UNIX
Description
How to remove CTRL-M characters from a file in UNIX.

You may need to do this when you import a text file from MS-DOS (or MS-Windows), and forget to transfer it in ASCII or text mode. Here are several ways to do it; pick the one you are most comfortable with.

    The easiest way is probably to use the stream editor sed to remove the ^M characters. Type this command: % sed -e "s/^M//" filename > newfilename
    To enter ^M, type CTRL-V, then CTRL-M. That is, hold down the CTRL key then press V and M in succession.
    You can also do it in vi: % vi filename
    Inside vi [in ESC mode] type: :%s/^M//g
    To enter ^M, type CTRL-V, then CTRL-M. That is, hold down the CTRL key then press V and M in succession.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
