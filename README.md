# Molokai Color Scheme for Vim

Molokai is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.

![Gray Background](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_normal_small_3.png)

![Molokai Original](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_original_small_3.png)

256-Color terminals are also supported, though there are some differences with the Gui version. Only the dark gray background style is supported on terminal vim at this time.

## Installation

Copy the file on your .vim/colors folder.

If you prefer the scheme to match the original monokai background color, put this in your .vimrc file: 
```
let g:molokai_original = 1
```

There is also an alternative scheme under development for color terminals which attempts to bring the 256 color version as close as possible to the the default (dark) GUI version. To access, add this to your .vimrc:
```
let g:rehash256 = 1
```

You can also alternative the popup menu color configuration in your .vimrc or \_vimrc file:
```
"不同配置下gvim 弹出窗口颜色不同
"alternative gui enviroment popmenu color set:
"(Olivedrab,Yellowgreen),(DarkMagenta,Purple),(DarkOrange3,DarkGoldenrod)
"(DarkOrange3,DarkMagenta),(OrangeRed1,Orange1),(Olive,Yellowgreen)
let PmenuGuibg="Olivedrab"
let PmenuSelGuibg="Yellowgreen"
"let PmenuSbarGuibg="Slategray"
"let PmenuThumbGuibg="Silver"

"不同配置下终端中vim弹出窗口颜色不同
"alternative cterm enviroment popmenu color set:
"(34,37),(DarkMagenta,93),(6,42),(2,100),(56,62)
"(130,136),(130,DarkMagenta),(202,214),(203,209)
"(26,32),(58,136),(62,68)
let PmenuCtermbg="34"
let PmenuSelCtermbg="37"
"let PmenuSbarCtermbg="233"
"let PmenuThumbCtermbg="7"
```

