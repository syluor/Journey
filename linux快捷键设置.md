# linux快捷键设置
https://zsh.sourceforge.io/Guide/zshguide04.html 如何给 shell 自定义快捷键

https://zhuanlan.zhihu.com/p/483983008 如何给 shell 自定义快捷键

https://www.runoob.com/w3cnote/bash-shortcut.html binkkey教程
## 复制粘贴
gnome默认终端的复制快捷键是ctrl+shift+c，如果改为ctrl+c的话就覆盖了终端驱动设置的ctrl+c（取消），因此不应该更改为ctrl+c 
https://unix.stackexchange.com/questions/746251/zsh-bindkey-map-ctrlc-to-ctrlp

gnome应用默认复制键是ctrl+c，无法更改。
- 鼠标侧键改为ctrl+c
- 修改 终端复制快捷键不变（ctrl+shift+c），粘贴改为ctrl+v
## shell快捷键
>bindkey '^f' backward-word

>bindkey '^j' forward-word

>bindkey '^w' kill-word
