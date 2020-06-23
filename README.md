# gruvbox-xterm
Gruvbox colorscheme for xterm terminal emulator
Hello guys! this is my first time on github, i hope everybody like this work
Hey Morhetz, thanks to share this colorscheme for vim, this colorscheme inspired me to made this!

gruvbox vim colorscheme of Morhetz:

https://vimawesome.com/plugin/gruvbox

Me: fabio carneiro <fabiocarneiro@slackjeff.com.br>

My youtube Channel: youtube.com/fabiocarneiro  ( Audio is in Portuguese ).

Installation

1) create a configuration file to XTerm: 

$ touch .Xresources

2) Open this file whith anything text editor, like sublime-text, vs-code, leafpad, pluma, or other
and paste the code bellow:

XTerm*termName: xterm-256color

XTerm*vt100.locale: true

XTerm*vt100.saveLinew: 4096

XTerm*vt100.renderFont: true

XTerm*vt100.font: 7x13

XTerm*vt100.selectToClipboard: true

XTerm*vt100.translations: #override \ Shift Ctrl <Key> C: copy-selection(CLIPBOARD) \n\ Shift Ctrl <Key> V: insert-selection(CLIPBOARD) 

XTerm*background: #262626

XTerm*boreground: #ebdbb2

XTerm*color0:     #262628

XTerm*color8:     #928374

XTerm*color1:     #CC241D

XTerm*color9:     #fb4934

XTerm*color2:     #98971a

XTerm*color10:    #b8bb26

XTerm*color3:     #FF8F15

XTerm*color11:    #FFAF00

XTerm*color4:     #458588

XTerm*color12:    #83a598

XTerm*color5:     #b16286

XTerm*color13:    #d3869b

XTerm*color6:     #689d6a

XTerm*color14:    #8ec07c

XTerm*color7:     #a89984

XTerm*color15:    #ebdbb2


3) Save then run in Terminal Emulador the code bellow

$ rxdb .Xresources

4) ok, now re-open Xterm Terminal Emulator, and be happy xD

Obs: With this file you can use Ctrl+shift+c to copy selected text and Ctrl+shift+v to paste copied text, fonts are better and whith this colorscheme can you codding per hours and don't hurt your eyes! xD

