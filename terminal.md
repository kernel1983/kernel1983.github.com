# Terminal

在 GUI 世界保持 Terminal 风，键盘清脆的愉悦心情

## Vim

Vim 不得不经常用，虽然 vim 和 emacs 的大战已经旷世久远，并且未来还难舍难分，但是桌面上早已摆上了 vscode 和 sublime text

毕竟 vim 身材匀称，并且不喜欢把自己标榜成操作系统，渐渐的就成为了心电感应和远程打击的默认选择

Buffer 切换

    :ls             buffers
    :bn             next
    :bp             previous
    :bd             delete

分屏

    :vs             vsplit
    :sp             split

切屏

    C-w left
    C-w right
    C-w up
    C-w down

调整大小

    C-w #+
    C-w #-
    C-w #>
    C-w #<
    C-w #=

    :#winc +
    :#winc -
    :#winc >
    :#winc <
    :#winc =

关屏

    C-w q

## Tmux

有 screen 就已经够好了，但 tmux 依然给的工作带来了乐趣和惊喜

`~/.tmux.conf`:

    set -g prefix C-a

Attach 神同步了

    tmux a

当更小屏幕的设备进来了，有一种保护原则，屏幕区域会变小，也可以强制弹舱

    C-a S-s

新窗口

    C-a c

切窗

    C-a n
    C-a p

分屏

    C-a "          split vertically
    C-a %          split horizontally

切屏

    C-a left
    C-a right
    C-a up
    C-a down

调整大小

    C-a M-up
    C-a M-down
    C-a M-left
    C-a M-right

关屏

    C-a x

Detach

    C-a d

Session 的在实际情况下使用的不多

## Mosh

神器