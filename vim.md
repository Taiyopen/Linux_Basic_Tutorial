# vim 指令
## vim簡介
功能強大的文字編輯器，主打鍵盤操作，減少手部離開鍵盤操控滑鼠的時間。
## 安裝vim
```bash
sudo apt install vim
```

## 使用教學
用vim打開檔案
```bash
vim [檔案]
```
一開始進入「普通模式」，上下左右鍵可以移動光標

按`i`可以進入「插入模式」，可以開始編輯文件

按`ESC`回到普通模式

## 命令列模式
輸入冒號`:`(Shift + ;)會進入命令列模式，這時左下角會出現一個冒號

可以像終端機一樣輸入指令

:w

w 代表的是 存檔(write)

:q

q 代表的是 離開(quit)

:wq

兩者可以結合起來，代表存檔後離開


## 補充教材
補充：[vim參考連結](https://www.youtube.com/watch?v=LQVriYE3kxk&list=PLBd8JGCAcUAH56L2CYF7SmWJYKwHQYUDI)


# TMUX

## 簡介
使用者可以通過 tmux 在一個終端內管理多個分離的對談，窗口及面板，對於同時使用多個命令列，或多個任務時非常方便。
## 安裝
```bash
sudo apt install tmux
```
## 使用方法
開啟
```bash
tmux
```
水平分割視窗 `Ctrl + b` 然後按 `"`

垂直分割視窗 `Ctrl + b` 然後按 `%`

切換視窗 `Ctrl + b` 然後按 `上下左右鍵`

關閉視窗 輸入`exit`