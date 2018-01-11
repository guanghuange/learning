# tmux的基本操作

## 前置操作 ctrl+b,下面所有的prefix均代表CTRL+b

### session 相关操作
* 查看/切换session
ctrl+b s
* 离开session
ctrl+b d
* 重命名session
ctrl+b $

* open session
tmux new -s basic

* detach session
tmux attach -t basic

* list session
tmux ls

* kill session
tmux kill-session -t basic

### Window相关操作
* c  创建新窗口
* w  列出所有窗口
* n  后一个窗口
* p  前一个窗口
* f  查找窗口
* ,  重命名当前窗口
* &  关闭当前窗口

### panel相关操作
* %  垂直分割
* "  水平分割
* o  交换窗格
* x  关闭窗格
* ⍽  左边这个符号代表空格键 - 切换布局
* q 显示每个窗格是第几个，当数字出现的时候按数字几就选中第几个窗格
* { 与上一个窗格交换位置
* } 与下一个窗格交换位置
* z 切换窗格最大化/最小化
